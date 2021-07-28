Запуск БД:
helm install pg bitnami/postgresql -f values.yaml

Запуск приложения:
kubectl apply -f secret.yaml -f config.yaml -f deployment.yaml -f service.yaml -f ingress.yaml

Инициализация БД происходит внутри образа

В файле hw2.postman_collection.json тесты для постман
