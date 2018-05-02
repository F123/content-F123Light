# Configurações via Arquivo de Configuração

É possível alterar e personalizar as configurações do leitor de tela a partir de um arquivo de configuração.
O arquivo é:
*/etc/fenrir/settings/settings.conf*
A sintaxe dos comandos de configuração não são complexas, e o arquivo está dividido em quatro partes:
* Sessões: Uma sessão é um grupo de configurações. Geralmente está entre colchetes, como no exemplo: [sound]. Essa seria uma sessão de configurações de som.
* Configurações: São as configurações permitidas dentro de cada sessão. Geralmente são antecedidas por uma linha de comentário, explicando a configuração, e logo depois vem uma configuração com seu valor. Exemplo: driver=genericDriver. Essa configuração define um driver de som.
* Valores: São os valores que uma determinada configuração pode assumir. O valor fica sempre depois do sinal de igualdade. Como no exemplo acima, o nome do driver de som é o valor que a configuração driver recebeu.
* Comentários: São úteis para explicitar e detalhar as configurações e valores no arquivo. Toda linha iniciada pelo símbolo "#" é um comentário, e, portanto, desconsiderada pelo sistema.

### Exercícios

1. Abra o arquivo de configurações e localize uma sessão.

2. Analise as configurações e escolha uma para alterar o valor.

3. Comente a alteração feita no arquivo.