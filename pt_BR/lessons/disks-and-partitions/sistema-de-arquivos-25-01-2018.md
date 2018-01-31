# Discos e Partições

## Sistema de Arquivos

Um sistema de arquivos é um conjunto de estruturas lógicas e de rotinas, que permitem ao sistema operacional controlar o acesso ao disco rígido.
O sistema de arquivos é criado durante a "formatação" da partição de disco.
Após a formatação, toda a estrutura para leitura/gravação/permissões de arquivos e diretórios pelo sistema operacional estará pronta para ser usada.
Normalmente este passo é feito durante a instalação de sua distribuição GNU/Linux.
Cada sistema de arquivos tem uma característica em particular, mas seu propósito é o mesmo: Oferecer ao sistema operacional a estrutura necessária para ler/gravar os arquivos/diretórios.
Abaixo segue alguns exemplos de sistemas de arquivos existentes:
Ext2: Usado em partições Linux Nativas para o armazenamento de arquivos.
Ext3: Este sistema de arquivos possui melhorias em relação ao ext2, como destaque o recurso de journaling e suporte a arquivos de até 16Gb. Ele também é totalmente compatível com o ext2 em estrutura.
O journal mantém um log de todas as operações no sistema de arquivos, caso aconteça uma queda de energia elétrica (ou qualquer outra anormalidade que interrompa o funcionamento do sistema), o comando "fsck" verifica o sistema de arquivos no ponto em que estava quando houve a interrupção, evitando a demora para checar todo um sistema de arquivos (que pode levar minutos em sistemas de arquivos muito grandes).
FAT32: Usado no DOS e oferece suporte a discos de até 2 Terabytes. Não possui suporte a permissões e journaling.
NTFS: Formato nativo de discos de sistemas operacionais Windows XP e superiores. Possui suporte a permissões de acesso e compactação nativa.

### Exercícios

1. O que é um sistema de arquivos?

2. Qual o objetivo do sistema de arquivos?

3. Quando o sistema de arquivos é criado?

4. Cite outros exemplos de sistemas de arquivos.