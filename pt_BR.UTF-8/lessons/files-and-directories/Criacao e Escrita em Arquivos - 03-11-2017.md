# Trabalhando com Diretórios e Arquivos

## Criando e Escrevendo em Arquivos

Agora vamos criar um arquivo.
É possível criar um arquivo vazio usando o comando "touch".
Exemplo:
*touch "Bem Vindo.txt"*
Observação: Para criar arquivos com mais de uma palavra, digite o nome entre
"
(aspas).

Também podemos criar um arquivo e escrever um texto nele simultaneamente.
Primeiramente vamos escolher um texto de exemplo que irá dentro desse arquivo. Para que o terminal imprima a mensagem "Bem vindo"
podemos utilizar o comando echo, que irá imprimir esses dois argumentos ("Bem" e "vindo"):
*echo Bem vindo*
O resultado será a mensagem impressa no terminal.
Enquanto digitamos comandos no terminal, uma espécie de histórico está sendo criada, se clicarmos no botão de seta para cima, voltamos ao comando anterior que foi
executado. Usamos esse atalho para navegarmos pelos comandos, clicando mais vezes a seta pra cima, chegaremos a comandos digitados a mais tempo, a seta para baixo
também funciona para voltar para os comandos mais atuais no histórico.
Se quiser limpar o histórico de comandos, basta usar o comando:
*clear*
Mas antes disso, vamos usá-lo para voltar ao echo e passarmos apenas um argumento, colocando aspas duplas na mensagem que queremos imprimir:
*echo "Bem vindo"*
Mas o que queremos é executar esse comando redirecionando sua saída para um arquivo, para isso, utilizamos o caractere
>
(maior)
depois da mensagem seguido pelo nome do arquivo que queremos salvar a mensagem:
*echo "Bem vindo" > "Bem Vindo.txt"*
O terminal já não imprime mais a mensagem, ela foi redirecionada para o arquivo, veja que se buscarmos novamente a lista de arquivos e diretórios usando o ls, teremos
nosso arquivo Bem Vindo.txt listado.
Observação 1: Cuidado com o parâmetro
>
(maior),
pois este só adiciona conteúdo novo ao arquivo. Se for utilizado em um arquivo já escrito, o conteúdo anterior será apagado e substituído pelo atual.
Para escrever mais conteúdo em um arquivo já escrito, utilize dois sinais de maior em vez de um.
Exemplo:
*echo "ao curso" >> "bem vindo.txt"*
Agora o conteúdo contido no arquivo será:
**Bem vindo ao curso**
Veremos com detalhes na lição seguinte como ler arquivos inteiros ou trechos específicos deles.
Observação 2: Ao redirecionar uma mensagem para um arquivo com o comando "echo", se este não existir, será criado no momento da execução do comando.

### Exercícios

1. Troque de diretório.

2. Crie um arquivo vazio.

3. Liste o conteúdo do diretório e verifique se o arquivo foi criado.

4. Exiba uma mensagem no terminal.

5. Volte no histórico de comandos digitados e redirecione a mensagem digitada para o arquivo criado anteriormente.

6. Escreva outras mensagens no arquivo. Cuidado para não sobrescrever o conteúdo anterior.

7. Limpe o histórico do terminal.