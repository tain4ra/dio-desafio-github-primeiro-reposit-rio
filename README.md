# Desafio de projeto Git/Github DIO
Repositório criado para o desafio de projeto

## Objetos básicos do GIT
### BLOBS

Contém metadados do GIT

#### Estrutura básica:

Tipo de objeto

Tamanho da string

\0

Conteúdo do arquivo


### TREES

Armazena Blobs

#### Estrutura básica:

\0

Blob

sha1

Nome do arquivo

aponta para blobs ou trees

### COMMITS

Une tudo.

#### Estrutura básica:

tree

parente

autor

mensagem (dando sentido ao código)

timestamp

Sistema distribuído e seguro, quando você altera qualquer um desses itens, toda a estrutura se altera.

