Создаем нового пользователя Post costumer -> проверка на мошенника в сервисе fraud -> отправка нотификации после проверки в сервисе notification(по 1 записе в каждой базе)
1. mvn clean package -P build-docker-image
2. docker compose pull
3. docker compose up -d
4. Server - amigoscode
5. Databases - fraud, costumer, notification
![Снимок экрана (15)](https://user-images.githubusercontent.com/87278338/178244260-e666d70d-eee2-420f-8c7c-297e740a1a48.png)
