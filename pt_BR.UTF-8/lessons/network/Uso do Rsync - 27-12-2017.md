# Rede

## Utilização do Rsync

O  Rsync, como o nome sugere, é um programa que copia e sincroniza remotamente os dados entre duas máquinas.
O software herdou as propriedades de criptografia do protocolo SSH, o que torna sua transmissão de dados mais segura que o FTP.
Ele é excelente para copiar e fazer backup de informações.
Para funcionar, o Rsync e o SSH devem estar instalados em ambas as máquinas que vão se comunicar.
Alguns parâmetros do Rsync são:
-v: Verborrágico, o programa mostrará todas as ações na tela.
-r: Cópias de dados de maneira recursiva.
-a: Modo de arquivamento, o modo de arquivo permite a cópia de arquivos de forma recursiva e também preserva links simbólicos e permissões de arquivos.
-z: Arquivos serão comprimidos.
-h: Deixa a saída de forma legível para seres humanos.

## Copiando ou Sincronizando Diretórios Locais

A sintaxe fica da seguinte forma:
*rsync parâmetros origem destino*
Se o diretório de destino não existir, será criado automaticamente.

## Copiando ou Sincronizando Arquivos Locais Para um Servidor Remoto

Um pré-requisito para enviar seus arquivos para o servidor remoto é possuir uma conta de usuário no sistema.
A sintaxe fica da seguinte forma:
rsync parâmetros diretorio-local usuario@servidor:/diretorio-remoto*
A senha de usuário será solicitada. Basta digitá-la e os arquivos serão copiados.

## Copiando ou Sincronizando Arquivos do Servidor Para Sua Máquina Local

Esta situação também requer um login para autenticação no servidor,.

Se você entendeu como funciona o comando anterior, basta inverter a ordem dos parâmetros.
A sintaxe fica da seguinte forma:
*rsync parâmetros usuario@servidor:/diretorio-remoto diretorio-local*

### Exercícios

1. Copie ou sincronize seus arquivos no seu computador com o Rsync.

2. Copie  ou sincronize seus arquivos do computador com um servidor remoto.

3. Copie ou sincronize arquivos do servidor para seu computador.