# Gerenciamento de Pacotes

## Instalando e Removendo Pacotes

No Linux, os programas s�o disponibilizados em forma de pacotes.
Existem reposit�rios (o local onde os pacotes ficam armazenados) oficiais e dos pr�prios usu�rios.

## Instalando um Pacote

Para instalar um pacote ou programa, execute o seguinte comando no terminal:
*sudo pacman -S pacote*
Ser� solicitada a sua senha de administrador. Basta digit�-la e pressionar "enter".

## Removendo um Pacote

Para remover um pacote, execute o seguinte comando:
*sudo pacman -R pacote*

## Op��es:

Abaixo ser�o listadas algumas op��es extras do comando "pacman":
Procurar pacote:
*sudo pacman -Ss pacote*
Listar todos os pacotes instalados:
*sudo pacman -Q*
Desinstalar pacotes, depend�ncias e todos os registros:
*sudo pacman -Rscn*
Procurar atualiza��o:
*sudo pacman -Su*

### Exerc�cios

1. Pesquise um pacote.

2. Instale um pacote no computador.

3. Procure atualiza��es dos pacotes.

4. Liste todos os pacotes instalados no computador.

5. Remova um pacote.

6. Remova um pacote com todas as depend�ncias e registros.