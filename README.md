# Как запустить сервер:

Команды:
- Создать docker image: `docker build -t server .`
- Запустить контейнер с помощью созданного image: `docker run -p 8000:8080 -d --name server-app flowers` (8000 - порт локально у тебя на компьтере; 8080 - порт в докере (виртуалке)). Порты можно поменять в Dockerfile
- Подключиться к контейнеру (по сути зайти в виртуалку): `docker exec -it server-app bash`\
Тут будет запущен linux на котором можно выполнять все команды