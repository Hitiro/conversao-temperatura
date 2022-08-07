Build da imagem Docker
    * docker build -t htirotsugawa/conversao-temperatura -f Dockerfile ./
 docker build -t name:conversao-temperatura -f Dockerfile ./

Remover um container forçado
docker container rm -f 4065c7adef44
* Se não quiser forçar, remover o "-f"

Fazer login no Docker
docker login

Enviar para o Docker
docker push hitirotsugawa/conversao-temperatura:v1

Alterar a tag
docker tag hitirotsugawa/conversao-temperatura:v1 hitirotsugawa/conversao-temperatura:latest


https://outstanding-bagel-fe2.notion.site/Docker-Iniciativa-DevOps-0c658550ef0a45598fef694365daefbf