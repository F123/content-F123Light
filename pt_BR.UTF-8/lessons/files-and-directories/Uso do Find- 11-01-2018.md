# Trabalhando Com Diretórios E Arquivos

## Utilização do Find

O comando "find" é utilizado para pesquisar arquivos e diretórios no sistema sob vários critérios.

## Pesquisando Arquivos e Diretórios Pelo Nome

Para pesquisar um arquivo pelo nome no diretório atual, digite:
*find . -name Nome-ARQUIVO.txt*
Observação: Esse comando diferencia maiúsculas de minúsculas. Para ignorá-las, basta utilizar a letra "i" antes do parâmetro "name", da seguinte forma:
*find . -iname Nome-ARQUIVO.txt*

Para pesquisar um arquivo pelo nome em um diretório específico, digite:
*find diretorio -iname nome-arquivo.txt*

Para pesquisar um diretório pelo nome, digite:
*find / -type d -name NOME-do-Diretório*

## Pesquisando Arquivos Por Extensão

Para pesquisar arquivos pela sua extensão (txt, por exemplo), digite:
*find / -type f -name “*.txt”*

##Pesquisando Arquivos Por Tamanho

Para pesquisar arquivos por tamanho (maiores que 500 MB, por exemplo), digite:
*find diretorio -size +500M*
Observação: Se quiser o tamanho em GB, basta substituir o "M" por "G". O sinal de mais pesquisa por tamanhos maiores e o sinal de menos por tamanhos menores.

## Pesquisando Arquivos Com Modificações

Para pesquisar arquivos modificados recentemente (nos últimos 5 dias, por exemplo), digite:
*find /home/ -mtime -5*

### Exercícios

1. Pesquise arquivos pelo nome no diretório atual.

2. Pesquise arquivos pelo nome em outros diretórios ignorando letras maiúsculas.

3. Pesquise diretórios pelo nome ignorando letras maiúsculas.

4. Pesquise arquivos com a extensão "pdf".

5. Pesquise arquivos de tamanho superior a 1 GB.

6. Pesquise arquivos que foram modificados no último dia.