Открыть терминал или консоль и перейти в нужную Вам директорию

Прописать команду git clone git@github.com:AndreySerebryakov/diplom.git

Если Вы используете https, то: git clone https://github.com/AndreySerebryakov/diplom.git

Перейти в директорию diplom/shop/shop Прописать команду docker-compose up --build

Для остановки контейнера используйте docker stop $(docker ps -a -q)
для удаления docker rm $(docker ps -a -q)

Админка:

User = admin
Password = 1234

Для начало надо зайти в админку и добавть категорию и её slug. Затем добавить товар. Дальше уже с этим товаром можно работать.
