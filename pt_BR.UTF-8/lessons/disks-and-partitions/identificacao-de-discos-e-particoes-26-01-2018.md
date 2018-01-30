# Discos e Partições

## Identificação de Discos e Partições

No Linux, os dispositivos existentes em seu computador (como discos rígidos, pen-drives, tela, portas de impressora, modem, etc.,) são identificados por um arquivo referente a este dispositivo no diretório "/dev".
A identificação é feita da seguinte forma:
Diretório: Local onde são armazenados os dispositivos existentes.
Sigla: Identifica o tipo de disco (sd: SATA/SCSI, hd: IDE, fd: Disquete, etc.).
Letra: Identifica o disco rígido (A: 1º, B: 2º, etc.).
Número: Identifica o número da partição no disco rígido.
Veja alguns exemplos:
/dev/fd0: Primeira unidade de disquetes.
/dev/sda: Primeiro disco rígido SATA ou SCSI.
/dev/sda1: Primeira partição do primeiro disco rígido SATA ou SCSI.
/dev/sr0: Primeiro CD-ROM SATA ou SCSI.
/dev/hda: Primeiro disco rígido IDE.
/dev/hda1: Primeira partição do primeiro disco rígido IDE.
Caso utilize pen-drives, memória flash, as unidades serão detectadas como sdc, sdd, e assim por diante.

### Exercícios

1. Como os discos e partições são identificados no Linux?

2. Como seria identificada a segunda partição do segundo disco rígido SATA?

3. Como seria identificado um pen-drive?

4. Como seria identificada a terceira partição do primeiro disco rígido IDE?