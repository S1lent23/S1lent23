<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Торнадо</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
   <header class="container row">
		<a href="index.html"><img src="./img/logo.svg" alt=""></a>
    <div class="toggleMenu" onclick="toggleMenu();"></div>
    <nav>
			<li><a href="index.html">Главная</a></li>
			<li><a href="#">Услуги</a></li>
			<li><a href="#">Прайс</a></li>
      <li><a href="#">Отзывы</a></li>
      <li><a href="#">Контакты</a></li>
      <li><a href="#">Войти</a></li>
      <li><a href="#" id="open_pop_up">Регистрация</a></li>   
		</nav>
	</header>
<div class="pop_up" id="pop_up">
        <div class="pop_up_cont">
            <div class="pop_up_body" id="pop_up_body">
                <p>Регистрация</p>
                <form action="">
                    <input type="email" placeholder="Email">
                    <input type="password"  placeholder="Пароль">
                    <input type="password"  placeholder="Повторите пароль">
                    <button>Зарегистрироваться</button>
                </form>
                <div class="pop_up_close" id="pop_up_close">&#x2715;</div>
            </div>
        </div>
    </div>

	<section class="hero_tornado">
		<div class="background-image" style="background-image: url(./img/IMAGE.png);"></div>
		<h1>Акции на абонименты</h1>
	</section>
            
  <section class="section_card_tornado">
    <h2>Наши услуги</h2>
     <div class="section">
      <div class="cards">
        <div class="card">
          <div class="image_section">
            <img src="img/Rectangle.png" alt="">
          </div>
          <div class="tren">
            <h1>Тренажерный зал</h1>
          </div>
        </div>

        <div class="card">
          <div class="image_section">
            <img src="img/Rectangle (1).png" alt="">
          </div>
          <div class="tren">
            <h1>Кардиозона</h1>
          </div>
        </div>
        <div class="card">
          <div class="image_section">
            <img src="img/Rectangle (2).png" alt="">
          </div>
          <div class="tren">
            <h1>Фитнес зал</h1>
          </div>
        </div>

        <div class="section">
          <div class="cards">
            <div class="card">
              <div class="image_section">
                <img src="img/Rectangle (3).png" alt="">
              </div>
              <div class="tren">
                <h1>Групповые занятия</h1>
              </div>
            </div>
        
            <div class="card">
              <div class="image_section">
                <img src="img/Rectangle (4).png" alt="">
              </div>
              <div class="tren">
                <h1>Индивидуальные занятия</h1>
              </div>
            </div>
            <div class="card">
              <div class="image_section">
                <img src="img/Rectangle (5).png" alt="">
              </div>
              <div class="tren">
                <h1>Кроссфит</h1>
              </div>
            </div> 
          </div>
        </div>
      </div>
    </div>
</section>

            <section class="price_tornado">
              <div class="tren_price">
                <h2>Прайс</h2>
              </div> 
            </section>

            <div class="cards">
              <div class="card shadow">
                <ul>
                  <li class="pack">Знакомство с клубом</li>
                  <li class="bottom-bar">Первое разовое посещение -100 р.</li>
                  <li class="bottom-bar">Разовое посещение - 250р.</li>
                  <li class="bottom-bar">Абонемент:<br>1 месяц ( c 09.00-13.00) - 3000р.</li>
                  <li><button class="btn">ЗАПИСАТЬСЯ</button></li>
                </ul>
              </div>
              <div class="card active">
                <ul>
                  <li class="pack">Индивидуальное занятие с тренером</li>
                  <li class="bottom-bar">Первое разовое посещение -200 р.</li>
                  <li class="bottom-bar">Разовое посещение - 250р.</li>
                  <li class="bottom-bar">Абонемент<br>1 месяц ( c 09.00-13.00) - от 800р.</li>
                  <li><button class="btn active-btn">ЗАПИСАТЬСЯ</button></li>
                </ul>
              </div>
              <div class="card shadow">
                <ul>
                  <li class="pack">Безлимит</li>
                  <li class="bottom-bar">1 месяц - 3500 руб</li>
                  <li class="bottom-bar">3 месяца - 5000 руб</li>
                  <li class="bottom-bar">6 месяцев - 7000 руб</li>
                  <li><button class="btn">ЗАПИСАТЬСЯ</button></li>
                </ul>
              </div>


              

              <section>
                <div class="title_otz">
                  <h2>Отзывы</h2>
                </div>

                <div class="slideshow-container">

                  <!-- Полноразмерные изображения с числом и текстом подписи -->
                  <div class="mySlides fade">
                    <img src="img/image 20.png" style="width:100%">
                  </div>
                
                  <div class="mySlides fade">
                    <img src="img/image 21.png" style="width:100%">
                  </div>
                
                  <div class="mySlides fade">
                    <img src="img/image 22.png" style="width:100%">
                  </div>
                
                  <!-- Вперед и назад кнопки -->
                  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
                  <a class="next" onclick="plusSlides(1)">&#10095;</a>
                </div>
                <br>
                
                <!-- Точки/круги -->
                <div style="text-align:center">
                  <span class="dot" onclick="currentSlide(1)"></span>
                  <span class="dot" onclick="currentSlide(2)"></span>
                  <span class="dot" onclick="currentSlide(3)"></span>
                </div>
              </section>




              <section class="title_contact">
                <div class="section_card">
            <h2>Контакты</h2>
           </div>
            </section>
               <div class="cards">
          <a> <h3>Телефон: 8 (800) 111-20-20</h3></a>
         </div>
        
<footer class="footer-distributed">
        <div class="footer-left">

            <p class="footer-links">
                <a class="link-1" href="#">Услуги</a>

                <a href="#">Прайс</a>

                <a href="#">Отзывы</a>
                <a href="#">Контакты</a>
            </p>

            <p>Фитнес клуб Торнадо &copy; 2022</p>
        </div>

    </footer>
         </section>    
    














      <script src="js/main.js"></script>
</body>
</html>
