# Utilizando o Cliente IRC Irssi

## Abrindo e Fechando Conexão Com um Servidor

Nessa lição, será ensinado como utilizar o cliente Irssi para se comunicar utilizando o protocolo IRC.
Primeiramente, o IRC é um protocolo de comunicação usado principalmente em bate-papo. Para utilizá-lo, precisamos de um cliente para conectar a um servidor IRC, e será utilizado o Irssi.
Para instalar o Irssi, digite:
*sudo apt-get install irssi*

Depois de instalado, vamos nos conectar a um servidor.
Neste exemplo, usaremos o "FreeNode", um servidor bastante popular e com canais variados.
Antes disso, no entanto, mostrarei alguns parâmetros que podem ser usados na conexão:
*-c*
Esse parâmetro serve para indicar o endereço do servidor.
*-n*
Esse parâmetro indica seu apelido.
*-p*
Esse parâmetro indica a porta do servidor. De modo geral, não é necessário utilizá-lo.
Agora sim, vamos realizar a conexão. Veja o exemplo:
*irssi -c irc.freenode.net -n Roberta*
Estamos nos conectando ao endereço "irc.freenode.net" com o nick "Roberta".
Se quiser, pode primeiro abrir o Irssi, digitando o comando:
*irssi*
e depois se conectando ao servidor, digitando:
*/server irc.freenode.net*

Para encerrar uma conexão, digite:
*/disconnect*
Para fechar o Irssi, digite:
*/exit*
Para sair do servidor e fechá-lo ao mesmo tempo, também pode usar o comando:
*/quit*
Nesta aula, demonstramos como abrir e fechar conexão com um servidor IRC.

### Exercícios

1. Instale o Irssi no seu computador.

2. Execute o programa e se conecte a um servidor.

3. Desconecte e feche o Irssi.

4. Se conecte novamente, agora usando os parâmetros do Irssi.

5. Desconecte e feche o programa com um único comando.