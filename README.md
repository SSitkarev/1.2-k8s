# Домашнее задание к занятию «Базовые объекты K8S» - Сергей Ситкарёв

## Задание 1. Создать Pod с именем hello-world

Создать манифест (yaml-конфигурацию) Pod.

Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.

[hello-world](https://github.com/SSitkarev/1.2-k8s/blob/main/pods/hello-world.yaml)

![Задание1](https://github.com/SSitkarev/1.2-k8s/blob/main/img/1.jpg)

Подключиться локально к Pod с помощью kubectl port-forward 

![Задание1](https://github.com/SSitkarev/1.2-k8s/blob/main/img/2.jpg)

и вывести значение (curl или в браузере).

![Задание1](https://github.com/SSitkarev/1.2-k8s/blob/main/img/3.jpg)

## Задание 2. Создать Service и подключить его к Pod

Создать Pod с именем netology-web.

Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.

Создать Service с именем netology-svc и подключить к netology-web.

[netology-web](https://github.com/SSitkarev/1.2-k8s/blob/main/pods/netology-web.yaml)

Подключиться локально к Service с помощью kubectl port-forward

![Задание2](https://github.com/SSitkarev/1.2-k8s/blob/main/img/4.jpg)

 и вывести значение (curl или в браузере).
 
![Задание2](https://github.com/SSitkarev/1.2-k8s/blob/main/img/5.jpg)