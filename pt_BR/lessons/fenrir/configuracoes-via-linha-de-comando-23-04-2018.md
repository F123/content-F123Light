# Configurações do Fenrir via Linha de Comando

O Fenrir permite que você altere configurações sem acessar diretamente o arquivo de configurações, bastando digitar a alteração no terminal.
A sintaxe da configuração é a seguinte:
*fenrir -o "sessão#configuração=valor"*
No exemplo a seguir, o driver de som será alterado:
*fenrir -o "sound#driver=gstreamerDriver*
Observação: É possível escrever vários comandos seguidos, basta colocar um ponto e vírgula ";" ao fim de cada comando. No exemplo a seguir, o driver de som será alterado e o braille desabilitado:
*fenrir -o "sound#driver=gstreamerDriver;braille#enabled=False"*

### Exercícios

1. Altere uma configuração única do Fenrir.

2. Altere três configurações na mesma linha.