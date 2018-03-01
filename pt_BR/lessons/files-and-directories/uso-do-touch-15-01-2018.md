# Trabalhando Com Diretórios E Arquivos

##Uso do Touch

O comando "touch é usado para alterar a data e hora de acesso e de modificação de arquivos.
É possível alterar as duas simultaneamente ou apenas uma delas.
Antes de prosseguir, veja a legenda abaixo:
A: Representa os dígitos do ano.
M: Representa os dígitos do mês.
D: Representa os dígitos do dia.
H: Representa os dígitos da hora.
M: Representa os dígitos do minuto.
S: Representa os dígitos do segundo.

## Alterando a Data e hora de Acesso

Para alterar a data e hora de acesso de um arquivo, digite o seguinte comando:
*touch -t AAAAMMDDhhmm.ss -a arquivo*
O parâmetro "-a" indica acesso.

## Alterando a Data e Hora de Modificação

Para alterar a data e hora de modificação de um arquivo, digite o seguinte comando:
*touch -t AAAAMMDDhhmm.ss -m arquivo*
O parâmetro "-m" indica modificação.

## Alterando a data e hora de acesso e modificação

Para alterar data e hora de acesso e modificação de um arquivo simultaneamente, digite o seguinte comando:
*touch -t AAAAMMDDhhmm.ss arquivo*
Observação: Se o arquivo não existir, ele será criado com a data e hora definidas no comando.

### Exercícios

1. Altere a data e hora de acesso de um arquivo para 25/03/2009 06:25:44.

2. Altere a data e hora de modificação de um arquivo para o dia anterior ao meio-dia.

3. Altere a data e hora de acesso e modificação de um arquivo.