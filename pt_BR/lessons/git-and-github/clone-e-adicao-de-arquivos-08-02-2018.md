# Git

## Clone e Adição de Arquivos

Com o Git configurado e uma conta criada no GitHub, é hora de começar a trabalhar em um projeto.
Para isso, é necessário clonar o repositório criado previamente no GitHub em seu computador.

Abra o terminal e navegue até uma pasta que queira utilizar para essa finalidade.
Execute o seguinte comando:
*git clone https://github.com/usuario/repositorio.git*
Onde:
usuario: É o nome do seu usuário no GitHub.
repositorio: É o nome que você digitou na criação do repositório.

Uma pasta com o nome do seu repositório será criada.
Navegue até ela para começar a interagir com o repositório.
Como exemplo, crie um arquivo de texto nessa pasta e digite algo. Salve e feche o arquivo.
Agora, execute o seguinte comando:
*git status*
Esse comando mostra o status do seu trabalho, como por exemplo os arquivos, modificações e se estão prontos para serem publicados.
Nesse caso, o seu arquivo de texto não está pronto para ser enviado ao GitHub. Para isso ainda falta um comando:
*git add .*
Ao contrário do que parece, esse comando não está adicionando um arquivo novo no repositório, e sim preparando os arquivos para serem enviados ao GitHub.
Você também pode definir apenas arquivos específicos digitando seus nomes, se não quiser enviar todos eles.

### Exercícios

1. Abra o terminal, navegue até uma pasta nova de trabalho e clone seu repositório criado anteriormente no GitHub.

2. Vá até a pasta criada e crie arquivos nela.

3. Adicione os arquivos, preparando-os para serem enviados para o GitHub.