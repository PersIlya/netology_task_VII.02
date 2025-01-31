
## <p style="text-align: center;">ОТЧЕТ</p> <p style="text-align: center;">по домашним заданиям к занятию «Базовые объекты K8S»</p>
## <p style="text-align: right;">Выполнил: студент Порсев И.С.</p>

### Цель задания

В тестовой среде для работы с Kubernetes, установленной в предыдущем ДЗ, необходимо развернуть Pod с приложением и подключиться к нему со своего локального компьютера. 

### Инструменты и дополнительные материалы, которые пригодятся для выполнения задания

1. Описание [Pod](https://kubernetes.io/docs/concepts/workloads/pods/) и примеры манифестов.
2. Описание [Service](https://kubernetes.io/docs/concepts/services-networking/service/).

------

### Задание 1. Создать Pod с именем hello-world

1. Создать манифест (yaml-конфигурацию) Pod.
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Подключиться локально к Pod с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

## Решение

![localImage](./screen_VII.02_1.png)    

## Ссылки на файлы:
>[Pod](./conf/pod.yaml);    
>[Service](./conf/service.yaml);   

![localImage](./Yes.png)


------

### Задание 2. Создать Service и подключить его к Pod

1. Создать Pod с именем netology-web.
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web.
4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

## Решение

![localImage](./screen_VII.02_2.png)    

## Ссылки на файлы:
>[Pod2](./conf/pod2.yaml);    
>[Service2](./conf/service2.yaml);   

![localImage](./Yes.png)
