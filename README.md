

<html> 
    <head> 
        <title> Celine </title>
        <link rel="stylesheet" href="style.css"> 
    </head>
    <body> 
        <header>
            <img src="https://elle.com.kz/wp-content/uploads/2023/03/celine-logo.png" class="logo">
            <nav> 
                <a href=""> Головна </a>
                <a href=""> Про нас </a>
                 <a href=""> Відгуки </a>
                <a href=""> Каталог</a>
                <a href=""> Де нас знайти ?</a>
            </nav>
        </header>
        <main>
            <h2>Про нас</h2> 
            <p class="pro">Ласкаво просимо до нашого магазину одягу!<br>
                 Ми створені для тих, хто цінує стиль, якість та комфорт.<br> Наш асортимент включає найактуальніші моделі, які допоможуть вам виразити свою індивідуальність та завжди виглядати на висоті.<br>
Ми працюємо тільки з перевіреними постачальниками, щоб запропонувати вам одяг, який відповідає останнім тенденціям моди та високим стандартам якості.<br> Незалежно від того, чи шукаєте ви елегантний образ для особливого випадку, чи зручний одяг для повсякденного життя — у нас є все, що вам потрібно.<br>
Наша команда завжди готова допомогти вам з вибором та відповісти на всі ваші питання.<br> Ми віримо, що кожен заслуговує відчувати себе впевнено та комфортно у своєму одязі, тому постійно вдосконалюємо наші колекції, враховуючи ваші побажання та відгуки.<br>
Дякуємо, що обрали нас! Ми цінуємо вашу довіру і завжди прагнемо зробити ваш шопінг приємним та легким.</p>
<section class="catalog">
<div class="sviter"> 
    <img src="https://twicpics.celine.com/product-prd/images/large/2AD3X384D.38NO_1_FW23_P2_M.jpg?twic=v1/cover=1:1/resize-max=480">
    <h3>Свитер CELINE <br>
    Ціна 1200 UAH</h3>
    <p>Стильна кофта Celine — ідеальне<br> поєднання елегантності<br> та комфорту. Виконана з м'якої,тканини </p>
</div>
<div class="sviter"> 
    <img src="https://forage-clothing.com/cdn/shop/files/T-Shirt_Basic_black_679faf76-6669-4370-8a8f-9df3971081fd_1100x.jpg?v=1711875384">
    <h3>Футболка CELINE <br>
    Ціна 500 UAH</h3>
    <p>Футболка Celine — це класика, яка ніколи не виходить з моди. </p>
</div>
<div class="sviter"> 
    <img src="https://img4.dhresource.com/webp/m/0x0/f3/albu/km/y/06/cd471899-d4d8-4956-9b59-bbef0162aca4.jpg">
    <h3>Шорти CELINE <br>
    Ціна 500 UAH</h3>
    <p>Шорти  — ідеальний вибір для активного відпочинку та повсякденних прогулянок. </p>
</div>
</section>
      <h2>Відгуки</h2>
  <h3>Андрій Л.:</h3>
  <p> Замовив тут теплу кофту для осінніх прогулянок, і це було відмінне рішення!<br> Кофта дуже зручна, добре зігріває, а якість матеріалу перевершила всі мої очікування.<br> Навіть після кількох прань вона зберігає форму та колір.<br> Швидка доставка та ввічливе обслуговування зробили покупку ще приємнішою. </p>
  <h3>Іван М.: </h3>
  <p> Дуже задоволений покупкою у цьому магазині!<br>  Купив тут кілька футболок і сорочок, і всі вони сидять чудово.<br>  Тканина приємна на дотик, а кольори залишаються яскравими навіть після кількох прань. <br> Обслуговування на високому рівні, допомогли обрати потрібний розмір. </p>
<div class="adr">
<h2> Де нас знайти ? </h2>
<!-- Тут має бути інша картинка, мій скрін -->
<h3>Адреса</h3>
<p>Місто Чернівці<br>вул.Емінеску, 1</p>
</div>
        </main>
        <footer> 

        </footer>
    </body>
</html>  



body {
    font-family: sans-serif;
    margin: 0;
    background-color: rgb(0, 0, 0);
    color: white;
}
.logo { 
    width: 200px;
    height: 100px;
}
a {
    text-decoration: none;
}
header { 
    display: flex;
    align-items: center;
    background-color: rgb(130, 131, 131);
    padding: 20px;
}
nav {
    display: flex;
    justify-content: space-around;
    width: 850px;
}
nav a { 
    font-size: 22px;
    color: black;
    font-weight: 600;
}
 
nav a:hover{
    transform: scale(1.2) translateY(-4px);
    text-shadow: 0px 0px 15px white, 0px 0px 5px white;
}
.pro { 
 font-size: 20px;
 font-weight: 550;
}

img {
    width:250px;
    height: 250px;
}
 p { 
    font-weight: 550;
    font-size: 20px;
}
.sviter { 
    width: 350px;
    background-color:rgba(0, 9, 61, 0.705) ;
    text-align: center;
    padding: 15px;
    border-radius: 10px;
    margin-top: 15px;
    margin-bottom: 15px;
}

h2 { 
    text-align: center;
}
.adr { 
    text-align: center;
}

.catalog { 
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
}

 
