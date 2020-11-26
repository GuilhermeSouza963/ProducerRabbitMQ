# ProducerRabbitMQ
Criação de um Producer do tipo FanOut para envio de logs em um console app .Net Core

Antes de rodar o projeto é nescessário ou instalar o RabbitMQ na sua máquina ou levantar a imagem dele pelo docker
seguindo este comando:

docker pull rabbitmq
docker run -d --hostname my-rabbit --name rabbitmq -p 80080:15672 -p 5672:5672 rabbitmq:3-management

Ele irá inicializar na porta padrão 15672 dentro do host já para acessar na sua maquina é só acessar pelo http://localhost:8080
