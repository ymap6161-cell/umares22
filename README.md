<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Umarjon Turmanov – Веб-разработчик</title>
  <!-- Подключаем иконки -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: linear-gradient(135deg, #2c5364, #203a43, #0f2027);
      color: #fff;
    }

    header {
      background: rgba(0,0,0,0.4);
      text-align: center;
      padding: 40px 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .logo {
      font-size: 2.5em;
      font-weight: bold;
      color: #ffcc00;
      margin-bottom: 10px;
    }

    header h1 {
      margin: 10px 0 5px;
      font-size: 2.5em;
    }

    header p {
      margin: 0;
      font-size: 1.2em;
      color: #ccc;
    }

    .flags {
      margin: 15px 0;
      font-size: 2em;
    }

    nav {
      margin-top: 15px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffcc00;
    }

    section {
      padding: 70px 20px;
      max-width: 900px;
      margin: 0 auto;
      text-align: center;
    }

    section h2 {
      font-size: 2em;
      margin-bottom: 20px;
      color: #ffcc00;
    }

    section p, section ul {
      font-size: 1.1em;
      line-height: 1.6;
      color: #eee;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin: 15px 0;
      font-size: 1.2em;
    }

    ul li i {
      color: #ffcc00;
      margin-right: 8px;
    }

    .profile-img {
      display: block;
      margin: 20px auto;
      border-radius: 50%;
      max-width: 200px;
      border: 5px solid #ffcc00;
      box-shadow: 0 0 20px rgba(255, 204, 0, 0.7);
    }

    footer {
      background: rgba(0,0,0,0.7);
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    footer p {
      margin: 0;
      font-size: 0.9em;
      color: #bbb;
    }

    @media (max-width: 600px) {
      nav {
        display: flex;
        flex-direction: column;
        align-items: center;
      }
      nav a {
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

  <!-- Шапка -->
  <header>
    <div class="logo"><i class="fas fa-laptop-code"></i> UT</div>
    <h1>Umarjon Turmanov</h1>
    <p>Начинающий веб-разработчик</p>
    <div class="flags">🇹🇯 🇩🇪</div>
    <nav>
      <a href="#about"><i class="fas fa-user"></i> Обо мне</a>
      <a href="#skills"><i class="fas fa-code"></i> Навыки</a>
      <a href="#projects"><i class="fas fa-project-diagram"></i> Проекты</a>
      <a href="#hobby"><i class="fas fa-futbol"></i> Хобби</a>
      <a href="#contact"><i class="fas fa-envelope"></i> Контакты</a>
    </nav>
  </header>

  <!-- Обо мне -->
  <section id="about">
    <h2>Обо мне</h2>
    <img src="https://placekitten.com/300/300" alt="Фото Umarjon Turmanov" class="profile-img">
    <p><b>Umarjon Turmanov</b>, родился <b>07.10.2005</b> в городе <b>Душанбе, Таджикистан</b>. 
       С детства меня вдохновляли компьютеры и технологии.</p>
    <p>После окончания школы я переехал в Германию, где начал новую главу своей жизни. 
       Сейчас я прохожу <b>Ausbildung как Koch (повар)</b>, но моё настоящее призвание — программирование.</p>
    <p>Сегодня я учу <b>HTML, CSS и JavaScript</b>, создаю свои первые проекты и строю фундамент для будущего в IT. 
       Этот сайт — символ моих первых шагов на пути к мечте 🚀</p>
  </section>

  <!-- Навыки -->
  <section id="skills">
    <h2>Навыки</h2>
    <ul>
      <li><i class="fab fa-html5"></i> HTML</li>
      <li><i class="fab fa-css3-alt"></i> CSS</li>
      <li><i class="fab fa-js"></i> JavaScript (начальный уровень)</li>
    </ul>
  </section>

  <!-- Проекты -->
  <section id="projects">
    <h2>Проекты</h2>
    <p>Мои первые учебные проекты:</p>
    <ul>
      <li><i class="fas fa-globe"></i> Простые сайты</li>
      <li><i class="fas fa-calculator"></i> Калькулятор</li>
      <li><i class="fas fa-tasks"></i> Список задач (To-Do List)</li>
    </ul>
  </section>

  <!-- Хобби -->
  <section id="hobby">
    <h2>Мои увлечения</h2>
    <p><i class="fas fa-desktop"></i> Моё главное хобби — работа с компьютером. 
       Я люблю учиться новому, пробовать идеи в коде и видеть, как они оживают на экране.</p>
    <p><i class="fas fa-futbol"></i> Я также обожаю футбол ⚽. 
       Он учит меня командной работе, терпению и стремлению к победе — качествам, которые нужны программисту.</p>
    <p><i class="fas fa-bolt"></i> Я верю, что настойчивость и труд превратят мою мечту в реальность. 
       Моя цель — стать профессиональным разработчиком и создавать проекты, 
       которые будут вдохновлять других так же, как технологии вдохновляют меня.</p>
  </section>

  <!-- Контакты -->
  <section id="contact">
    <h2>Контакты</h2>
    <p><i class="fas fa-envelope"></i> Email: <a href="mailto:umarturmanov11@gmail.com">umarturmanov11@gmail.com</a></p>
    <p><i class="fab fa-github"></i> GitHub (будет позже)</p>
  </section>

  <!-- Подвал -->
  <footer>
    <p>&copy; 2025 Umarjon Turmanov. Все права защищены.</p>
  </footer>

</body>
</html>
