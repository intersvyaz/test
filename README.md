#Тестовое задание

* Развернуть и запустить блог как описано [тут](http://www.yiiframework.com/doc/blog/). Рекомендуется развернуть его по шагам туториала, для того чтобы понимать что и зачем делается. В качестве базы данных использовать sqlite. 
* Переделать подключение фреймворка Yii в блоге на [composer](https://getcomposer.org/). Подключить autoloader, который генерирует composer. 
* Переделать структуру приложения, так чтобы файлы, которые может иметь доступ пользователь лежали в поддиректории приложения public.
В конечном счёте приложение должно принять следующий вид:
```
/
 - protected/ - директория с закрытыми файлами приложения
 - public/ - директория с открытыми файлами приложения
 - vendor/ - директория подключаемых библиотек
 - composer.json
 - composer.lock
```
* Разместить код приложения в публичном доступе на хостинге кода [github](https://github.com/). Необходимо использовать git с первых шагов тестового задания и коммитить каждый шаг, будет легче откатываться к предыдущему состоянию и разбираться с тем, что пошло не так.
* Форматирование кода должно соответствовать PSR-2
