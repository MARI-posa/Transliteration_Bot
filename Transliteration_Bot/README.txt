Получить персональный токен у BotFather в telegram
Вставить его в dockerfile
В терминале ввести команду: docker build . 
После ее выполения использовать команду: docker images
Взять IMAGE ID и вставить его в команду ниже на место ##IMAGE ID##
Запустить конамнду: docker run -d -p 80:80 ##IMAGE ID##

Бот работает! :D

Если необзодимо остановить docker:
Ввести команду docker ps
Копировать CONTAINER ID
Вставить его в команду ниже не место ##CONTAINER ID##
docker stop ##CONTAINER ID##