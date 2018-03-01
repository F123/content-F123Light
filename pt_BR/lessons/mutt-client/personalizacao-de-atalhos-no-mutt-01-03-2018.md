# Cliente Mutt

## Personalizando Atalhos

No Mutt, é possível personalizar os atalhos, atribuindo atalhos à sua escolha, substituindo os originais.
Isso é feito no arquivo .muttrc.
Se for feito no arquivo que fica na sua pasta de usuário, as alterações só funcionarão no seu usuário.
Se quiser aplicar as alterações em todo o sistema, basta fazer as alterações no arquivo de mesmo nome na pasta /etc.

O Mutt possui vários tipos de menus, e os atalhos devem ser associados a um ou mais deles. Para associar um atalho a vários menus, basta separá-los por vírgulas.
Alguns menus existentes são:
pager: É o modo usado para exibir dados de mensagens / anexos e listas de ajuda.
attach: É usado para acessar os anexos nas mensagens recebidas.
index: É a lista de mensagens contidas em uma caixa de correio.
compose: É a tela usada ao enviar uma nova mensagem.

Existem mais menus, que podem ser consultados nos manuais do programa.
A atribuição é feita da seguinte forma:
bind menu atalho função
Onde:
bind: Indica a atribuição de um atalho.
menu: Indica o menu a qual aquele atalho pertence, ou seja, qual o tipo de ação será executada (navegação, ajuda, anexos, etc.).
atalho: A combinação de teclas atribuída por você.
função: A função que o atalho executará naquele menu.
Nos manuais existe uma tabela completa de funções e teclas que podem ser atribuídas.
Para atribuir o control, por exemplo, e mais uma letra, basta escrever:
\cx
Onde:
c: Representa a tecla Control.
x: Representa a combinação atribuída, pode ser qualquer letra disponível.
Observação: No caso do Ctrl, maiúsculas e minúsculas são ignoradas tanto para ele quanto para a letra que o acompanha. Nos demais casos, maiúsculas e minúsculas não são ignoradas.
Segue abaixo alguns exemplos de atribuições:
bind pager j next-line
bind pager k previous-line
bind pager g top
bind pager G bottom
bind attach,index g first-entry
bind attach,index G last-entry
bind attach,index,pager \CD next-page
bind attach,index,pager \CU previous-page

Note que, no exemplo acima, a letra "g" foi usada várias vezes. Mas em alguns comandos estava maiúscula, e em outros minúscula. E, mesmo assim, note que elas se repetiram, mas para menus diferentes.

### Exercícios

1. Antes de qualquer alteração, faça uma cópia do seu arquivo .muttrc original para outra pasta. Dessa forma, qualquer alteração errada pode ser reparada, bastando copiar o arquivo original novamente para sua pasta de usuário.

2. Personalize seu arquivo .muttrc.

3. Utilize a tabela de funções, menus e teclas para criar suas próprias combinações.