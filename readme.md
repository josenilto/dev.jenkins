##  DEV | Jenkins em docker compose

Automação gratuito e de código aberto. Ajuda a automatizar as partes do desenvolvimento de software relacionadas à construção, teste e implantação, facilitando a integração e entrega contínuas.

Este comando é um comando shell que baixa e executa um script para instalar o Docker em seu sistema.
Aqui está um detalhamento do que cada componente do comando faz:

curl: esta é uma ferramenta de linha de comando usada para transferir dados de ou para um servidor usando uma sintaxe de URL. Neste caso, ele é usado para baixar o script que irá instalar o Docker.
-fsSl: São opções que modificam o comportamento do curlcomando:
-f: esta opção informa curlpara falhar silenciosamente e sair com um código de status diferente de zero se ocorrer um erro durante a transferência de dados.
-s: Esta opção diz curlpara trabalhar silenciosamente, ou seja, não mostrará progresso ou mensagens de erro.
-S: Esta opção diz curlpara mostrar uma mensagem de erro se não conseguir baixar os dados.
https://get.docker.com: Este é o URL do script que instalará o Docker.
|: Este é um símbolo de pipe que diz ao shell para pegar a saída do curlcomando e usá-la como entrada para o próximo comando.
sh: Este é o comando shell que executará o script baixado para instalar o Docker. O script detectará o sistema operacional e instalará a versão apropriada do Docker para esse sistema.

```bash
curl -fsSl https://get.docker.com |sh
```

Name                Command               State                                           Ports
-----------------------------------------------------------------------------------------------------------------------------------------
Jenkins   /usr/bin/tini -- /usr/loca ...   Up      0.0.0.0:50000->50000/tcp,:::50000->50000/tcp, 0.0.0.0:8080->8080/tcp,:::8080->8080/tcp



```bash
docker-compose ps
```

docker-compose -f docker-compose.yaml up -d

docker-compose -f docker-compose.yaml down

docker network list