# my-sitehtml,
body {
  margin: 0;
  font-family: "Arial", sans-serif;
  font-size: 14px;
  line-height: 20px;
}

body {
  min-width: 430px;
  border: 2px dashed #c7e4ff;
}

html::before,
body::before,
header::before,
footer::before,
main::before {
  color: #7fc1ff;
}

main,
header,
footer {
  background-color: #f3faff;
  border: 2px solid #7fc1ff;
}

nav,
section,
article,
aside {
  background-color: #f9f7ff;
  border: 2px solid #9779ec;
}

nav::before,
section::before,
article::before,
aside::before {
  color: #9779ec;
}

h1,
h2,
h3 {
  font-size: 18px;
  background-color: #ffffff;
  border: 2px solid #ff994f;
}

h1::before {
  content: "h1";
  color: #ff994f;
}

h2::before {
  content: "h2";
  color: #ff994f;
}

h3::before {
  content: "h3";
  color: #ff994f;
}

p {
  background-color: #ffffff;
  border: 2px solid #f36dff;
}

p::before {
  color: #f36dff;
  content: "p";
}

* {
  position: relative;
  padding: 25px 25px 20px;
  margin: 0;
  border-radius: 4px;
}

*:not(:last-child) {
  margin-bottom: 20px;
}

*::before {
  position: absolute;
  top: 8px;
  left: 10px;
  font-weight: 700;
  font-size: 11px;
  line-height: 10px;
  letter-spacing: 0.04em;
}

html::before {
  content: "html";
}

body::before {
  content: "body";
}

main::before {
  content: "main";
}

header::before {
  content: "header";
}

footer::before {
  content: "footer";
}

section::before {
  content: "section";
}

article::before {
  content: "article";
}

aside::before {
  content: "aside";
}

nav::before {
  content: "nav";
}

body {
  margin: 0;
  min-width: 960px;
  font-family: "Montserrat", "Helvetica", "Arial", sans-serif;
  font-size: 16px;
  line-height: 32px;
  color: #222222;
  background-color: #f2f4f6;
  background-image: url("img/hero-bg.jpg");
  background-repeat: no-repeat;
  background-position: top center;
}

.container {
  max-width: 928px;
  margin: 0 auto;
  padding: 0 16px;
}

.page-header {
  margin: 0 0 160px;
  padding: 32px 0 32px;
}

.page-header .container,
.page-footer .container {
  max-width: 1408px;
  text-align: right;
}

.page-header a {
  margin-left: 56px;
  color: #288be6;
  text-decoration: none;
  background-repeat: no-repeat;
  background-position: left;
}

.header-email {
  padding-left: 30px;
  background-image: url("img/icon-email-header.svg");
}

.header-phone {
  padding-left: 25px;
  background-image: url("img/icon-phone-header.svg");
}

.hero-image {
  margin-bottom: 620px;
}

.hero-image .container {
  max-width: 1408px;
  text-align: center;
}

.heading {
  margin: 0 0 16px;
  font-family: "Old Standard TT", "Times", "Times New Roman", serif;
  font-size: 88px;
  line-height: 96px;
  font-weight: 400;
}

.hero-image p {
  margin: 0;
  font-size: 32px;
  line-height: 48px;
}

.intro {
  margin: 0 0 120px;
}

.subheading {
  margin: 0 0 56px;
  font-family: "Old Standard TT", "Times", "Times New Roman", serif;
  font-size: 64px;
  line-height: 80px;
  font-weight: 400;
  text-align: center;
}

.user-image {
  margin: 0 0 32px;
  text-align: center;
}

.intro h3,
.portfolio h3 {
  margin: 0 0 12px;
  font-size: 28px;
  line-height: 40px;
  font-weight: 500;
}

.intro p {
  margin: 0 0 32px;
}

.skills-list {
  margin: 0;
  padding: 0;
}

.skills-list dt {
  padding-left: 32px;
  background-repeat: no-repeat;
  background-position: left;
}

.skill-html {
  background-image: url("img/icon-html.svg");
}

.skill-css {
  background-image: url("img/icon-css.svg");
}

.level {
  margin: 4px 0 16px;
  padding: 0;
  height: 14px;
  font-size: 0;
  background-color: #ffffff;
  border: 1px solid #86c3fa;
  border-radius: 8px;
}

.level div {
  margin: 1px;
  height: 12px;
  background-color: #288be6;
  border-radius: 6px;
}

.portfolio {
  margin: 0 0 120px;
}

.projects {
  margin: 0;
  padding: 0;
  list-style: none;
}

.projects li {
  margin: 0 0 80px;
}

.project-image {
  margin: 0 0 24px;
  text-align: center;
}

.projects p {
  margin: 0 0 24px;
}

.button {
  padding: 6px 20px;
  display: inline-block;
  vertical-align: baseline;
  text-decoration: none;
  text-transform: uppercase;
  border-radius: 4px;
  background-color: #288be6;
  color: #ffffff;
}

.page-footer {
  padding: 40px 0;
  background-color: #00417d;
  color: #ffffff;
}

.page-footer a {
  margin-left: 56px;
  color: inherit;
  text-decoration: none;
  background-repeat: no-repeat;
  background-position: left;
}

.footer-email {
  padding-left: 30px;
  background-image: url("img/icon-email-footer.svg");
}

.footer-phone {
  padding-left: 25px;
  background-image: url("img/icon-phone-footer.svg");
}
<!DOCTYPE html>
<html lang="ru">
  <head>
    <link href="https://fonts.googleapis.com/css?family=Montserrat:400,500,700|Old+Standard+TT&display=swap&subset=cyrillic" rel="stylesheet">
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <title>Портфолио Junior верстальщика</title>
  </head>

  <body>
    <header class="page-header">
    <div class="container">
      <a href="mailto:romeo.lts.1994@gmail.com" class="header-email"> romeo.lts.1994@gmail.com</a>
     <a href="tel:+48577586212" class="header-phone">  +48577586212</a>
    </div>
    
    
    </header>

    <section class="hero-image">
      <div class="container">
      <h1 class="heading">Roman Lutsenko</h1>
      <p>Junior верстальщик</p></div>
    </section>

    <section class="intro">
      <h2 class="subheading">Давайте познакомимся</h2>
      <figure class="user-image">
        <img src="files/user.jpg" width="928" height="536" alt="Фотография Романа">
      </figure>
      <h3>Учюсь верстать</h3>
      <p>Сижу на карантине, изучаю новую для себя професию.</p>
      <h3>Чем могу быть полезен</h3>
      <p>Текст о том, чем могу быть полезен.</p>
    </section>

    <section class="portfolio">
      <h2 class="subheading">Мои работы</h2>
      <figure class="project-image">
        <img src="files/project.jpg" width="928" height="536" alt="Cайт инструктора Кекса">
      </figure>
      <h3>Сайт инструктора Кекса</h3>
      <p>Мой первый сайт.</p>
      <a class="button" href="source/project/index.html">Открыть страницу</a>
      <h3>Блог начинающего верстальщика</h3>
      <p>Статический блог про обучение HTML и CSS.</p>
    </section>

    <footer class="page-footer">
      Контакты: 
      <a class="footer-phone" href="tel:+48577586212">+48577586212</a> 
      <a class="footer-email" href="mailto:romeo.lts.1994@gmail.com">romeo.lts.1994@gmail.com</a>

    </footer>
  </body>
</html>
