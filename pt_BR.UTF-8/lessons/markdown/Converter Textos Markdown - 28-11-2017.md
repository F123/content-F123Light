# Introdução ao Markdown

## Convertendo Textos

Depois de aprender alguns símbolos que permitem formatar textos com o Markdown, agora será mostrado como converter esses textos para outros formatos.
Para converter, utilizaremos um programa chamado Pandoc.
Este programa aceita vários formatos, tanto de entrada (arquivo original que deseja converter), quanto de saída (arquivo que será gerado a partir do arquivo original).
Abaixo serão listados os principais formatos suportados:
Formatos de entrada: Markdown, TXT, HTML, EPUB,  DOC e DOCX (formato de arquivos do Word a partir da versão 2007).
Formatos de saída: Markdown, TXT, HTML, RTF, EPUB, DOC e DOCX.

## Convertendo o Arquivo

Vamos converter o arquivo já criado para outros formatos.
Para isso, abra o terminal, mude para o diretório onde está o arquivo e digite o seguinte comando:
*pandoc -o Testando Markdown.doc Testando Markdown.txt*
Esse comando está escrito da seguinte forma:
Primeiro vem o nome do programa, o Pandoc. Em seguida, vem o parâmetro "-o", que representa o arquivo de saída (output em inglês). Depois do parâmetro vem o nome e o formato do arquivo a ser gerado, e em seguida, o nome e extenção do arquivo original.
"Pandoc, o arquivo de saída (representado pelo parâmetro -o) será Testando Markdown.doc, e o arquivo a ser convertido é Testando Markdown.txt".
Esse é o comando para converter qualquer formato que desejar.
Observação: Os arquivos formatados com Markdown geralmente possuem a extenção (.md), mas também podem ser escritos em arquivos de texto simples (.txt).

### Exercícios

1. Abra o terminal, vá até o diretório onde salvou o arquivo das aulas anteriores e o converta para o próprio formato do markdown.

2. Converta o mesmo arquivo para formatos do Word (DOC e DOCX).

3. Tente fazer o inverso, converta os arquivos gerados novamente para Markdown (experimente mudar o nome do arquivo a ser gerado para não perder o original).

4. Converta para outros formatos disponíveis e veja o resultado.