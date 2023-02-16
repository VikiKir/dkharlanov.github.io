<html lang="en"><head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Сайт-Шаблон</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
<style>
#myBtn {
    display: none; /* Hidden by default */
    position: fixed; /* Fixed/sticky position */
    bottom: 20px; /* Place the button at the bottom of the page */
    right: 30px; /* Place the button 30px from the right */
    z-index: 99; /* Make sure it does not overlap */
    border: none; /* Remove borders */
    outline: none; /* Remove outline */
    background-color: gray; /* Set a background color */
    color: white; /* Text color */
    cursor: pointer; /* Add a mouse pointer on hover */
    padding: 15px; /* Some padding */
    border-radius: 10px; /* Rounded corners */
    font-size: 18px; /* Increase font size */
}

#myBtn:hover {
    background-color: #555; /* Add a dark-grey background on hover */
}

table {
 background: white; /* цвет фона */
 border: 1px black solid; /* стиль внешней рамки */
}
td {
 border: 1px black solid; /* стиль рамки ячеек */
 padding: 0.2em; 
 text-align: center;
}
th {
 background: #ffaaaa;
 border: 1px black solid; /* стиль рамки заголовков */
 padding: 0.2em; 
 width: 20%;
 text-align: center;
</style>
<script>
// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
    if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
        document.getElementById("myBtn").style.display = "block";
    } else {
        document.getElementById("myBtn").style.display = "none";
    }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
    document.body.scrollTop = 0; // For Safari
    document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
}
  </script>



  </head>
  <body>
    <nav class="navbar navbar-expand-lg bg-body-secondary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">ЭлЖур</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#center">Главная</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#table">Оценки</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Ссылки на официальные ресурсы
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="https://school10kd.eljur.ru/">Оригинальный ЭлЖур</a></li>
            <li><a class="dropdown-item" href="https://vk.com/school10kld">МАОУ СОШ №10 в ВК</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#programmer">Ссылка на разработчика</a></li>
          </ul>
        </li>
      </ul>
      
    </div>
  </div>
</nav>
<div class="container-fluid" style="margin-top: 10px;">
    <div id="center" class="jumbotron p-3 p-md-5 text-white rounded bg-dark">
        <div class="col-md-12 px-0">
          <h1 class="display-4 font-italic">Тренировочный  ЭлЖур</h1>
          <p class="lead my-3">На данном пробном сайте вы можете посмотреть оценки 11_А_У класса</p>
          <p class="lead mb-0"><a href="https://school10kd.eljur.ru/" class="text-white font-weight-bold">Оригинальный ЭлЖур</a></p>
        </div>
      </div>
    </div>
      <div class="container-fluid" style="margin-top: 10px;">
