#Кнопка чата ВКонтакте на сайте

Кнопка для перехода с сайта в сообщения сообщества.

###Примеры
- https://botpult.com/vk-chat-button/demo-line-xs.html 
- https://botpult.com/vk-chat-button/demo-line.html 
- https://botpult.com/vk-chat-button/demo.html 
- https://botpult.com/vk-chat-button/demo-circle.html

###Подключение

- Скачайте файл `botpult-button.min.css`
- Вставьте код перед закрывающимся тегом ```<body>``` и замените ```ID_Сообщества``` на id вашего сообщества ВКонтакте
```html
<!-- Botpult button -->
<link href='https://fonts.googleapis.com/css?family=Open+Sans' rel='stylesheet' type='text/css'>
<link rel="stylesheet" type="text/css" href="botpult-button.min.css">
<div class="BotpultButton right-bottom" onclick="window.open('https://vk.com/im?sel=-' + ID_Сообщества, '_blank').focus()">
    <span class="text">Напишите нам!</span>
</div>
<!--End of botpult button -->
```

####Вешний вид
Можете выбрать 1 из 4 видов кнопки, просто заменив css класс `BotpultButton` на другой
```html
<div class="BotpultButton right-bottom" ...>
```

css класс | вид
--------- | ---
```BotpultButton``` | ![Basic](https://raw.githubusercontent.com/botpult/vk-chat-button/master/img/basic.jpg)
```BotpultButton--circle``` | ![Circle](https://raw.githubusercontent.com/botpult/vk-chat-button/master/img/circle.jpg)
```BotpultButton--line``` | ![Line](https://raw.githubusercontent.com/botpult/vk-chat-button/master/img/line.jpg)
```BotpultButton--line-xs``` | ![LineXS](https://raw.githubusercontent.com/botpult/vk-chat-button/master/img/line-xs.jpg)

####Положение на старинце

Доступны 4 разных варианта расположения на странице, просто добавьте css класс к div элементу
```html
<div class="BotpultButton right-bottom" ...>
```

- `right-bottom` справа снизу
- `left-bottom` слева снизу
- `left-top` слева сверху
- `right-top` справа сверху
