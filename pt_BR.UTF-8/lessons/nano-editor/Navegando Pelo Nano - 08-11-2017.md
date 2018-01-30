# Editor Nano

## Navegando Pelo Editor

Depois de editar textos com o Nano, abordaremos alguns comandos de navegação pelo texto.

Confira a seguir:

Abrir vários arquivos simultaneamente:
*nano teste1 teste2*
Neste caso, apenas o primeiro será exibido. Para navegar entre os arquivos, utilize:
*Alt + >* (maior)
para navegar para frente, e:
*Alt + <* (menor)
para navegar para trás.

Abrir um arquivo em modo somente-leitura:
*nano -v teste*

Ir para uma linha e coluna específicas (com o arquivo já aberto):
*Alt + g* <número da linha, [número da coluna]>
O número da coluna é opcional.

Levar o cursor para o início e para o final do documento:
Para o início:
*Alt + \*
Para o final:
Alt + /

Rolar uma página para frente e para trás:
Para frente:
*^v*
Para  trás:
*^y*

Recortar a linha toda onde se encontra o cursor e guardá-la no buffer de transferência:
*^k*
Essa opção pode ser usada para apagar uma linha inteira.

Colar o conteúdo do buffer de transferência no local onde se encontra o cursor:
*^u*

Efetuar uma busca por palavra no texto:
*^w* <palavra> <enter>
Para repetir a busca pela mesma palavra, digite
*Alt + w*

A ajuda do programa:
*^g*

Selecionar texto (região) para copiar ou recortar trechos de texto:
Primeiramente, posicione o cursor no local a partir de onde o texto desejado será selecionado (a seleção pode ser feita tanto para frente quanto para trás)
Pressionar a combinação de teclas:
*Alt + a*
para ativar a marcação de textos (modo de seleção).
Efetuar a seleção usando as setas direcionais do teclado.
Após selecionar o texto desejado como mostrado no item #13, pressione agora a combinação de teclas
*Alt + 6*
para copiar o conteúdo selecionado para o buffer de transferência.
Para colar o texto em outro local dentro do arquivo, posicione o cursor no destino e use a combinação:
*^u*

Mostrar a posição atual do cursor dentro do texto, incluindo linha, coluna e número do caractere:
*^c*

Observação: Lembre-se que ^ (circunflexo) representa "ctrl".

### Exercícios

1. Crie outro arquivo com o Nano, escreva um texto e salve o arquivo.

2. Abra os dois arquivos simultaneamente com o Nano e navegue entre eles.

3. Escolha um dos arquivos, copie uma linha de texto e cole no outro arquivo.

4. Escolha uma linha de texto de sua preferência e a remova.

5. Cole a linha anteriormente removida no outro arquivo.

6. Verifique qual a posição atual do cursor no texto.

7. Mova o cursor para o início do texto e vá para uma linha e coluna expecíficas. Depois role até o fim do arquivo.

8. Busque por uma palavra repetidas vezes em ambos os arquivos e verifique os resultados.