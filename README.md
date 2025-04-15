Запускаем
`docker compose -f ./docker/docker-compose.yml build`
`docker compose -f ./docker/docker-compose.yml up`

Установка из контейнера
`docker compose -f ./docker/docker-compose.yml exec -u www-data php-fpm bash`
(https://symfony.com/doc/current/setup.html)
В контейнере запускаем:
`composer create-project symfony/skeleton:"7.2.x" my_project_directory`

Переносим все файлы из my_project_directory/ в корневую директорию.