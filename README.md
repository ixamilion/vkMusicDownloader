Скрипт python3 для скачивания Вашей и не Вашей музыки из вконтакта.

Как использовать:

```bash
pip3 install -r requirements.txt
./src/main.py
```
При 1-ом запуске скрипт попросит Вас авторизоваться:
```bash
Авторизоваться заново? yes/no
> yes
```
Далее попросит ввести логин под которым мы будем авторизироваться:
```bash
Введите логин
> my_login 
```
Далее введите пароль:
```bash
Введите пароль
> 
```
Далее необходимо ввести id пользователя/группы музыку которого мы хотим скачать:
```bash
Введите id профиля
> 
```
Узнать id по имени можно например [здесь](http://regvk.com/id/)

Если все было сделано успешно, то Вы увидите следующее:
```bash
Вы успешно авторизовались.
Подготовка к скачиванию...
Будет скачано: 113 аудиозаписей.
Скачивание началось...

1 Уже скачен: Ленинград - i_$uss.mp3.
2 Уже скачен: Chamdo - Tibetan Gorshay Dance.mp3.
...
113 аудиозаписей скачано за: 6.139557838439941 сек.

```