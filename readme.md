## dev.jenkins

Automação gratuito e de código aberto. Ajuda a automatizar as partes do desenvolvimento de software relacionadas à construção, teste e implantação, facilitando a integração e entrega contínuas.



docker-compose ps

Name                Command               State                                           Ports
-----------------------------------------------------------------------------------------------------------------------------------------
Jenkins   /usr/bin/tini -- /usr/loca ...   Up      0.0.0.0:50000->50000/tcp,:::50000->50000/tcp, 0.0.0.0:8080->8080/tcp,:::8080->8080/tcp


docker-compose -f docker-compose.yaml up -d

docker-compose -f docker-compose.yaml down

docker network list