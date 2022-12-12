# How to run rabbitmq images

```shell
    $ docker run --name rabbitmq3 -p "5672:5672" -p "15672:15672" -e RABBITMQ_DEFAULT_USER=admin -e RABBITMQ_DEFAULT_PASS=123123 rabbitmq:3.9.26-management-alpine
```