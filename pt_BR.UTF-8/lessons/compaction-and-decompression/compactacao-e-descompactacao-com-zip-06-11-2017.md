# Compactação e Descompactação

## Compactação e Descompactação com zip

O Linux, por padrão, possui vários utilitários de compressão de arquivos. Compactar
arquivos e diretórios é uma boa prática para realização de "backups".
Veremos alguns comandos de compressão, começando pelo zip.

Vamos compactar o diretório Documentos criado anteriormente. Ele possui
atualmente dois arquivos de texto, dados e teste.
Dentro do diretório, primeiramente devemos usar o comando:
*cd ..*
Para voltar ao diretório pai.
Para compactar um arquivo com o zip, é necessário adicionar o parâmetro
"-r", caso contrário o arquivo compactado terá apenas um diretório vazio.
O comando é composto pelo zip, seu parâmetro de recursividade, o nome do arquivo zip que pretende gerar, e, por último, o diretório a ser compactado no arquivo.
Exemplo:
*zip -r doc.zip Documentos/*
O arquivo compactado doc.zip será gerado. Será exibido cada arquivo adicionado no arquivo compactado.

Se quiser verificar o conteúdo do arquivo compactado, pode usar o comando:
*unzip -l doc.zip*

Para descompactar o arquivo, use o seguinte comando:
*unzip doc.zip*

Se o arquivo for descompactado no mesmo local e o diretório ainda
existir, seu conteúdo será sobrescrito.
Experimente remover o diretório anteriormente compactado antes de
descompactar o arquivo gerado.
Lembre-se de usar o comando:
*ls*
para verificar os resultados.

Os comandos:
*zip*
e
*unzip*
são muito verborrágicos, ou seja, imprimem muita informação na tela. Se
preferir ocultar essas mensagens, utilize o parâmetro "-q".
Exemplos:
*zip -rq doc.zip Documentos/*
*unzip -q doc.zip*
No caso do "zip", os parâmetros "-q" e "-r" podem ficar juntos, formando "-rq".

### Exercícios

1. Escolha um diretório para compactar. A partir dele, volte para o diretório pai.

2. Compacte o diretório com todo o seu conteúdo.

3. Verifique o conteúdo do arquivo compactado.

4. Apague o diretório e descompacte o arquivo gerado.

5. Utilize o parâmetro e oculte as mensagens da tela.