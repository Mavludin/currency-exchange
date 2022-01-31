# О проекте

Проект написан на React JS на шаблоне Create React App

## Запуск проекта

Выполнить следующие команды в терминале: сперва **npm install**, затем **npm start**

## Как все работает

После запуска проекта откроется страница с единственной кнопкой по середение;  
Нажав на кнопку открывается окно с виджетом конвертера валют;  
Обмен производится только по следующимвалютам: RUB, USD, и EUR;  
Вводить валюту можно только в левое окно, правое - только для результата;  
Вводить можно только цифры;  
Ограничений по большим числам нет, могу добавить при необходимости;  
При нажатии на кнопку между окнами, валюты меняются местами;  
При открытии виджета, курсы валют берутся с API -  https://v6.exchangerate-api.com;  
Каждые 15 секунд данные обновляются. Это можно заметить, если обратить внимание на коэффициент обмена слева снизу - он будет мигать.  
  
**Используемые технологии:** React JS, Axios, React Query, Ant Design, SASS (SCSS);  
Какой-то стейт менеджер не стал использовать, могу использовать при необходимости.  
  
Остается одна проблема касательно хранения API ключа для запроса. Добавить его в **.env** не получится, т.к. этот файл идет в билд. Если добавить в **.gitignore**, то при пуше, его не будет в репозитории и вы не сможете так протестировать проект. В итоге оставлю данный ключ просто в коде, т.к. пока это все для теста.

## Внешний вид

### Основная панель
![Основная панель](https://i.imgur.com/gIJhpIW.jpg)
