# Как запустить сервер:

Команды:
- Создать docker image: `docker build -t server .`
- Запустить контейнер с помощью созданного image: `docker run -p 8000:3000 -d --name server-app flowers` (8000 - порт локально у тебя на компьтере; 3000 - порт в докере (виртуалке))
- Подключиться к контейнеру (по сути зайти в виртуалку): `docker exec -it server-app bash`\
Тут будет запущен linux на котором можно выполнять все команды