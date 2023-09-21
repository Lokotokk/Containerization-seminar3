# Задание:
## 1 - устанавливаем Докер:  
Установленный докер:  
![](https://github.com/Lokotokk/Containerization-seminar3/blob/main/images/1_dockerVersion.png)  

## 2 -тестируем:  
![](https://github.com/Lokotokk/Containerization-seminar3/blob/main/images/2_cowsay.png)  

## 4- Хранение данных в контейнерах Docker.
### Часть-1:  
Запускаем контейнер из образа убунты и входим в него, смотрит информацию о файлах в широком формате, создаем новую директорию в корне,
создаем файлы добавляем в него данные:  
![](https://github.com/Lokotokk/Containerization-seminar3/blob/main/images/3_mkdir_container.png)  

Останавливаем контейнер и затем запускаем его снова. Проверяем сохранность данных и видим, что они сохранились:  
![](https://github.com/Lokotokk/Containerization-seminar3/blob/main/images/4_st_stop_container.png)  

Удаляем контейнер и создаем его заново. Видим, что данных нет:  
![](https://github.com/Lokotokk/Containerization-seminar3/blob/main/images/5_rm_container.png)  

Создаем директорию и подмонтируем ее к контейнеру, добавляем данные в подмонтированную директорию, смотрим содержимое из контейнера, проверяем достпуность из локальной системы:  
![](https://github.com/Lokotokk/Containerization-seminar3/blob/main/images/6.png)  

Удаляем контейнер и создаем его снова, подмонтировав директорию, видим, что данные доступны:  
![](https://github.com/Lokotokk/Containerization-seminar3/blob/main/images/7.png)  








