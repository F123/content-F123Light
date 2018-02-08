# Discos e Partições

## Formatação de Disco

Formatar um disco é útil em várias situações: Quando for necessário reinstalar o sistema operacional, ou quando for preciso utilizar outro sistema de arquivos.
Para isso, será usado o programa mkfs.
O mkfs torna fácil formatar drives de vários tipos no Linux, tais como pendrives, cartões de memória, HDs, SSDs, etc.
O aplicativo permite várias opções e parâmetros de uso, que lhe conferem grande versatilidade para realizar a tarefa.
Observação: É importante ser cuidadoso. Não é possível desfazer a formatação depois.
Portanto, tenha sempre a certeza de que está formatando o drive certo.

## Como Formatar

Para formatar um pendrive, localizado em /dev/sdc1, por exemplo, deve-se primeiro desmontar o dispositivo com o comando:
*sudo umount /dev/sdc1*
Agora já é possível criar um sistema de arquivos nele.
O comando a seguir formata e apaga todo o conteúdo do dispositivo e cria um sistema de arquivos ext3 nele:
*sudo mkfs -t ext3 -l pendrive -I /dev/sdc1*
Se você não especificar o sistema de arquivos a ser construído no dispositivo, o mkfs vai usar o ext2 como padrão.
Os parâmetros usados tem o seguinte significado:
-t: Tipo de sistema de arquivos.
-n: Nome que será dado ao novo disco formatado.

Para usar o novo disco, é preciso montá-lo com o seguinte comando:
mount /dev/sdc1 /mnt -t ext3

### Exercícios

1. Utilize uma unidade de armazenamento vazia, como um pendrive, por exemplo, e formate.

2. Configure o sistema de arquivos ext4.

3. Utilize a unidade formatada para armazenar conteúdo.