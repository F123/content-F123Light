# Introdução ao Markdown

O Markdown é uma simples linguagem de marcação.
Com poucos e simples caracteres, é possível formatar seu texto em um simples editor, adicionar títulos, subtítulos, links, listas, etc., e depois converter para vários outros formatos.
Para converter esses textos, utilizaremos o programa Pandoc, que permite conversões entre vários formatos diferentes.

Começaremos com simples exemplos de formatação com Markdown. Depois, será ensinado como realizar a conversão.

## Parágrafos

Um parágrafo é uma linha de texto comum, não exige nenhum caractere especial. Basta dar alguns espaços antes de começar a escrever na linha para indicar que é um parágrafo.

## Títulos e Subtítulos

Os títulos são marcados com um "#" (cardinal ou jogo-da-velha) no início da sua linha. Os títulos vão do nível 1 a 6. O título de nível 1 é o que possui letras maiores, e quanto maior o nível, menor o título.
Ou seja, os demais podem ser considerados subtítulos.
Ou, supondo que tenhamos um título de nível 3 e outro de nível 4, o de nível 4 é um subtítulo em relação ao de nível 3.
O nível do título é definido pela quantidade de "#" antes dele. Ou seja, se tivermos:
*# Este Exemplo*
é de nível 1,
*## O Segundo Exemplo*
é de nível 2, e assim sucessivamente.

Antes de avançarmos, vale uma observação importante apartir de agora. Como já foi possível notar, o Markdown usa caracteres bastante comuns para formatar o texto. E se você quiser usar algum deles, como um "#", mas sem querer indicar um título?
Para isso, usamos o caractere "\" (barra invertida) antes do caractere que deseja usar. Assim, ele assume o sentido literal e não é interpretado pelo Markdown.
Se quiser usar a própria barra invertida, basta digitá-la duas vezes.

### Exercícios

1. Abra seu editor de textos favorito, crie um arquivo chamado "Testando Markdown.txt", por exemplo, e comece a escrever um texto com os primeiros caracteres de formatação ensinados.

2. Escreva  títulos e subtítulos.

3. Escreva o símbolo "#" antes de algum texto, mas faça com que não seja interpretado como caractere de formatação.

4. Salve o arquivo criado.