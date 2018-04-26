# Gerenciamento de Pacotes

## Instalando e Removendo Pacotes

No Linux, os programas são disponibilizados em forma de pacotes.
Existem repositórios (o local onde os pacotes ficam armazenados) oficiais e dos próprios usuários.

## Instalando um Pacote

Para instalar um pacote ou programa, execute o seguinte comando no terminal:
*sudo pacman -S pacote*
Será solicitada a sua senha de administrador. Basta digitá-la e pressionar "enter".

## Removendo um Pacote

Para remover um pacote, execute o seguinte comando:
*sudo pacman -R pacote*

## Opções:

Abaixo serão listadas algumas opções extras do comando "pacman":
Procurar pacote:
*sudo pacman -Ss pacote*
Listar todos os pacotes instalados:
*sudo pacman -Q*
Desinstalar pacotes, dependências e todos os registros:
*sudo pacman -Rscn*
Procurar atualização:
*sudo pacman -Su*

### Exercícios

1. Pesquise um pacote.

2. Instale um pacote no computador.

3. Procure atualizações dos pacotes.

4. Liste todos os pacotes instalados no computador.

5. Remova um pacote.

6. Remova um pacote com todas as dependências e registros.