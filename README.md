# ivan-kamenskiy_microservices
ivan-kamenskiy microservices repository

Каков результат? Что выдал docker ps? Как думаете почему? 
Контейнеры не запустились т.к. используют одну и туже сеть и один и тот же порт.


Повторите запуски контейнеров с использованием драйверов
none и host и посмотрите, как меняется список namespace-ов. 
При использование драйвера none колличество неймспрейсов увеличивается
при host неймспейсы не изменяются

Добавлен reddit, gitlab-ci.yaml, docker-compose

docker hub login 12313210313210321032 
