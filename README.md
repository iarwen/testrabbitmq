##运行docker rabbit
docker run -d --hostname my-rabbit --name som0e-rabbit -p 8080:15672 -p 5672:5672 rabbitmq:3-management