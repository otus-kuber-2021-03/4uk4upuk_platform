Домашнее задание №1
1. Настройка локального окружение(запуск minikube, скачивание kubectl, k9s, настройка автозаполнения, создание алиаса k=kubectl)
2. Создание Dockerfile, собран образ с nginx с портом 8000.
3. Создание манифеста и запуск в minikube, с последущим port-forward.
4. Запуск frontend и решение проблемы(необходимо добавить переменные окружения).

Разберитесь почему все pod в namespace kube-system восстановились после удаления:
core-dns: Deployments, в minikube replica=1
kube-apiserver: запускается демоном kubelet