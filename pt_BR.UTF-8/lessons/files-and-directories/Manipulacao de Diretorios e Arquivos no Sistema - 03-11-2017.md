# Trabalhando Com Diretórios E Arquivos

## Copiando, Movendo, Renomeando e Removendo

Para copiar um arquivo, usamos o comando:
*cp*
Vamos copiar o arquivo teste para o diretório Documentos:
*cp teste Documentos*
Verifique com o comando "ls" e veja o resultado:
*ls Documentos*
Também é possível copiar o conteúdo de um arquivo para outro, utilizando o comando da mesma maneira.
*cp teste teste2*
O conteúdo de teste foi copiado para teste2. Para verificar, basta ler o conteúdo de ambos com o comando "cat".

Para copiar um diretório para outro, basta usar o parâmetro "-r". Criaremos o diretório Documentos2 e copiaremos Documentos para dentro dele.
Exemplo:
*mkdir Documentos2*
*cp -r Documentos Documentos2*
O diretório Documentos foi copiado para Documentos2. Liste o conteúdo e verifique o resultado.

Para mover um arquivo, utilizamos o comando "mv".
Exemplo:
*mv teste Documentos*
O arquivo foi movido para o diretório Documentos. Verifique com o comando "ls".
Para renomear um arquivo ou diretório, basta digitar primeiro o nome original e depois o novo nome.
Exemplo:
*mv teste teste2*
O arquivo teste agora chama-se teste2.
Para mover um diretório, basta fazer exatamente como foi feito com arquivos. O comando "mv" já é recursivo, o que dispensa o parâmetro "-r".

Para remover um arquivo, usamos o comando "rm".
Exemplo:
*rm teste*
O arquivo teste foi removido.
Para remover um diretório vazio, usamos o comando "mrdir".
Exemplo:
*rmdir Documentos*
Como temos arquivos nesse diretório, ele não foi removido. Portanto, para diretórios contendo conteúdo, usamos o comando "rm -r".
Exemplo:
*rm -r Documentos*
Agora o diretório foi removido com todo o seu conteúdo.
Não se esqueça de conferir o resultado de cada alteração com os comandos "ls" e "cat".

### Exercícios

1. Crie um arquivo, escreva um conteúdo e copie para outro diretório.

2. Copie o conteúdo desse arquivo para outro arquivo.

3. Copie um diretório para outro.

4. Mova seus arquivos para outro diretório.

5. Renomeie o arquivo de teste.

6. Mova um diretório para outro.

7. Apague o arquivo de teste.

8. Apague o diretório criado para teste.