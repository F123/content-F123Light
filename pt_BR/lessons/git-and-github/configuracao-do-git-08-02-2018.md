# Git

## Configuração do Git

Com o Git em seu sistema, basta configurá-lo para ter acesso à sua conta e repositórios no GitHub.
Você só precisa fazer uma vez. As configurações serão mantidas entre atualizações.
Você também poderá alterá-las a qualquer momento executando os comandos novamente.

O Git vem com uma ferramenta chamada git config que permite a você ler e definir variáveis de configuração que controlam todos os aspectos de como o Git opera.
Abra o terminal e digite os comandos a seguir:
*git config --global user.name "Seu Nome"*
*git config --global user.email "Seu e-mail"*
Estas configurações ficam alocadas no arquivo "~/.gitconfig", onde o ~ é o seu diretório home.
Quando precisar definir um nome e  e-mail específicos para um projeto, basta repetir os comandos sem o parâmetro "--global".

## Configuração do Repositório

Para enviar e receber as alterações corretamente, é necessário configurar o repositório no computador.
O primeiro passo é transformar uma pasta em um repositório.
Crie uma nova pasta e execute o comando:
*git init*
Um repositório vazio será iniciado.

## Adicionando o Endereço do Repositório

Agora, o endereço do repositório criado anteriormente no GitHub será configurado no terminal.
Execute o comando:
*git remote add origin https://github.com/usuario/repositorio.git*
A expressão "origin" será usada toda vez que for enviar alterações para esse repositório. Você pode atribuir outro nome, basta não se esquecer dele na hora de publicar novidades no GitHub.
Para ver a lista de todos os repositórios adicionados, digite:
*git remote*

### Exercícios

1. Abra o terminal e configure o Git para um único projeto.

2. Configure o Git de forma global, para todos os projetos que for criar.