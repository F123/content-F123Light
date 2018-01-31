# Trabalhando Com Diretórios E Arquivos

## Trocando de Diretório

Agora que já foi mostrado o conteúdo de diretórios, é hora de saber como navegar de um diretório para o outro.

O comando usado para trocar de diretório é o:
*cd*

Existem vários parâmetros para combinarmos ao comando e trocar de diretórios. Eles serão listados a seguir:

/
Este parâmetro navega até o diretório
/
mais conhecido por Diretório Raiz ou "Root". Todos os demais diretórios são criados dentro do diretório raiz.
Exemplo:
*cd /*
Se listar o conteúdo do diretório, perceberá que foi alterado.

~
Este parâmetro aponta diretamente para o diretório "Home" do usuário (ou pasta do usuário).
Exemplo:
*cd ~*

-
Este parâmetro navega até o último diretório em que esteve.
Considerando que os comandos anteriores foram executados, se esteve no diretório raiz e em seguida foi para o diretório de usuário, usando o comando a seguir, voltará
para o diretório raiz, que é o último visitado antes do diretório atual.
Exemplo:
*cd -*

Para navegar até um diretório dentro do atual, basta digitar cd seguido do nome do diretório. No exemplo a seguir, utilizarei o diretório Documentos dentro da minha pasta 
"Home".
Exemplo:
*cd Documentos*
Alternativamente, é possível digitar o caminho completo do diretório.
Exemplo:
*cd /home/roberta/Documentos*

..
Este parâmetro volta ao diretório anterior na hierarquia. Considerando que estejamos no diretório Documentos, de acordo com o exemplo anterior, usando esse parâmetro é
possível voltar para o diretório "home".
Exemplo:
*cd ..*

Observação: Quando trocar de diretório, utilize o comando:
*ls*
para verificar o conteúdo do diretório e certificar-se de que navegou ao diretório correto.

### Exercícios

1. Navegue ao diretório raiz.

2. Liste o conteúdo do diretório e entre em algum de sua escolha.

3. Volte ao diretório anterior.

4. Navegue até o diretório home.

5. Navegue ao último diretório visitado.

6. Navegue a outro diretório utilizando o caminho completo do mesmo.