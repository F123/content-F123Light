# Utilização de Alias

Um recurso muito interessante disponível no sistema operacional é o Alias.
Um Alias nada mais é do que um apelido para determinada instrução. É muito útil, especialmente, para comandos grandes e que necessitam ser usados com frequência.
Para conhecer a lista de alias disponível, digite:
*alias*

## Criando um Alias

É muito simples criar um alias. Por exemplo, em vez de digitar "clear" para limpar o terminal, poderíamos digitar apenas "cl".
Para isso, digite:
*alias cl='clear'*
O comando funciona da seguinte forma: Em primeiro lugar vem o apelido, e depois a instrução correspondente.

## Tornando o Alias Fixo

O único problema é que todo alias criado dessa forma só funcionará enquanto o seu usuário estiver ativo.
Para tornar um alias fixo no seu usuário, é preciso adicioná-lo no arquivo ".bashrc" que está na pasta home do usuário em questão.
Ao abrir o arquivo, note que existem várias configurações. Existe uma sessão específica para alias. Procure por:
"# some more ls aliases".
Adicione seu alias nessa sessão, com a mesma sintaxe já feita no terminal.
Salve o arquivo e saia do editor. Depois, tente executar seu alias.
Ele não funcionará, pois o terminal ainda não leu o arquivo para aplicar a configuração. Para isso, você pode encerrar o terminal e abrir novamente, ou então utilizar o comando "source" da seguinte forma:
*source .bashrc*
Agora sim, digite novamente seu alias e veja que funcionará normalmente.

### Exercícios

1. Atribua um apelido a um comando que julgue importante.

2. Edite o arquivo de configuração e torne seus aliases fixos.

3. Escolha um dos métodos para que o terminal leia o arquivo e aplique a configuração.