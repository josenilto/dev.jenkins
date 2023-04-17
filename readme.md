## DEV | Jenkins em docker compose

Automação gratuito e de código aberto. Ajuda a automatizar as partes do desenvolvimento de software relacionadas à construção, teste e implantação, facilitando a integração e entrega contínuas.

Este comando é um comando shell que baixa e executa um script para instalar o Docker em seu sistema.   
O script detectará o sistema operacional e instalará a versão apropriada do Docker para esse sistema.

```bash
curl -fsSl https://get.docker.com |sh
```

```bash
sudo apt  install docker-compose
```

```bash
docker compose version
```

```bash
docker ps -a
```

```bash

```

Lista contêineres para um projeto do Compose, com status atual e portas expostas.
```bash
docker-compose ps
```

Por padrão, apenas os contêineres em execução são mostrados. --all sinalizador pode ser usado para incluir contêineres parados.
```bash
docker compose ps --all
```

```bash
docker-compose -f docker-compose.yaml up -d
```

```bash
docker-compose -f docker-compose.yaml down
```

```bash
docker network list
```

```bash
docker container list
```