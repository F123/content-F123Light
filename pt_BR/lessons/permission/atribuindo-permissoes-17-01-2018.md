# Permissões

## Atribuindo Permissões

O comando "chmod" atribui permições de acesso a um arquivo ou diretório.
Os parâmetros são:
u: Permissão para o dono (user).
g: Permissão para o grupo (group).
o: Permissão para usuários que não são membros do grupo (others).
a: Permissão para todos (all).
r: Leitura.
w: Gravação.
x: Execução (para arquivos) ou autorização de acesso (para diretórios).
Exemplo:
*chmod ug+rw teste.txt*
O comando define que o arquivo "teste.txt" tem permissão de leitura (r) e gravação (r) para usuários e membros do grupo.
Também é possível definir permissões com números:
0: Sem permissão.
1: Permissão de execução.
2: Permissão de gravação.
3: Permissão de gravação e execução.
4: Permissão de leitura.
5: Permissão de leitura e execução.
6: Permissão de leitura e gravação.
7: Permição de leitura, gravação e execução.
Os números são interpretados da direita para a esquerda, de modo que o último número definido no comando será a permissão para outros usuários, o do meio será para membros do grupo e o primeiro para o dono. Exemplo:
*chmod 764 teste.txt*
O comando acima define permissão de leitura, gravação e execução para o dono (7), leitura e gravação para os membros do grupo (6) e somente leitura para outros usuários (4).

### Exercícios

1. Defina permissão de leitura, gravação e execução para o dono do arquivo, para membros do grupo, e somente leitura para outros usuários.

2. Defina permissão de leitura, gravação e execução para o dono, somente leitura para o grupo e nenhuma permissão para outros usuários.

3. Defina permissão de leitura, gravação e execução para o grupo e somente leitura para outros usuários.

4. Defina permissão de leitura, gravação e execução para todos.

5. Defina permissão de leitura, gravação e execução para o dono, leitura e execução para membros do grupo e somente execução para todos os usuários.