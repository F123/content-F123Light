# Rede

## Utilização do Wget

O Wget é muito útil para fazer downloads de endereços na Internet.
Suas principais vantagens é a possibilidade de restringir o tipo de arquivo a ser baixado e a possibilidade de retomar o download de onde parou, caso este seja interrompido.
Para fazer um download, basta fornecer o link do que desejar baixar.
Exemplo:
*wget http://www.site.com.br/download/arquivo-exemplo.zip*
Abaixo, seguem alguns parâmetros do Wget:
-r: Download recursivo.
-nd: Não baixar diretórios, apenas os arquivos.
-c: Retomar o download de onde parou.
Exemplo:
*wget -c http://www.site.com.br/download/arquivo-exemplo.zip*
--accept=: Baixar apenas arquivos especificados. Por exemplo, se quiser baixar apenas arquivos .zip, digite:
*wget -r --accept=zip http://www.site.com.br/download//*.
É possível especificar várias extensões, separando por vírgulas.
Se quiser fazer vários downloads, basta colocar todos os links em um arquivo e passar o caminho dele como parâmetro.
Exemplo:
*wget -i arquivo_com_urls.txt*

### Exercícios

1. Faça um download da Internet.

2. Faça download de arquivos com a mesma extensão.

3. Baixe arquivos sem seus diretórios.

4. Reuna vários links em um arquivo e faça download.