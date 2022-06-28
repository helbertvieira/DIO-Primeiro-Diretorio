# Anotacoes GIT

#### Git hash: Cria um código com 40 caracteres criptografados para cada alteração de código.

##### openssl sha1 texto.txt

## Objetos internos no GIT

#### Blobs / Tree / Commits  -  Todos tem Sha1(codificação)

##### Blobs: contém metadados, tamanho do objeto, tamanho da string, tipo do arquivo

##### Tree: árvores - armazenam blobs, também guarda o nome

blob <-- Tree --> Tree --> blob

​                  |

​              blob

##### Commits: Junta tudo - Sha1 é o hash de toda a informação

Tree, parent, autor, mensagem, timestamp