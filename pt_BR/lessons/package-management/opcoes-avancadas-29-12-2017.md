# Gerenciamento de Pacotes

## Opções Avançadas

O "pacman" tem opções interessantes para gerenciar pacotes.
Abaixo serão listados mais alguns comandos úteis:
Instalar pacotes sem precisar de confirmação:
*sudo pacman -S pacote noconfirm*
Instalar pacotes sem dependências:
*sudo pacman -Sdd*
Listar pacotes desnecessários (sem dependências):
*sudo pacman -Qdt*
Apagar pacotes desnecessários (sem dependências):
*sudo pacman -Rns $(pacman -Qqdt)*
Apagar pacotes e deixar suas dependências no computador:
*sudo pacman -Rdd*

### Exercícios

1. Instale pacotes ignorando as dependências.

2. Instale pacotes sem precisar de confirmação.

3. Liste pacotes que não possuem dependências e os remova.

4. Remova pacotes deixando as dependências no computador.