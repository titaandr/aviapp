# aviapp

Реализовано кеширование (memcached)

Запустить команду: 
docker-compose -f django_app.yaml up

http://127.0.0.1:8000/api/v1/posts/create/ - создать обьявление
http://127.0.0.1:8000/api/v1/posts/all/?ordering=price - отсортировать по возрастанию 
http://127.0.0.1:8000/api/v1/posts/all/?ordering=-price - отсортировать по убыванию
http://127.0.0.1:8000/api/v1/posts/itemid/2/ = поулучить по id 
http://127.0.0.1:8000/api/v1/posts/field/?search=name - поиск по имени 
http://127.0.0.1:8000/api/v1/posts/field/?search=2 - поиск по цене 
