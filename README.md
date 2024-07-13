  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Team - Маркетинговая компания</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>My Team</h1>
            <p>Ваш партнер в мире маркетинга</p>
            <nav>
                <ul>
                    <li><a href="#about">О нас</a></li>
                    <li><a href="#services">Наши услуги</a></li>
                    <li><a href="#portfolio">Портфолио</a></li>
                    <li><a href="#contact">Контакты</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>О нас</h2>
            <p>Мы - команда профессионалов, специализирующаяся на разработке и внедрении маркетинговых стратегий, которые помогают нашим клиентам достигать своих целей. Наш опыт и креативный подход позволяют нам создавать уникальные решения для каждого проекта.</p>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>Наши услуги</h2>
            <ul>
                <li>Разработка маркетинговых стратегий</li>
                <li>SEO оптимизация</li>
                <li>Социальные медиа маркетинг</li>
                <li>Контент-маркетинг</li>
                <li>Email маркетинг</li>
            </ul>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Портфолио</h2>
            <div class="portfolio-items">
                <div class="portfolio-item">
                    <img src="project1.jpg" alt="Проект 1">
                    <p>Проект 1: Успешная кампания для клиента A</p>
                </div>
                <div class="portfolio-item">
                    <img src="project2.jpg" alt="Проект 2">
                    <p>Проект 2: SEO оптимизация для клиента B</p>
                </div>
                <div class="portfolio-item">
                    <img src="project3.jpg" alt="Проект 3">
                    <p>Проект 3: Социальные медиа стратегия для клиента C</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Контакты</h2>
            <form action="submit_form.php" method="post">
                <label for="name">Имя:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Сообщение:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Отправить</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 My Team. Все права защищены.</p>
        </div>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header p {
    font-size: 1.2em;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.container {
    width: 80%;
    margin: 0 auto;
}

section {
    padding: 20px 0;
}

h2 {
    font-size: 2em;
    margin-top: 0;
}

p, ul {
    font-size: 1.1em;
    line-height: 1.6;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background-color: #4CAF50;
    color: white;
    margin: 5px 0;
    padding: 10px;
}

.portfolio-items {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.portfolio-item {
    width: 30%;
    margin: 10px 0;
    text-align: center;
}

.portfolio-item img {
    width: 100%;
    height: auto;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-top: 10px;
    font-weight: bold;
}

form input, form textarea {
    margin-top: 5px;
    padding: 10px;
    font-size: 1em;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    margin-top: 20px;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 4px;
    font-size: 1.2em;
    cursor: pointer;
}

form button:hover {
    background-color: #45a049;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}


