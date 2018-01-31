# Cliente Mutt

## Primeiros Passos

Hoje o e-mail executa um papel absolutamente essencial no processo da comunicação.
A praticidade e rapidez com que se pode enviar mensagens pela internet a vários destinatários elegeu esta ferramenta como um dos principais recursos de comunicação utilizados na atualidade.
O Mutt é um excelente cliente de e-mail para terminal.
Depois de instalado, basta digitar "mutt" no terminal para executá-lo.
Ele pode parecer meio sem graça no começo, mas não se preocupe. A configuração inicial não é muito amigável, mas é possível resolver de forma simples.
O arquivo
*~/.muttrc*
deve ser criado e configurado para ficar do jeito que você quer.
Abaixo seguem algumas configurações básicas:
Observação: Para colocar comentários no arquivo de configuração, basta iniciar a linha com um "#". Isso é importante antes de cada configuração, para não esquecer o que ela significa.

# Configuração do SMTP
set smtp_url = "smtp://email@smtp.dominio.com:587/"
#set smtp_pass = "senha"
set from = "email@dominio.com"
set realname = "Seu Nome"

# Configurações Imap
# Ativação da segurança TLS
set ssl_starttls=yes
# Sempre usar TLS
set ssl_force_tls=yes

Basta salvar o arquivo e executar o Mutt.
Alguns comandos básicos ao abrir o Mutt:
q: Sai do Mutt.
d: Apaga a mensagem.
u: Desfaz a ação do delete.
r: Responde um e-mail.
g: Responde para todos os endereços que constam na mensagem.
@: Mostra o e-mail do autor.
v: Mostra os arquivos anexos.
m: Cria uma nova mensagem.
?: Ajuda do programa.

Para enviar um e-mail, faça o seguinte:
*echo 'Conteúdo do e-mail' | mutt -s 'Assunto do e-mail' email-do-destinatario@dominio.com*
Para enviar um anexo, faça o seguinte:
*echo 'Conteúdo do e-mail' | mutt -s 'Assunto do e-mail' -a anexo1.txt anexo2.txt -- email-do-destinatario@dominio.com*

### Exercícios

1. Configure o Mutt.

2. Execute o programa e teste suas opções.

3. Envie um e-mail de teste.

4. Envie um e-mail de teste com anexo.