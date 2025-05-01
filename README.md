# practice
/* Файл: index.html (Домашняя страница) */
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Главная | Проект 2ГИС</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Проект 2ГИС: Университет в 3D</h1>
    <nav>
      <a href="index.html">Главная</a>
      <a href="about.html">О проекте</a>
      <a href="team.html">Участники</a>
      <a href="journal.html">Журнал</a>
      <a href="resources.html">Ресурсы</a>
    </nav>
  </header>
  <main>
    <h2>Аннотация проекта</h2>
    <p>Проект «2ГИС: Университет в 3D» направлен на упрощение навигации по территории вуза для новых студентов. В рамках проекта мы создаём и интегрируем 3D-модели университетских корпусов в сервис 2ГИС, чтобы каждый мог быстро ориентироваться и находить нужные помещения.</p>
  </main>
</body>
</html>

/* Файл: about.html (О проекте) */
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>О проекте | Проект 2ГИС</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>О проекте</h1>
    <nav>
      <a href="index.html">Главная</a>
      <a href="about.html">О проекте</a>
      <a href="team.html">Участники</a>
      <a href="journal.html">Журнал</a>
      <a href="resources.html">Ресурсы</a>
    </nav>
  </header>
  <main>
    <ul>
      <li><strong>Цель:</strong> Облегчить адаптацию студентов первого курса в кампусе вуза.</li>
      <li><strong>Задачи:</strong>
        <ul>
          <li>Создание 3D-моделей основных корпусов.</li>
          <li>Интеграция моделей в 2ГИС.</li>
          <li>Актуализация информации по аудиториям.</li>
        </ul>
      </li>
      <li><strong>Инструменты:</strong> Blender, SketchUp, API 2ГИС, Hugo.</li>
      <li><strong>Сроки:</strong> февраль – май 2025.</li>
    </ul>
  </main>
</body>
</html>

/* Файл: team.html (Участники) */
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Участники | Проект 2ГИС</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Участники проекта</h1>
    <nav>
      <a href="index.html">Главная</a>
      <a href="about.html">О проекте</a>
      <a href="team.html">Участники</a>
      <a href="journal.html">Журнал</a>
      <a href="resources.html">Ресурсы</a>
    </nav>
  </header>
  <main>
    <ul>
      <li><strong>Артём Падерин</strong> – координатор проекта. Руководит работой команды, оформляет сайт и презентационные материалы.</li>
      <li><strong>Титкин Степан</strong> – 3D-моделлер. Разрабатывает модели корпусов в Blender и SketchUp.</li>
      <li><strong>Соловей Никита</strong> – интегратор. Работает с API 2ГИС и отвечает за загрузку моделей в карту.</li>
    </ul>
  </main>
</body>
</html>

/* Файл: journal.html (Журнал) */
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Журнал | Проект 2ГИС</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Журнал проекта</h1>
    <nav>
      <a href="index.html">Главная</a>
      <a href="about.html">О проекте</a>
      <a href="team.html">Участники</a>
      <a href="journal.html">Журнал</a>
      <a href="resources.html">Ресурсы</a>
    </nav>
  </header>
  <main>
    <ul>
      <li><strong>15 февраля 2025:</strong> Сформирована команда, утверждена тема проекта.</li>
      <li><strong>1 марта 2025:</strong> Создана первая 3D-модель корпуса А в Blender.</li>
      <li><strong>25 марта 2025:</strong> Модель успешно загружена в тестовую карту 2ГИС, выявлены проблемы с масштабом.</li>
    </ul>
  </main>
</body>
</html>

/* Файл: resources.html (Ресурсы) */
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Ресурсы | Проект 2ГИС</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Полезные ресурсы</h1>
    <nav>
      <a href="index.html">Главная</a>
      <a href="about.html">О проекте</a>
      <a href="team.html">Участники</a>
      <a href="journal.html">Журнал</a>
      <a href="resources.html">Ресурсы</a>
    </nav>
  </header>
  <main>
    <ul>
      <li><a href="https://partner.api.2gis.com/" target="_blank">2ГИС для бизнеса (официальный сайт)</a></li>
      <li><a href="https://learn.sketchup.com/" target="_blank">Инструкция по SketchUp</a></li>
      <li><a href="https://github.com/" target="_blank">GitHub — примеры интеграции</a></li>
      <li><a href="https://docs.blender.org/manual/en/latest/" target="_blank">Blender Manual</a></li>
    </ul>
  </main>
</body>
</html>

/* Файл: style.css (общие стили для всех страниц) */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background-color: #f9f9f9;
  color: #333;
}
header {
  background-color: #0077cc;
  color: white;
  padding: 20px;
  text-align: center;
}
nav {
  margin-top: 10px;
}
nav a {
  margin: 0 10px;
  text-decoration: none;
  color: white;
  font-weight: bold;
}
main {
  padding: 20px;
}
ul {
  list-style: none;
  padding-left: 0;
}
li {
  margin-bottom: 10px;
}

