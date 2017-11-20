# letishop-blackfriday

В папке **vc.ru** находится версия, которая не подгружает шрифт *Roboto* и библиотеку *likely.js*.
Версия в папке **standalone** загружает все, что ей необходимо.

Код встраивания можно увидеть в файлах *blackfriday.html* и *blackfriday-nofont.html*. Вот этот код для встраивания на vc.ru:

    <div id="game_blackfriday"
         data-base="./"
         data-share-url="https://vc.ru/special/letyshops/"
         data-share-title="Черная пятница. Игра, в которой нужно все посчитать."
         data-share-twitter="Черная пятница. Игра, в которой нужно все посчитать."
    >Загрузка…</div>
    <link rel="stylesheet" type="text/css" href="all.min.css"></script>
    <script src="all.min.js"></script>

Параметры:
* *data-base*: URL, по которому размещен код игры.
* *data-share-url*: URL для шеринга в соцсетях.
* *data-share-title*: заголовок поста в соцсетях.
* *data-share-twitter*: заголовок для Twitter.
* *load-fonts*: если этот атрибут присутствует, игра загружает необходимые шрифты.

Все URL должны заканчиваться слешем.