# Screen

## Uso do Screen

O Screen é um multiplexador de terminais que permite ao usuário, em uma mesma sessão, abrir várias janelas e realizar atividades paralelas.
Se você precisa realizar outra tarefa enquanto faz um download, por exemplo, o screen é muito útil, já que é possível abrir outra tela de terminal enquanto seu download é feito em segundo plano.

## Utilização

Para utilizar o screen, basta digitar:
*screen*
Nada vai aparecer, mas o screen estará aberto nesse momento.
Agora, você pode executar a tarefa que quer deixar em segundo plano enquanto faz outras.
Depois disso, pressione a combinação:
*Ctrl+A D*
Essa combinação de teclas fará com que essa sessão virtual seja separada (detached) da sessão original, liberando por consequência o terminal para realização de outra tarefa.
Para listar as sessões abertas, digite:
*screen -ls*
Se você estiver em outra sessão e quiser restaurar a anterior, para verificar o estado de download, por exemplo, digite:
*screen -r*
Observação: Quando o comando tem uma letra separada, como o comando visto acima (Ctrl+A D, por exemplo), significa que Ctrl+A devem ser pressionadas ao mesmo tempo, e o D deve ser pressionado só após soltar as teclas anteriores.

## Múltiplas Telas

Para criar e navegar por mútiplas telas dentro do screen, veja os comandos a seguir:
Ctrl+A c: Criar nova janela.
Ctrl+A p: Ir para a tela anterior.
Ctrl+A n: Ir para a tela seguinte.
Para fechar o screen, execute:
*exit*

### Exercícios

1. Abra o terminal, execute o screen e inicie o download de um arquivo grande.

2. Crie mais telas e execute outras tarefas.

3. Navegue entre as telas, indo para as telas seguintes e voltando.

4. Restaure a tela do download para verificar seu andamento.