# Trabalhando Com Diretórios E Arquivos

## Verificando o Diretório Atual e Seu Conteúdo

Para iniciar as atividades, é fundamental conhecer o terminal e seu conteúdo.

Ao abrir o terminal, estamos em algum diretório do sistema. Para descobrir o diretório, basta digitar o comando:
*pwd*	
A saída será algo parecido com:
**/home/roberta**

O nome depois de /home varia, de acordo com o usuário logado no sistema.

Para exibir a lista de diretórios e arquivos existentes dentro do diretório atual, basta utilizar o comando:
*ls*

Exemplo:
*ls*

Será exibido na tela algo como:
**Documentos**
**Teste.txt**

Note que há um diretório criado, o diretório Documentos. Também há o
arquivo Teste.txt. Posteriormente será ensinado como criar diretórios e arquivos.

O comando ls possui alguns outros parâmetros importantes, que serão listados abaixo:

-l
Exibe informações dos arquivos e diretórios, como tamanho, dono, grupo, data, etc.
Se for diretório, as informações começarão com a letra 'd'.
Exemplo:
*ls -l*
Todas as informações dos seus arquivos e diretórios serão exibidas.

-a
Lista arquivos e diretórios ocultos.
Exemplo:
*ls -a*
Todos os arquivos e diretórios ocultos serão exibidos.
Observação: Nomes de diretórios e arquivos ocultos começam com um
.
(ponto).

Os parâmetros também podem ser combinados, veja o exemplo:
*ls -la*
Este comando exibe as informações de todo o conteúdo, inclusive do conteúdo oculto.

Existe um atalho equivalente ao comando acima:
*ll*
Exibirá exatamente o mesmo conteúdo do comando anterior.

*
Exibe o conteúdo do diretório corrente e, caso exista diretórios dentro deste, exibe também o conteúdo deles.
Exemplo:
*ls * *

Existe também outro comando bem útil, que permite saber o tipo de cada arquivo.
Exemplo:
*file teste.txt*
A saída será algo parecido com:
**Teste.txt: ASCII Text**
Serve também para diretórios, veja o exemplo:
*file Documentos*
A saída será parecida com:
**Documentos: Directory**

Observação: No terminal, há diferença entre maiúsculas e minúsculas. Portanto, preste atenção ao digitar comandos, nomes de diretórios e arquivos.

### Exercícios

1. Descubra qual o diretório atual em que se encontra.

2. Exiba o conteúdo do diretório corrente.

3. Exiba informações dos arquivos e diretórios.

4. Exiba o conteúdo oculto dentro do diretório corrente.

5. Exiba informações de todos os arquivos e diretórios, incluindo os ocultos. Em seguida, faça o mesmo utilizando o atalho.

6. Verifique o tipo de cada conteúdo, inclusive diretórios.