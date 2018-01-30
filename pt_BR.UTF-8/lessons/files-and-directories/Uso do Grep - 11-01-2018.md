# Arquivos e Diretórios

## Utilização do Grep

O comando "grep" é utilizado para buscar palavras específicas no nome de um arquivo ou em seu conteúdo.

## Pesquisando em Nomes de Arquivos

Para encontrar arquivos que tenham determinada palavra (teste, por exemplo), digite:
*ls | grep teste*
Observação: O "ls" é usado para listar os arquivos que tem a palavra correspondente.

Para pesquisar arquivos com extensão, digite:
*ls | -E grep teste.txt*
Observação: O parâmetro "E" é usado para que o "grep" aceite pontos e alguns outros caracteres.

## Pesquisando no Conteúdo dos Arquivos

Para pesquisar uma palavra ou frase contidas em um arquivo, digite:
*grep oi teste.txt*
O comando retorna todas as linhas do arquivo "teste.txt" que contenham "oi".
Observação: Para definir uma frase, coloque entre aspas, caso contrário o "grep" considera que a segunda palavra já faz parte do nome do arquivo. Por exemplo:
*grep "bom dia" teste.txt*
O comando retornará todas as linhas que contenham a frase "bom dia".

### Exercícios

1. Pesquise palavras em nomes de arquivos.

2. Pesquise palavras em nomes de arquivos com extensão.

3. Pesquise palavras dentro de arquivos.

4. Pesquise frases dentro de arquivos.