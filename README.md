<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Avesta</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
  <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
  
  <script type="text/javascript">
  $(function() {
  $(window).scroll(function() {
  if($(this).scrollTop() != 0) {
  $('#topNubex').fadeIn();
  } else {
  $('#topNubex').fadeOut();
  }
  });
  $('#topNubex').click(function() {
  $('body,html').animate({scrollTop:0},700);
  });
  });
  </script>

<style>
  
</style>

</head>

<body>
  <div class="shap">
    <a href="index1.php">Авторизация</a><img src="Frame1.svg" align="left" style="width: 250px;height: 140px;">
    <h1 align="center">Торговый комплекс Avesta</h1>
  </div>

  <div class="cent">
    <h2 align="center">В нашем магазине имеется ассортимент высококачественных материалов</h2>
  </div>
  <div class="new">
    <h4 align="center">Внимание! Идет переоценка! Цены уточняйте у продавцов-консультантов</h4>
  </div>
  <div class="sidenav">
    <a href="#novoe">ТК Avesta</a>
    <a href="#forma">Форма</a>
    <a href="#end">Контакты</a>
  </div>
  <!--
  <div class="content">
    <h1 align="center">Наш магазин - это </h1>
    <table align="center" class="content-table">
    <tr>
      <td><p>-Доступные цены</p></td><td><img src="Frame 2.svg" class="content-img"></td>
    </tr>
    <tr>
      <td>
        <p>-Большой выбор</p>
      </td>
      <td>
        <img src="Frame 3.png" class="content-img">
      </td>
    </tr>
    <tr>
      <td>
        <p>-Прямые доставки</p>
      </td>
      <td>
        <img src="Frame 4.png" class="content-img">
      </td>
    </tr>
  </table>
</div>-->
<!--<div class="main" id="main">
  <h1 align="center">Ассортимент</h1>
  <table align="center" class="table">
    <tr>
      <td><h3>Электроинтрументы</h3>
      </td>
      <td><h3>Стройматериалы</h3>
      </td>
      <td><h3>Сантехника</h3>
      </td>
    </tr><tr>
      <td><img src="Электро.jpg" class="imoge"></td>
      <td><img src="Строй.png" class="imoge"></td>
      <td><img src="сантех.jpg" class="imoge"></td>
    </tr>
  </table>

  <table align="center" class="table">
    <tr>
      <td><h3>Отопление</h3></td>
      <td><h3>Интерьер и декор</h3></td>
      <td><h3>Освещение</h3></td>
      </tr><tr>
      <td><img src="ото.jpg" class="imoge"></td>
      <td><img src="интер.jpg" class="imoge"></td>
      <td><img src="люст.jpg" class="imoge"></td>
    </tr>
  </table>

  <table align="center" class="table">
    <tr>
      <td><h3>Напольное покрытие</h3>
      <td><h3>Двери</h3></td>
      <td><h3>Керамическая плитка</h3></td>
      </tr><tr>
      <td><img src="пол.jpg" class="imoge"></td>
      <td><img src="дверь.jpg" class="imoge"></td>
      <td><img src="плита.jpg" class="imoge"></td>
    </tr>
  </table>
</div>-->

<div class="novoe" id="novoe">
  <div class="zin1">
    <h1>Магазин "Хозтовары"</h1>
    <hr>
    <p>
    <img src="хоз1.jpg" alt="" class="drive">
    <img src="хоз2.jpg" class="drive">
    <img src="хоз3.jpg" class="drive">
  </p>
  </div>
  <div class="zin2">
    <h1>Магазин "Обои, Сантехника, Напольное покрытия"</h1>
    <hr>
    <img src="обо1.jpg" class="drive">
    <img src="обо2.jpg" class="drive">
    <img src="обои3.jpg" class="drive">
  </div>
  <div class="zin3">
    <h1>Магазин-Склад "Строительные товары"</h1>
    <hr>
    <img src="склад1.jpg" class="drive">
    <img src="склад5.jpg" class="drive">
    <img src="склад3.jpg" class="drive">
  </div>
</div>

<div class="forma" >
  <div class="format">
    <form method="post">
		<span class="last_name">Фамилия</span><br>
		<input type="text" name="last_name"><br>
		<span class="name">Имя</span><br>
		<input type="text" name="name"><br>
		<span class="first_name">Отчество</span><br>
		<input type="text" name="first_name"><br>
		<span class="">Телефон</span><br>
		<input type="phon" name="firstName">
  </form>
  </div>
  </div>

<div class="end" id="end">
  <h1 align="center">Контакты</h1>
  <table align="center">
    <tr>
      <td><h2>Магазин "Хозтовары"</h2></td>
      <td><h2>Магазин «Обои, Сантехника, Напольные покрытия»</h2></td>
      <td><h2>Магазин-Склад «Строительные товары»</h2></td>
    </tr>
    <tr>
      <td><p>ул. 50 Лет ВЛКСМ-4 <br>(42355) 25-1-11 <br>8-968-167-57-74 <br>Lena-Avesta@yandex.ru</p></td>
      <td><p>ул. Петрова-32<br>(42355) 26-0-77<br>8-966-287-88-08<br>yulia@avestadv.ru</p></td>
      <td><p>ул. Станционная-21<br>(42355) 25-8-51<br>8-968-167-57-51<br>avestadva@gmail.com</p></td>
    </tr>
  </table>
  <div style="height:30px"></div>
   
   <div id="topNubex"><img src="Frame 1.svg" width="60px" height="60px" /></div>
</div>

<div class="nnn"><p>&copy;Avesta 1997-2022</p></div>
</body>
</html>