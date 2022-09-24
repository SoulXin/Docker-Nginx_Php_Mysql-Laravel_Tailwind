step:
1. docker-compose build
2. docker-compose up -d
3. cd src
4. npm install
5. docker exec -it php bash
6. composer install
7. cp .env.example .env
8. php artisan key:generate

version:
1. nginx 1.20.2
2. mysql 5.7.22
3. tailwind 3
4. Laravel Framework 8.83.5

localhost:8088

1. Run docker => docker-composer up -d
2. Stop docker => docker-composer down
