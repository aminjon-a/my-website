<!DOCTYPE html>
<html lang="ru">
<head>
     <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frontend</title>
    <meta name="description" content="Ресурсы и инструменты для фронтенд разработчиков. Узнайте о лучших практиках, фреймворках и современных технологиях.">
    <meta name="keywords" content="фронтенд, разработка, HTML, CSS, JavaScript, фреймворки, React, Vue, Angular, веб-дизайн, SEO, обучение">
    <meta name="author" content="Frontend">
    <meta name="robots" content="index, follow">
    <meta name="language" content="ru">
    <meta property="og:title" content="Сайт для фронтенд разработчиков">
    <meta property="og:description" content="Ресурсы и инструменты для фронтенд разработчиков. Узнайте о лучших практиках, фреймворках и современных технологиях.">
    <meta name="twitter:title" content="Сайт для фронтенд разработчиков">
    <meta name="twitter:description" content="Ресурсы и инструменты для фронтенд разработчиков. Узнайте о лучших практиках, фреймворках и современных технологиях.">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>План изучения фронтенда</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }

        h1 {
            text-align: center;
            color: #333;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .task {
            background-color: #fff;
            border-radius: 10px;
            padding: 20px;
            margin: 10px;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .task:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .task h3 {
            color: #007bff;
        }

        .task input[type="checkbox"] {
            margin-right: 10px;
        }

        .icon {
            width: 50px;
            height: 50px;
            background-color: #007bff;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 15px;
            transition: background-color 0.2s;
        }

        .icon:hover {
            background-color: #0056b3;
        }

        .icon img {
            width: 30px;
            height: 30px;
        }

        .resource {
            color: #007bff;
            text-decoration: none;
        }

        .resource:hover {
            text-decoration: underline;
        }

        iframe {
            width: 100%;
            height: 200px;
            border: none;
            margin-top: 15px;
        }
    </style>
</head>
<body>

    <h1>План изучения фронтенда на 9 месяцев</h1>
    <div class="container">

        <!-- Неделя 1-2: Основы HTML5 -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/732/732212.png" alt="HTML5 Icon">
            </div>
            <h3>Неделя 1-2: Основы HTML5</h3>
            <p>Изучение основных тегов, семантики и создание простой веб-страницы.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://developer.mozilla.org/ru/docs/Web/HTML" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/pQN-pnXPaVg" allowfullscreen></iframe>
        </div>

        <!-- Неделя 3-4: Основы CSS3 -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/732/732190.png" alt="CSS3 Icon">
            </div>
            <h3>Неделя 3-4: Основы CSS3</h3>
            <p>Изучение селекторов, шрифтов, цветов и стилизация веб-страницы.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://developer.mozilla.org/ru/docs/Web/CSS" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/yfoY53QXEnI" allowfullscreen></iframe>
        </div>

        <!-- Неделя 5-6: Продвинутый CSS3 -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/732/732190.png" alt="CSS3 Icon">
            </div>
            <h3>Неделя 5-6: Продвинутый CSS3</h3>
            <p>Flexbox, Grid, анимации и адаптивные макеты.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://developer.mozilla.org/ru/docs/Web/CSS" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/JJSoEo8JSnc" allowfullscreen></iframe>
        </div>

        <!-- Неделя 7-8: Sass -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/919/919831.png" alt="Sass Icon">
            </div>
            <h3>Неделя 7-8: Sass</h3>
            <p>Оптимизация CSS-кода с использованием Sass: переменные, вложенность, миксины.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://sass-lang.com/guide" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/_a5j7KoflTs" allowfullscreen></iframe>
        </div>

        <!-- Неделя 9-10: Основы JavaScript -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" alt="JavaScript Icon">
            </div>
            <h3>Неделя 9-10: Основы JavaScript</h3>
            <p>Переменные, типы данных, функции и циклы.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/hdI2bqOjy3c" allowfullscreen></iframe>
        </div>

        <!-- Неделя 11-12: DOM и события -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" alt="JavaScript Icon">
            </div>
            <h3>Неделя 11-12: DOM и события</h3>
            <p>Работа с DOM, добавление элементов и обработка событий.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://developer.mozilla.org/ru/docs/Web/API/Document_Object_Model" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/0ik6X4DJKCc" allowfullscreen></iframe>
        </div>

        <!-- Неделя 13-14: Асинхронность и AJAX -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" alt="JavaScript Icon">
            </div>
            <h3>Неделя 13-14: Асинхронность и AJAX</h3>
            <p>Промисы, fetch() и работа с API.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide/Using_promises" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/PoRJizFvM7s" allowfullscreen></iframe>
        </div>

        <!-- Неделя 15-16: Модули и ES6 -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" alt="JavaScript Icon">
            </div>
            <h3>Неделя 15-16: Модули и ES6</h3>
            <p>Модули, стрелочные функции, деструктуризация.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/import" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/IEf1KAcK6A8" allowfullscreen></iframe>
        </div>

        <!-- Неделя 17-18: Введение в Bootstrap -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/5968/5968672.png" alt="Bootstrap Icon">
            </div>
            <h3>Неделя 17-18: Введение в Bootstrap</h3>
            <p>Сетка Bootstrap, компоненты и адаптивная верстка.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://getbootstrap.com/docs/5.0/getting-started/introduction/" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/-qfEOE4vtxE" allowfullscreen></iframe>
        </div>

        <!-- Неделя 19-20: Введение в React.js -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/919/919851.png" alt="React Icon">
            </div>
            <h3>Неделя 19-20: Введение в React.js</h3>
            <p>Основы компонентов, JSX и состояния.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://reactjs.org/docs/getting-started.html" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/w7ejDZ8SWv8" allowfullscreen></iframe>
        </div>

        <!-- Неделя 21-22: Продвинутый React.js -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/919/919851.png" alt="React Icon">
            </div>
            <h3>Неделя 21-22: Продвинутый React.js</h3>
            <p>Hooks, управление состоянием и жизненный цикл компонентов.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://reactjs.org/docs/hooks-intro.html" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/TNhaISOUy6Q" allowfullscreen></iframe>
        </div>

        <!-- Неделя 23-24: Введение в WordPress -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/174/174881.png" alt="WordPress Icon">
            </div>
            <h3>Неделя 23-24: Введение в WordPress</h3>
            <p>Установка, создание тем и редактирование контента.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://wordpress.org/support/article/new-to-wordpress-where-to-start/" class="resource" target="_blank">Ресурс</a>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/FEwjdBCtCSI?list=PLDyJYA6aTY1kwHPV1cr6qsN7_3dCA-MB8" allowfullscreen></iframe>

        </div>

        <!-- Неделя 25-26: Figma для дизайна сайтов -->
        <div class="task">
            <div class="icon">
                <img src="https://cdn-icons-png.flaticon.com/512/5968/5968705.png" alt="Figma Icon">
            </div>
            <h3>Неделя 25-26: Figma для дизайна сайтов</h3>
            <p>Создание макетов и прототипов сайтов в Figma.</p>
            <label>
                <input type="checkbox"> Завершено
            </label>
            <br>
            <a href="https://www.figma.com/resources/learn-design/" class="resource" target="_blank">Ресурс</a>
            <iframe src="https://www.youtube.com/embed/jwCmIBJ8Jtc" allowfullscreen></iframe>
        </div>

    </div>
    <a href="BooksStore.html" target="_blank">
        <img src="image.png" alt="Нажмите для открытия новой страницы" style="width:300px;height:auto;">
    </a>
    
</body>
</html>

