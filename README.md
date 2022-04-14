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
<!-- Contacts -->
<style>
    body {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
        font-size: 11pt;
    }

    .container {
        background-color: #303030;
        color: #888;
        text-align: center;
        padding: 10px;
    }

    h2 {
        color: #FFF;
        padding: 35px 0 0 0;
    }

    .container p {
        padding: 0 30px 20px 30px;
    }

    input[type="text"],
    textarea {
        width: 100%;
        background-color: #282828;
        padding: 0.75em;
        margin: 0.75em 0;
        border-radius: 8px;
    }

    input[type="submit"] {
        background-color: #43B3E0;
        color: #FFF;
        width: 100%;
        font-size: 1.2em;
        font-weight: 600;
        border-radius: 8px;
        padding: 1em 0;
    }

    hr {
        border: 0;
        border-top: 1px solid #444;
    }
    footer{
        padding:30px;
    }
</style>
<section>
    <div class="container">
        <header>
            <h2>Lorem ipsum dolor sit amet</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum beatae quas velit obcaecati doloribus
                ullam eveniet sit adipisci, neque ad similique ut ab fugiat dolor officia rerum quam minima. Quam.</p>
        </header>
        <div>
            <form action="#">
                <input type="text" placeholder="Name">
                <input type="text" placeholder="Email">
                <input type="text" placeholder="Subject">
                <textarea name="" id="" cols="30" rows="10" placeholder="Message"></textarea>
                <input type="submit" value="Send Message">
            </form>
        </div>
    </div>
</section>
<section>
    <div class="container">
        <hr>
        <footer> © Untitled. All rights reserved. </footer>
    </div>
</section>
```
