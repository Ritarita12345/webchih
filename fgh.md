# webchih
<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Тихачева Маргарита Александровна</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №3.«HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>Visual SStudio Code</b> редактор исходного кода, разработанный Microsoft для Windows, Linux и macOS. Позиционируется как «лёгкий» редактор кода для кроссплатформенной разработки веб- и облачных приложений.</p>
<p><b>HTML</b> — стандартизированный язык гипертекстовой разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора.</p>

<br>
<h1 align = "center">Цели и задачи</h1>


<p>Создать простую страницу, продемонстрировать умение программировать.</p>

<p>ФУНКЦИОНАЛЬНЫЕ ТРЕБОВАНИЯ:</p>
<ul>
<li>Создать веб-страницу</li>
</ul>

<p></p>



<h1 align = "center">Решение</h1>

<p>Для выполнения этой лабораторной работы, я пользовалась:</p>

<ul>
<li>Вашими парами</li>
<li>Материалом в сети интернет</li>
</ul>


<h2 align = "center">Главный файл</h2>


```kotlin
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        #fd:hover{background-color: aquamarine;}
        #bgu,#gd,#jgsn,#fd,#sg{color: blueviolet; font-size: 18px;}
        
    </style>
    <link rel="icon" href="emo.ico">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="background-color: #f0f0f0;">
    <h1 id="bgu">df</h1>
    <h2 id="sgm" style="color: rgb(94, 155, 196);">dg</h2>
    <h3 id="gd" style="background-color: black;">dg</h3>
    <h4 id="jgsn" style="border: 8px inset rgb(248, 149, 190); border-radius: 9px;">gd</h4>
    <h5 id="fd" >dg</h5>
    <h6 id="sg">dg</h6>
    <form>
          <input type="text" />
          <input type="number"/>
          <input type="month"/>
          <input type="checkbox"/>
          <input type="button"  value="поставьте 5"/>
          <button style="height: 300px; width: 800px;background-image: url('png-clipart-computer-icons-smiley-emoticon-icon-design-smiley-miscellaneous-face.png');background-size: 50%;"></button>
          <input type="color"/>
      </form>
      <ul type="square">
        <li>список</li>
        <li>список</li>
        <li>список</li>
        <li>список</li>
       </ul>
       <ol>
        <li>аааа</li>
        <li>аАаАа</li>
        <li>ААААААА</li>
        <li>ааа....</li>
       </ol>
</body>
</html>
```
```kotlin
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: rgb(19, 112, 19);">
    <p style="color: rgb(255, 255, 255); font-family: Arial, Helvetica, sans-serif;">Две равно уважаемых семьи
        В Вероне, где встречают нас событья,
        Ведут междоусобные бои
        И не хотят унять кровопролитья.
        
        Друг друга любят дети главарей,
        Но им судьба подстраивает козни,
        И гибель их у гробовых дверей
        Кладет конец непримиримой розни.
        
        Их жизнь, любовь и смерть и, сверх того,
        Мир их родителей на их могиле
        На два часа составят существо
        Разыгрываемой пред вами были.
        
        Помилостивей к слабостям пера —
        Их сгладить постарается игра.</p>
       <h1 class="container" id="h1">Акт 1. Сцена 1</h1>
       <h2 class="container" id="h2">Верона. Площадь.Входят Самсон и Грегорио, слуги Капулетти.</h2>
       <h3 class="container" id="h3">Самсон:Грегорио, уговор: перед ними не срамиться.</h3>
       <h4 class="container" id="h4">Грегорио:Что ты! Наоборот. Кого ни встречу, сам осрамлю.</h4>
       <h5 class="container" id="h5">Самсон:Зададим им баню!</h5>
       <h6 class="container" id="h6">Грегорио:Самим бы выйти сухими из воды.</h6>
       <iframe src="Untitled-1.html" width="2000" height="1000">
     </iframe>
</body>
</html>
```
```kotlin
<!DOCTYPE html>
<html lang="en">
<head>
<style> 
a:hover {color:#75af16;} 
.bth{
  background-color: #DB1F48;
  color: #fff;
  transition: background-color 1s;
}  
.bth:hover {
  background-color: #a5f0b1;
}
.dropdown {
  display: inline-block;
  position: relative;
}
.dropdown-options {
  display: none;
  position: absolute;
  overflow: auto;
}

.dropdown:hover .dropdown-options {
  display: block;
}
.box {
  opacity: 0;
  transition: all 1s ease;
}

.box-wrap:hover .box {
  opacity: 1;
}
@-webkit-keyframes pulsate {
 50% { color: #fff; text-shadow: 0 -1px rgba(0,0,0,.3), 0 0 5px #ffd, 0 0 8px #fff; }
}
@keyframes pulsate {
 50% { color: #c91818; text-shadow: 0 -1px rgba(0,0,0,.3), 0 0 5px #ffd, 0 0 8px #fff; }
}
#blink7 {
  color: rgb(255, 255, 255);
  text-shadow: 0 -1px rgba(0,0,0,.1);
  -webkit-animation: pulsate 1.2s linear infinite;
  animation: pulsate 1.2s linear infinite;
  text-align: center;
  font-size: 100px;
}
#table tr:nth-child(even){background:rgb(92, 82, 82)}
</style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="background-color: rgb(175, 110, 57);" >
    <h1 style="text-align: center; color: rgb(189, 19, 19); outline: thick double #ca8326;text-shadow: #FC0 1px 0 10px;">Сайт для всех любителей кваса</h1>
    <div style="background-color: rgb(240, 236, 211); border: 6px dotted wheat; border-radius: 50%; padding: 5%; text-align: center; box-shadow: 10px 5px 5px rgb(145, 9, 9); height: 150px; width: 150px;">
        <input type="text" /> <h2 style="font-size: small;">ваш квасовый псевдоним</h2>
        <br/>  <input type = "text"  /> <h2 style="font-size: small;">ваш квасовый пароль</h2>
        <br/>  <button class="bth">квасификация</button>
    </div>
    <table id="table" style="padding-left: 45%;">
      <tr><th> это</th><th>таблица<th>)))))</th></tr>
      <tr><td> все </td><td>еще<td> таблица</td></tr>
      <tr><td> это</td><td>тоже<td> таблица</td></tr>
      <tr><td> ААааАа</td><td>ЫЫыыЫЫ<td> ЭЭээээЭЭ</td></tr>
      </table>
      <img style="width: 605px; border-style: double;" src="kvas.gif"/>  <img style="border-style: double; width: 605px;" src="kvas.gif"/>  <img style="border-style: double;width: 605px;" src="kvas.gif"/>
        <a href=Untitled-2.html>Наши партнеры</a>
        <div class="dropdown">
          <a>наши продукты</a>
          <div class="dropdown-options">
            <a>квас</a>
            <br/> <a>квас</a>
            <br/>  <a>еще квас</a>
          </div>
        </div>
        <div class="box-wrap">хехе
          <div class="box">хихи</div>
        </div>
        <div id="blink7">квасец</div>
</body>
</html>
```
```kotlin
.container{padding-left: 50%;}
    #h1,h2,h3,h4,h5,h6{color: rgb(171, 255, 171);width: 100px;height: 100px;font-size: 20px;padding-top: 10px; font-family: Arial, Helvetica, sans-serif;}
```

<h1 align = "center">Результат</h1>

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, я познакомилась с основами языка html и научилась создавать постые карты.</p>
