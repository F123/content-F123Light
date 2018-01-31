# Compactação e Descompactação

## Compactação e Descompactação Com Tar

Agora, veremos como trabalhar com compactação e descompactação com um padrão de compressão bastante popular no Linux, o "Tar".
Vale notar que o "tar" sozinho não serve para compactar arquivos. Ele apenas os empacota, afim de facilitar a transferência. Portanto,
utilizaremos o "tar" em conjunto com o "zip", o primeiro empacota e o segundo compacta.

## Compactação

Para compactar o diretório Documentos, utilizamos o seguinte comando:
* tar -cz Documentos > doc.tar.gz*
O parâmetro "-cz" indica que o arquivo "tar" será criado (-c), e será compactado pelo "zip" (-z) usando redirecionamento, representado pelo sinal de maior (>).
Observação: O "tar" já é automaticamente recursivo.

## Descompactação

Para descompactar o arquivo ".tar.gz" que foi criado, usamos o seguinte comando:
*tar -xz < doc.tar.gz*
Perceba que há apenas duas diferenças em relação ao comando de compactação, a presença de "-x" de "extract", para extrair os arquivos e a direção do
redirecionamento, representada pelo sinal de menor (<), que agora em vez de indicar saída de dados, indica entrada de dados.

## Eliminando o Redirecionamento

Trabalhar com redirecionamento não é uma boa ideia. Para resolver isso, o "tar" possui o parâmetro "-f".
Exemplo:
*tar -czf doc.tar.gz Documentos/*
Desse modo, primeiro temos o nome do arquivo a ser gerado, e depois o diretório a compactar.

Para descompactar, usamos o comando a seguir:
*tar -xzf doc.tar.gz*

O "tar" não é verborrágico por padrão, como o "zip". Mas se quiser exibir as informações, basta usar o parâmetro "-v".
Exemplo:
*tar -vxzf doc.tar.gz*

### Exercícios

1. Escolha um diretório para compactar e vá até seu diretório pai.

2. Compacte o diretório usando o "tar" com redirecionamento e exiba as informações na tela.

3. Remova o diretório e descompacte o arquivo com redirecionamento.

4. Remova o arquivo anterior e compacte o diretório sem redirecionamento.

5. Remova novamente o diretório e descompacte sem redirecionamento.