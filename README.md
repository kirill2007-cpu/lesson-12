<p align="center">
  <img src="logos/eh-logo.svg" alt="Exception Hunters logo"/>
</p>
<br />

# Что будем делать (22 июля 2020)
1) Продолжим верстать "Super Host"
2) Извлечем все картинки из макета
3) Установим все шрифты (воспользуемся сервисом google fonts)
4) Изучим что такое javascript объекты 
5) Начнем изучать популярную библиотеку для создания слайдеров "Slick Slider"
6) JQuery (javascript библиотека)
7) BEM (Block Element Modificator)

# Что не успели пройти в прошлом уроке
1) rgb, rgba (альфа канал, 16-тиричная система)
2) Pixel Perfect 

# Что сделали сегодня
1) Продолжили верстать "Super Host" (сделали 'header', начали секцию 'intro')
2) Извлекли часть картинок из макета
3) Познакомились с BEM (методика наименования классов)
4) Очень поверхностно коснулись JQuery (javascript библиотека)

# Ключевые моменты урока
1) Некоторые вещи при верстке сайта делаются шаблонно (одинаково). Например верхняя панель навигации очень часть делается так:
```html
<nav class="header__nav">
  <ul class="header__list">
    <li class="header__item">
      <a href="#">HOME</a>
    </li>
    <li class="header__item">
      <a href="#">ABOUT US Us</a>
    </li>
    <li class="header__item">
      <a href="#">WHMCS-BRIDGE</a>
    </li>
    <li class="header__item">
      <a href="#">HOSTING</a>
    </li>
    <li class="header__item">
     <a href="#">HOSTING</a>
    </li>
    <li class="header__item">
      <a href="#">BLOG</a>
     </li>
     <li class="header__item">
       <a href="#">CONTACT US</a>
    </li>
  </ul>
</nav>
```
2) Для того, что-бы прописать стили для веб элементов есть 4 способа как это сделать:
  * Через класс(к примеру .intro{display: flex})
  * Через id (к примеру #one{color: red})
  * Через имя тега(к примеру div{display: flex})
  * Прописать в теге атрибут style="color: red" и в кавычках писать стили

3) Когда мы прописываем стиль 'width' в классе для какого-либо элемента то нужно помнить как отмеряется ширина и высота элемента.
Для того что бы ширина и высота отмерялась от краев марджинов (что рекомендуется), то нужно прописать:
```html
html {
    box-sizing: border-box;
}

*,
*::after,
*::before {
    box-sizing: inherit;
}
```
<p align="center">
  <img height="400" src="logos/border-box.svg" alt="border-box"/>
</p>

4) Если у нас в некотором месте html документа стоят подряд одинаковые элементы с одинаковыми классами и нужно что-бы к первому стиль не применился то пишем:
```html
.header__item+.header__item {
    margin-left: 44px;
}
```
(ВНИМАНИЕ!!! Имя класса header__item дано для примера, вместо него может быть то имя которое мы зададим ему сами)

# Разное
Верстку которую мы делаем по макету 'SuperHost' я загрузил сюда (на github) в директорию super-host

<br />
<br />
<br />
<p align="center">
  <img with="100" height="100" src="logos/html-5.svg" alt="html-logo"/>
  <img with="100" height="100" src="logos/css.svg" alt="css-logo"/>
  <img with="100" height="100" src="logos/javascript.svg" alt="js-logo"/>
  <img with="100" height="100" src="logos/react.svg" alt="react-logo"/>
  <img with="100" height="100" src="logos/redux.svg" alt="redux-logo"/>
  <img with="100" height="100" src="logos/firebase.svg" alt="firebase"/>
  <img with="100" height="100" src="logos/graphql.svg" alt="graphql"/>
  <img with="100" height="100" src="logos/redux-saga.svg" alt="redux-saga-logo"/>
  <img with="100" height="100" src="logos/material-ui-1.svg" alt="material-ui-logo"/>
</p>
