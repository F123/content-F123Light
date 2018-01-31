# Trabalhando Com Diretórios E Arquivos

## Uso do Diff

O comando "diff" compara o conteúdo de dois arquivos ou diretórios e exibe a diferença entre eles, e isso inclui arquivos compactados com gzip.
Os parâmetros aceitos no comando são:
-i: Ignora diferenças entre maiúsculas e minúsculas.
-E: Ignora diferenças de tabulação.
-b: Ignora diferenças de quantidade de espaços em branco.
-w: Ignora qualquer espaço em branco.
-B: Ignora linhas em branco.
-a: Compara os arquivos como arquivos de texto, mesmo que não sejam.
-q: Mostra apenas se o conteúdo é igual ou diferente.
-y: Mostra os arquivos em colunas, exibindo as diferenças.
-t: Converte tabulações em espaços.
-r: Compara recursivamente o conteúdo de diretórios.

O comando reporta, basicamente, o que é preciso alterar no arquivo que vem primeiro, para que fique igual ao último.

Para comparar dois arquivos, digite:
*diff arquivo1 arquivo2*
Se os arquivos forem diferentes, vai aparecer o número da linha onde isso ocorre, seguido de uma letra:
a: Indica que uma informação deve ser adicionada.
c: Indica que uma informação deve ser substituída.
d: Indica que uma informação deve ser deletada.
>: Indica que a informação depois dele deve ser incluída.
<: Indica que a informação depois dele deve ser excluída.
-: Separa informações.

Para comparar arquivos compactados, digite:
*zdiff arquivo1.gz arquivo2.gz*

### Exercícios

1. Compare dois arquivos e exiba a saída em colunas.

2. Compare dois arquivos ignorando diferença de maiúsculas e minúsculas.

3. Compare dois arquivos compactados ignorando diferenças entre maiúscula e minúscula, espaços e linhas em branco e exiba o resultado em colunas.