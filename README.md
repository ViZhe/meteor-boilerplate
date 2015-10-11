# Meteor Boilerplate

## Структура приложения (TODO)

    app/                     - Корень проекта
    ├── both                 - Общие файлы
    │   ├── collections      - работа с коллекциями
    │   └── ****             -
    ├── client               - Клиентские файлы
    │   ├── compatibility    -
    │   ├── routes           - роутинг
    │   ├── styles           - стили
    │   └── templates        -
    │       ├── application  - базовые шаблоны
    │       └── home         - шаблон главной страницы
    ├── private              -
    ├── public               - Статика (картинки, robots.txt)
    ├── server               - Серверные файлы
    │   ├── methods          -
    │   ├── publications     - публикация данных из коллекций
    │   ├── routes           - роутинг
    │   └── startup          -
    └── tests                - Тесты (никуда не загружаются)

## Удаленные пакеты

* `autopublish`
* `insecure`


## Установленные пакеты

* `coffeescript` - Добавляет поддержку CoffeeScript
* `mquandalle:jade` - Добавляет поддержку Jade
* `iron:router` - Добавляет роутинг
* `spiderable` - Генерим страницу для ботов. Нуждается в `sudo apt-get install phantomjs`



## Пакеры на будущее
* [manuelschoebel:ms-seo](https://atmospherejs.com/manuelschoebel/ms-seo) - Формирование метатегов для СЕО
