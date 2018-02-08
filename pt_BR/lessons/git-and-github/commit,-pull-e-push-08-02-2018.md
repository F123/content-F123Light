# Git

## Commit, Pull e Push

Agora que arquivos já foram adicionados e preparados para envio, será demonstrado como enviar esses arquivos para o GitHub.

## Commit

Um commit serve para documentar as alterações feitas naquele projeto.
Com os arquivos já preparados com o comando "git add .", é hora de fazer o primeiro commit:
*git commit -m "Escreva as alterações realizadas aqui".
Pronto, suas alterações já estão documentadas, prontas para serem publicadas.

## Pull

O pull serve para atualizar o repositório na sua máquina.
Se alguém já alterou o projeto antes de você, é necessário obter essas modificações antes de enviar as suas, para manter o repositório sempre atualizado.
Para isso, basta digitar:
*git pull*

## Push

Você modificou os arquivos, commitou descrevendo o que fez exatamente naquela modificação e agora precisa enviar tudo isso para o servidor.
O push empurra as suas modificações para o servidor, incluindo-as no histórico do projeto.
Execute:
*git push -u origin master*
Pronto, suas alterações foram enviadas para o repositório no GitHub.

### Exercícios

1. Faça seu primeiro commit e adicione um comentário.

2. Faça um pull do projeto.

3. Envie as alterações para o GitHub.