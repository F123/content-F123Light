# Trabalhando Com Diretórios E Arquivos

## Exibindo Conteúdo de Arquivos

Para ler o conteúdo de arquivos no Terminal, usamos o comando:
*cat*
Exemplo:
*cat "Bem Vindo.txt"*
A saída do comando cat será o texto presente dentro do arquivo "Bem Vindo.txt".
Você também pode exibir o conteúdo com numeração de linhas, para isso utilize o parâmetro:
-n
Exemplo:
*cat -n "Bem Vindo.txt"*

Observação: Para todos os comandos envolvendo arquivos ou diretórios, existe a possibilidade de escrevermos apenas uma parte do nome deles e buscar um específico utilizando
a tecla "TAB". Se houver apenas um arquivo com o início do nome digitado, o terminal o preenche automaticamente ao apertarmos a tecla.

## Criando e editando com Cat

O comando "cat" tem outras funcionalidades bastante interessantes.
Com ele, é possível criar um arquivo e inserir dados com o parâmetro:
>
(maior).
Digite o seguinte comando:
*cat > teste*
Em seguida tecle "enter". O arquivo teste foi criado, e agora você pode inserir dados nele. Exemplo:
*Este é um arquivo de teste.*
Quando terminar de digitar, pressione o atalho "CTRL + D". O arquivo será salvo e a tela de edição será fechada.
Confira o resultado digitando:
*cat teste*
A saída será:
**Este é um arquivo de teste.**

## Concatenação

Também é possível utilizar o comando "cat" para concatenar conteúdo de
arquivos.
Vamos juntar o conteúdo do arquivo "Bem Vindo.txt" com o conteúdo do arquivo "teste" copiando para um novo arquivo.
Digite:
cat "Bem Vindo.txt" teste > arquivo_concatenado
Agora verifique o conteúdo do arquivo "arquivo_concatenado".
**Bem Vindo
Este é um arquivo de teste.**

## Exibindo início e fim de arquivos

Existem dois comandos que permitem exibir o início e o fim de um
arquivo, são eles "head" e "tail".
O "head" exibe as primeiras linhas de um arquivo. Por padrão, ele exibe as 10 primeiras, mas é possível aumentar ou diminuir esse valor com o parâmetro:
-n
seguido do número de linhas que deseja exibir.
Exemplo:
*head -n 1 arquivo_concatenado*
Ele exibirá apenas a primeira linha do arquivo.

O "tail" exibe o fim do arquivo e funciona como o "head". Possui o mesmo valor padrão de linhas exibidas e o mesmo parâmetro para mudar a exibição.
Exemplo:
*tail -n 1 arquivo_concatenado*
Ele exibirá apenas a última linha do arquivo.

### Exercícios

1. Verifique os arquivos existentes no diretório corrente.

2. Exiba o conteúdo dos arquivos existentes.

3. Crie um novo arquivo e insira dados nele.

4. Copie os dados de vários arquivos para um arquivo novo.

5. Leia o arquivo e numere as linhas.

6. Exiba:
a) As duas primeiras linhas do arquivo criado.
b) As três últimas linhas do arquivo criado.