No terminal, no diretorio que está o arquivo docker-compose.yml, executar o seguinte comando:

- docker-compose up

Acessar o RabbitMQ pela aplicação web:

http://localhost:15672


Microserviço que publica mensagens na fila:

- order-service

Microserviços que consomem as mensagens da fila:

- cashback-service e notification-service


Observações importantes:

Parar o serviço mysql (windows), executar comando:
 
- net stop MySQL80  

https://stackoverflow.com/questions/10885038/stop-mysql-service-windows




Fonte (Algaworks):

https://www.youtube.com/watch?v=SzcvuHjRJKE

