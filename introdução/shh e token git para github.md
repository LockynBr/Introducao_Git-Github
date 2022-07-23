# Gerar  SHH Key e Token Git para Github:key:

### Windows / Linux

ssh-keygen

cd /c/User/name/.ssh/ -> Com a pasta .ssh criada no Disco C.

cat chave.pub

Colar no github a chave que foi imprimida apos o comando.

###  Inicializar o ssh keygen

eval $(ssh-agent -s)

ssh-add chave -> Precisa ser a chave privada.

###  Clonar uma Pagina

git clone (linkssh) 

ou

git clone (linkhttps)
