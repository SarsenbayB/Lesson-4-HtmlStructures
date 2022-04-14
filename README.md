# HtmlStructures

### Nav
Элемент nav используется для навигации по сайту. 
     Это ненумерованный список с набором ссылок.
```
<style>
    body {
        font-family: Arial, Helvetica, sans-serif;
        margin: 0;
        padding: 0;
    }

    nav {
        background-color: #282828;
        height: 3.5em;
        position: fixed;
        width: 100%;
        text-align: center;
    }

    nav ul {
        margin: 0 auto;
    }

    nav li {
        display: inline-block;
    }

    nav li a {
        color: #FFF;
        text-decoration: none;
        font-weight: 400;
        padding: 0 1.25em;
        line-height: 3.5em;
    }
</style>
<!-- Nav -->
<nav>
    <ul>
        <li>
            <a href="#">Обо мне</a>
        </li>
        <li>
            <a href="#">Мои работы</a>
        </li>
        <li>
            <a href="#">Портфолио</a>
        </li>
        <li>
            <a href="#">Контакты</a>
        </li>
    </ul>
</nav>
```

### Section
Общий раздел, который имеет заголовок, колонтитулы.
Используется для оптимизации поисковой системы.
Разница от div в том, что div общий контейнер, исползуется для группировки, и позиционирования элементов при помощи css
```
<article>
            <span>01</span>
            <div class="content">
                <h3>Portitor ullamcorper</h3>
                <p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante
                    interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
            </div>
        </article>
```
### Article
Независимая часть документа, например пост, статья, заметка, комментарии, 
Используется для организации и управления сайтом
```
<section>
    <header>
        <h2>Erat lacinia</h2>
    </header>
    <div>
        <article>
            <span>01</span>
            <div class="content">
                <h3>Portitor ullamcorper</h3>
                <p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante
                    interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
            </div>
        </article>
        <article>
            <span>02</span>
            <div class="content">
                <h3>Sapien veroeros</h3>
                <p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante
                    interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
            </div>
        </article>
        <article>
            <span>03</span>
            <div class="content">
                <h3>Quam lorem ipsum</h3>
                <p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante
                    interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
            </div>
        </article>
        <article>
            <span>04</span>
            <div class="content">
                <h3>Sed magna finibus</h3>
                <p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante
                    interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
            </div>
        </article>
    </div>
</section>
```
