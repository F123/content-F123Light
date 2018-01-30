# Permissões

## Alterando o Dono e / ou Grupo de Arquivos

O comando "chown" permite alterar o dono e/ou grupo de um arquivo. Os parâmetros do comando são:
-c: Informa quais arquivos estão sendo alterados.
-R: Altera, recursivamente, o dono e/ou grupo.
Exemplo:
*chown -Rc aluno:informatica teste*
O comando acima atribui o diretório teste e todos os arquivos dele ao usuário aluno e ao grupo informática.
Para alterar apenas o dono, digite:
*chown -Rc aluno teste*
Para alterar apenas o grupo, digite:
*chown -Rc :informatica teste*

### Exercícios

1. Altere o dono do diretório teste para seu nome e o grupo para informática.

2. Altere apenas o dono do diretório.

3. Altere apenas o grupo do diretório.