# Go with RabbitMQ

## Run RabbitMQ

using image: rabbitmq:3-management

```
docker run -d --hostname my-rabbit --name test-my-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management

d526401c03e758a233394db0ca64205d3ee59a2df47cca4695c78ed4325103cf
```

http://localhost:15672 

id: guest
pwd: guest

로 접근해본다. 

## 