<table id="table" class="table" style="border">
  <thead>
    <tr style="background: grey;">
      <td colspan="5" align="center"><b>11_А_У</b></td>
    </tr>
    <tr>
      <th>Январь</th>
      <th><div class="col-md-12">
      <div class="col-md" style="margin-right: 10px !important;">
 <a href="#baze_html" style=" text-decoration: none;">
        <div class="page-main__links-item d-flex flex-column" style="padding: 1.5em; height: auto; line-height: 1.2em; background-color: lime; border-radius: 10px; border: 1px solid rgb(238, 238, 238); flex-direction: column !important; display: flex !important;" onmouseover="this.style.backgroundColor='#ADD5F0';" onmouseout="this.style.backgroundColor='lime';">
          <p style="margin: auto;">
 <b><span style="color: black;">
            Base_HTML</span> </b>
          </p>
        </div>
 </a>
      </div>
    </div></th>
      <th><div class="col-md-12">
      <div class="col-md" style="margin-right: 10px !important;">
 <a href="#lesson_2" style=" text-decoration: none;">
        <div class="page-main__links-item d-flex flex-column" style="padding: 1.5em; height: auto; line-height: 1.2em; background-color: lime; border-radius: 10px; border: 1px solid rgb(238, 238, 238); flex-direction: column !important; display: flex !important;" onmouseover="this.style.backgroundColor='#ADD5F0';" onmouseout="this.style.backgroundColor='lime';">
          <p style="margin: auto;">
 <b><span style="color: black;">
            Lesson_2</span> </b>
          </p>
        </div>
 </a>
      </div>
    </div></th>
      <th><div class="col-md-12">
      <div class="col-md" style="margin-right: 10px !important;">
 <a href="#lesson_3" style=" text-decoration: none;">
        <div class="page-main__links-item d-flex flex-column" style="padding: 1.5em; height: auto; line-height: 1.2em; background-color: lime; border-radius: 10px; border: 1px solid rgb(238, 238, 238); flex-direction: column !important; display: flex !important;" onmouseover="this.style.backgroundColor='#ADD5F0';" onmouseout="this.style.backgroundColor='lime';">
          <p style="margin: auto;">
 <b><span style="color: black;">
            Lesson_3</span> </b>
          </p>
        </div>
 </a>
      </div>
    </div></th>
      <th><div class="col-md-12">
      <div class="col-md" style="margin-right: 10px !important;">
 <a href="#lesson_today" style=" text-decoration: none;">
        <div class="page-main__links-item d-flex flex-column" style="padding: 1.5em; height: auto; line-height: 1.2em; background-color: lime; border-radius: 10px; border: 1px solid rgb(238, 238, 238); flex-direction: column !important; display: flex !important;" onmouseover="this.style.backgroundColor='#ADD5F0';" onmouseout="this.style.backgroundColor='lime';">
          <p style="margin: auto;">
 <b><span style="color: black;">
            Lesson_Today</span> </b>
          </p>
        </div>
 </a>
      </div>
    </div></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th><a href="C:\Users\user\Desktop\site\personal.html">Гумовска Виктория</a><img src="https://avatars.dzeninfra.ru/get-ynews/4971158/36d83e407c2c9c2254fb8d03c2455e38/800x400" alt="Письма мастера дзен"></th>
      <td>5</td>
      <td>5</td>
      <td>4</td>
      <td>2</td>
    </tr>
    <tr>
      <th>Джандаров Мухаммад</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Дробышев Артём</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Заводяная Александра</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Каравская Есения</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Коноплева Алла</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Лагутина Мария</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Медвецкий Александр</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Нелюбина Алина</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Носаченко Роман</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Табунов Тимофей</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Тимонин Артём</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Тимонина Мария</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Тручек Никита</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
        <tr>
      <th>Шкодич Кирилл</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>
  <div class="container-fluid" style="margin-top: 10px;">
    <div id="baze_html" class="jumbotron p-3 p-md-5 text-white rounded bg-dark">
        <div class="col-md-12 px-0">
          <h1 class="display-4 font-italic">Основы HTML</h1>
          <p class="lead my-3">НА данном уроке узнали об основных тегах HTML</p>
          <p class="lead mb-0"><a href="https://school10kd.eljur.ru/" class="text-white font-weight-bold">Sublime_Text</a></p>
        </div>
      </div>
    </div>
     <div class="container-fluid" style="margin-top: 10px;">
    <div id="lesson_2" class="jumbotron p-3 p-md-5 text-white rounded bg-dark">
        <div class="col-md-12 px-0">
          <h1 class="display-4 font-italic">Основы HTML</h1>
          <p class="lead my-3">НА данном уроке узнали об основных тегах HTML</p>
          <p class="lead mb-0"><a href="https://school10kd.eljur.ru/" class="text-white font-weight-bold">Sublime_Text</a></p>
        </div>
      </div>
    </div>
     <div class="container-fluid" style="margin-top: 10px;">
    <div id="lesson_3" class="jumbotron p-3 p-md-5 text-white rounded bg-dark">
        <div class="col-md-12 px-0">
          <h1 class="display-4 font-italic">Основы HTML</h1>
          <p class="lead my-3">НА данном уроке узнали об основных тегах HTML</p>
          <p class="lead mb-0"><a href="https://school10kd.eljur.ru/" class="text-white font-weight-bold">Sublime_Text</a></p>
        </div>
      </div>
    </div>
     <div class="container-fluid" style="margin-top: 10px;">
    <div id="lesson_today" class="jumbotron p-3 p-md-5 text-white rounded bg-dark">
        <div class="col-md-12 px-0">
          <h1 class="display-4 font-italic">Основы HTML</h1>
          <p class="lead my-3">НА данном уроке узнали об основных тегах HTML</p>
          <p class="lead mb-0"><a href="https://school10kd.eljur.ru/" class="text-white font-weight-bold">Sublime_Text</a></p>
        </div>
      </div>
    </div>


<footer id="programmer" class="container">
        <p>©2023 dkharlanov</p>
      </footer>
      <button onclick="topFunction()" id="myBtn" title="Go to top">В начало</button>



    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
  
</body></html>
