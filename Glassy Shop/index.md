<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="utf-8">
    <title>GlaccyShop</title>
    <link rel="stylesheet" href="#">
  </head>
  <body>
    <header class="header">
      <a href="#" class="header_logo">
        <img src="#">
      </a>
      <nav class="header_nav">
        <ul>
          <li><a href="#" class="header_link">Каталог</a>
            <ul>
              <li><a href="#">Новинки</a></li>
              <li><a href="#">Сливочное</a></li>
              <li><a href="#">Щербеты</a></li>
              <li><a href="#">Фруктовый лед</a></li>
              <li><a href="#">Мелорин</a></li>
            </ul>
          </li>
          <li><a href="#" class="header_link">Доставка и оплата</a></li>
          <li><a href="#" class="header_link">О компании</a></li>
        </ul>
        <a href="#" class="search"></a><!--форма поиска-->
        <a href="#" class="log_in">
          <span>Вход</span><!--форма входа+иконка входа через псевдоэлемент-->
        </a>
        <a href="#" class="basket">
            <span>Пусто</span><!--здесь должна быть ваша корзина+
            иконка входа через псевдоэлемент-->
        </a>
      </nav>
      <p class="header_data">c 10 до 20, ежедневно
        <span class="phone">8-812-450-25-25</span>
      </p>
    </header>
    <main>
      <h1>Крем-брюле и пломбир с малиновым джемом</h1>
      <div class="switch">
        <button></button><!--понятия не имею, как сделать листалку-->
        <button></button>
        <button></button>
      </div>
      <a href="#" class="main">Давайте оба</a>
      <ul class="article-preview">
        <li class="raspberry">
          <h2>Малинка даром!<h2>
          <p>При покупке 2 кг любого фруктового мороженого, добавим в ваш заказ
          банку малинового варенья бесплатно.</p>
          <a href="#" class="raspberry">Хочу варенье!</a>
        </li>
        <li class="chocolate">
            <h2>Шоколадки даром!<h2>
            <p>При покупке 2 кг пломбира, добавим в ваш заказ упаковку
            вкуснейшей шоколадной присыпки совершенно бесплатно.</p>
            <a href="#" class="chocolate">Хочу шоколадки!</a>
        </li>
      </ul>
        <ul class="ice-cream">
        <li>
          <div class="hit"></div>
          <img src="#"><!--изображение 1-->
          <p>310 &#x20bd;<span>/кг</span></p>
          <p class="description description-orange">
            <a href="#">Сливочное с апельсиновым джемом и цитрусовой стружкой</a>
          </p>
        </li>
        <li>
          <div class="hit"></div>
          <img src="#"><!--изображение 2-->
          <p>380 &#x20bd;<span>/кг</span></p>
          <p class="description description-coffee">
            <a href="#">Сливочно-кофейное с кусочками шоколада</a>
          </p>
        </li>
        <li>
          <div class="hit"></div>
          <img src="#"><!--изображение 3-->
          <p>355 &#x20bd;<span>/кг</span></p>
          <p class="description description-orange">
            <a href="#">Сливочно-клубничное с присыпкой из белого шоколада</a>
          </p>
        </li>
        <li>
          <div class="hit"></div>
          <img src="#"><!--изображение 4-->
          <p>415 &#x20bd;<span>/кг</span></p>
          <p class="description description-orange">
            <a href="#">Сливочное с апельсиновым джемом и цитрусовой стружкой</a>
          </p>
        </li>
      </ul>
      <section class="about_glaccy"><!--картинки напротив каждого пункта через псевдоэлемент-->
        <p>Магазин Глэйси - это онлайн- и офлайн-магазин по продаже мороженого
        собственного производства на развес</p>
        <p>Все наше мороженое изготавливается на собственном производстве, с
        использованием современного оборудования и проверенных временем технологий.</p>
        <p>Для приготовления мороженого используются настоящие сливки и молоко
        высочайшего класса. Все дополнительные ингредиенты и добавки произведены из
        натурального, экологически чистого сырья.</p>
        <p>Доставка нашего мороженогдо заказчиков осуществляется в специальном
        термопаке, который не дает мороженому растаять в пути и позволяет сохранить
        первосходный вкус.</p>
      </section>
      <article class="blog_new">
        <p>Новое в нашем блоге</p>
        <p><a href="#">10 способов сервировки фруктовых щербетов к столу</a></p>
      </article>
      <form class="subscribe_form">
        <p>Подпишитесь на нашу сладкую рассылку и будете всегда в курсе всего
        самого вкусного, что у нас происходит. Обещаем не спамить и не слать вяской
        ненужной ерунды. Честно =)</p>
        <div>
          <input name="email" required type="email" placeholder="Электронная почта">
        </div><!--не уверена, что точно прописала форму обратной связи-->
        <button type="submit">Отправить<button>
      </form>
      <div class="map">
        <img src="#"><!--карта Питера-->
        <div>
          <p class="address">Адрес главного офиса и офлайн-магазина:
            <span>ул. Большпя Конюшенная 19/8, Санкт-Петербург</span>
          </p>
          <p class="order">Для заказов по телефону:
            <span>8 812 450 25 25</span>
          (с 10 до 20 едежневно)
          </p>
          <a href="#" class="callback_form">Форма обратной связи</a>
        </div>
    </main>
    <footer>
      <ul class="social_networks">
        <li><a href="#">
          <img src="#" alt="Twitter">
          </a>
        </li>
        <li><a href="#">
          <img src="#" alt="Instagram">
          </a>
        </li>
        <li><a href="#">
          <img src="#" alt="Facebook">
          </a>
        </li>
        <li><a href="#">
          <img src="#" alt="Vkontakte">
          </a>
        </li>
      </ul>
      <nav class="footer_navigation">
        <ul>
          <li><a href="#">Для поставщиков</a><!--иконка перед строкой-->
          <li><a href="#">О производстве</a>
          <li><a href="#">Наши документы</a>
          <li><a href="#">Экологические стандарты</a>
        <!--либо нужно было разбивать на 2 списка, чтобы получить 2 колонки?-->
        </ul>
        <div>
          <img src="#" class="html_logo">
          <p>Сделано в <a href="#">HTML Academy</a>&#169;2017</p>
      </footer>
  </body>
</html>
