# Для запуска (перезапусков) контейнеров:

0. docker-compose down
1. chmod +x init-letsencrypt.sh
2. ./init-letsencrypt.sh
3. docker-compose up -d

# Для добавление домена:

1. В папку conf добавить файл %domain%.conf (по аналогии с другими файлами)
2. В файле init-letsencrypt.sh добавить домен (строка №8)
3. Перезапусть контейнера

# P.S.: Содержимое в certbot создается автоматически

Источник: https://pentacent.medium.com/nginx-and-lets-encrypt-with-docker-in-less-than-5-minutes-b4b8a60d3a71
