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

### Article
Независимая часть документа, например пост, статья, заметка, комментарии, 
Используется для организации и управления сайтом
```
<style>
    #home {
        text-align: center;
        color: #888;
        font-family: Arial, Helvetica, sans-serif;
        font-size: 10pt;
        padding: 5em 0;
    }
    .image img {
        width: 200px;
        height: 200px;
        border-radius: 100%;
    }

    h1 {
        font-weight: 300;
    }
</style>
<article id="home">
    <div class="container">
        <div class="image">
            <img src="James_Bond.jpg" alt="">
        </div>
        <div>
            <h1>Привет. Я <strong>James Bond</strong>.</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Veritatis officia quod id officiis? Nam
                incidunt cum voluptates deleniti error doloribus qui accusantium possimus molestias, voluptatem
                blanditiis delectus magni eius tempore.</p>
           
        </div>
    </div>
</article>
```

### Section
Общий раздел, который имеет заголовок, колонтитулы.
Используется для оптимизации поисковой системы.
Разница от div в том, что div общий контейнер, исползуется для группировки, и позиционирования элементов при помощи css
```

```
