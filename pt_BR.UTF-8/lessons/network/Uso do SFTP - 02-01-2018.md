# Rede

## Utilização do SFTP

FTP (Protocolo de Transferência de Arquivos) é um protocolo popular de transferência de arquivos entre sistemas.
SFTP (Protocolo de Transferência de Arquivos com SSH) é um protocolo separado, empacotado com SSH que funciona de forma similar em cima de uma conexão segura.
O FTP não é recomendado, já que não tem segurança.
Para se conectar com SFTP, basta seguir o mesmo estilo de conexão SSH da seguinte forma:
*sftp usuario@servidor*
Para navegar no SFTP os comandos são os mesmos do terminal.
Se precisar, digite:
*help*
para obter ajuda.
Os comandos exibirão o conteúdo do servidor. Mas e se quiser ver os arquivos e diretórios da sua máquina?
Isso é possível, caso contrário não seria interessante transferir arquivos do computador para o servidor e do servidor para o computador.
Para ver o conteúdo do seu computador, basta preceder cada comando pela letra "l".
Por exemplo, para exibir o conteúdo de um diretório local, digite:
*lls*
e para trocar de diretório, digite:
*lcd diretório*.

## Download de Arquivos e Diretórios

Para transferir um arquivo do servidor para o computador, utiliza-se o comando "get".
Digite:
*get nome-do-arquivo*.
Se você quiser copiar o arquivo com um outro nome, digite:
*get nome-do-arquivo novo-nome*.
Para transferir um diretório inteiro com seu conteúdo, digite:
*get -r Diretório*.
Observação: O parâmetro "-r" indica recursão. Sem ele, o diretório será copiado, mas sem seu conteúdo.

## Upload de Arquivos e Diretórios

Para transferir arquivos do computador para o servidor, o comando utilizado é o "put". Funciona de maneira semelhante ao "get".
Digite:
*put Nome-do-Arquivo*.
Para copiar o arquivo com um novo nome, digite:
*put Nome-do-Arquivo Novo-Nome*
Para transferir um diretório inteiro com seu conteúdo, digite:
*put -r Diretório*.

### Exercícios

1. Conecte-se com SFTP e navegue pelos diretórios.

2. Transfira um arquivo do servidor para seu computador.

3. Transfira um diretório do servidor para seu computador.

4. Transfira um arquivo do seu computador para o servidor.

5. Transfira um diretório do seu computador para o servidor.