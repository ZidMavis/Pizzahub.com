 <!DOCTYPE html>
<html>
<head>
  <title>Pizzahub</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
	
	html {
		background-image: url('bgc.jpg');
		background-repeat: no-repeat;
		background-attachment: fixed;
		background-size: 100% 110%;
	}

    body {
      margin: 0;
      font-family: 'Roboto', sans-serif
      
    }

    .header {
      background-color: #212121;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 10px;
      position: sticky;
      top: 0;
    }

    .logo a {
      text-decoration: none;
      color: white;
      font-size: 30px;
      font-weight: 700;
    }
	
	.logo2 {
	  background-color: #fb9800;
	  color: black;
	  padding-left: 5px;
	  padding-right: 5px;
	border-radius: 5px;
	}

    ul {
      display: flex;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    ul li a {
      text-decoration: none;
      color: #fff;
      font-size: 18px;
      font-weight: 500;
      padding: 8px 15px;
      border-radius: 5px;
    }

    ul li a:hover {
      background-color: #fb9800;
      color: black;
      border: 1px solid white;
	  border-radius: 5px;
	  padding: 8px 14px;
    }

    .content {
      background-color: #212121;
      color: white;
      padding: 10px;
    }

    input {
      width: 100%;
    }

    .menu {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
    }

    .left {
      color: white;
      font-size: 25px;
      padding: 5px;
      text-shadow: 0px 0px 5px black;
    }

    .roll {
      height: auto;
      width: 200px;
      animation: anim 5s infinite linear;
      position: relative;
    }

    .right {
      margin-top: 40px;
      margin-right: 20px;
    }

    .sign {
      background-color: #212121;
      color: white;
      font-size: 30px;
      font-weight: 700;
      text-align: center;
      padding: 10px;
	  opacity: 0.8;
    }

    .menus {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .list {
      background-color: #f3e5f5;
      color: #212121;
      width: 200px;
      height: flex;
      margin: 20px;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      border: 3px groove #e0e0e0;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .list img {
      height: auto;
      width: 100px;
      margin: 0 auto;
    }

    .list button {
      background-color: #212121;
      color: white;
      border: none;
      padding: 8px 16px;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    .list button:hover {
      background-color: #fb9800;
	  color: black;
    }

	@keyframes anim {
	from {
		tranform: rotate(0deg);
		}
	to {
		transform: rotate(360deg);
		}
	}

  </style>
</head>
<body>
  <div class="all">
    <div class="header">
      <div class="logo"><a href="">Pizza<b class="logo2">hub</b></a></div>
      <ul>
        <li><a href="PH.htm">HOME</a></li>
        <li><a href="About us.html">ABOUT US</a></li>
        <li><a href="Contact.html">CONTACT US</a></li>
        <li><a href="#">INTERACT</a></li>
      </ul>
    </div>

    <div class="content">
      <input type="text" placeholder="Search" name="search">
    </div>

    <div class="menu">
      <div class="left">
        <h1>Sliced or Whole, Take it all!</h1>
        <h3>The best food is eaten with your hands.</h3>
      </div>
      <div class="right">
        <img height="400px" width="400px" src="pizza1.png" class="roll">
      </div>
    </div>
  </div>

  <!-- pizza menu -->
  <div class="sign">PIZZAS</div>
  <div class="menus">
    <div class="list">
      <img height="auto" width="100px" src="pizza1.png">
      <h4>Bacon<br>$10</h4>
	  <p>Bacon is a meat that is very salty and is also very crispy. It helps give the pizza an extra salty flavor, which is also a good thing. Additionally, bacon is also a meat that is really easy to eat, even through the pieces are quite small. Meatballs are a slightly different kind of pizza topping.</p>
      <button type="button">Order</button>
    </div>
    <div class="list">
      <img height="auto" width="100px" src="pizza2.png">
      <h4>Chilli<br>$25</h4>
	  <p>A spicy pizza usually consisting of chili pepper, vinegar, salt, sugar, and spices and used especially as a condiment and in cooking. Also : a milder, sweeter sauce containing similar ingredients but made primarily with tomato pure. </p>
      <button type="button">Order</button>
    </div>
    <div class="list">
      <img height="auto" width="100px" src="pizza3.png">
      <h4>Veggie<br>$20</h4>
	  <p>Vegetarian pizza, a baked meatless Italian pie, is an option for vegetarians, those who may have a special needs diet, or simply for those looking for a healthier alternative to regular pizza.</p>
      <button type="button">Order</button>
    </div>
    <div class="list">
      <img height="auto" width="100px" src="pizza4.png">
      <h4>Hawaiian<br>$10</h4>
	  <p>Hawaiian pizza is a pizza originating in canada, and is traditionally topped with pineapple, tomato sauce, chese, and either ham or bacon.</p>
      <button type="button">Order</button>
    </div>
    <div class="list">
      <img height="auto" width="100px" src="pizza5.png">
      <h4>Classic<br>$15</h4>
	  <p>It is made using the most traditional techniques which is by kneading the fresh dough until it reaches the optimal level of softness. Then, this dough is stretched carefully. The classic hand-tossed pizza is chosen owing to the texture of the crust.</p>
      <button type="button">Order</button>
    </div>

	<div class="list">
      <img height="auto" width="100px" src="pizza5.png">
      <h4>Buffalo<br>$15</h4>
	  <p>It is not like a traditional pizza, but it is so much better! The flavor is like a big bowl of hot wings, piled onto a pizza crust topped with melty cheese and flavorful ranch and blue cheese.</p>
      <button type="button">Order</button>
    </div>

	<div class="list">
      <img height="auto" width="100px" src="pizza5.png">
      <h4>Diavola<br>$15</h4>
	  <p>Is a variety of Italian pizza that is traditionally topped with tomato sauce, mozzarella cheese, spicy salami, and hot chilli peppers, black olives are optional and can be added for extra flavor.</p>
      <button type="button">Order</button>
    </div>

	<div class="list">
      <img height="auto" width="100px" src="pizza5.png">
      <h4>Salmon<br>$15</h4>
	  <p>Made with store bought pizza crust, flat bread or naan, topped with cream cheese, smoked salmon, onion, and capers.</p>
      <button type="button">Order</button>
    </div>


  </div>

  <!-- drinks menu -->
  <div class="sign">DRINKS</div>
  <div class="menus">
    <div class="list">
      <img height="auto" width="100px" src="D1.jpeg">
      <h4>Coffee<br>$10</h4>
	  <p>Iced coffee tea is the perfect combination of coffee and tea in a cool glass of ice. Get this simple, yet delicious iced tea coffee recipe.</p>
      <button type="button">Order</button>
    </div>
    <div class="list">
      <img height="auto" width="100px" src="D2.jpeg">
      <h4>Strawberry<br>$25</h4>
	  <p>Strawberry tea is a red, sweet, fruity, and freshly brewed tea flavored with fresh summer strawberries.</p>
      <button type="button">Order</button>
    </div>
   
    <div class="list">
      <img height="auto" width="100px" src="D4.jpeg">
      <h4>Grapes<br>$10</h4>
	  <p>This elegantly flavored grape tea fills the mouth with the sweet and savory aroma of the famous Japanese "Kyoho" grape. Its refreshing taste make it ideal for iced tea. </p>
      <button type="button">Order</button>
    </div>
    <div class="list">
      <img height="auto" width="100px" src="D5.jpeg">
      <h4>Apple<br>$15</h4>
	  <p>Apple iced tea combines brewed black tea with a splash of naturally sweet apple juice and tart apple slices</p>
      <button type="button">Order</button>
    </div>

	 <div class="list">
      <img height="auto" width="100px" src="Red1.jpg">
      <h4>Georgia<br>$30</h4>
	  <p>Wines from the Saperavi grape are also known as the pride of georgia. The dark red Saperavi wines have a robust, somewhat heavy but balanced.</p>
      <button type="button">Order</button>
    </div>

	 <div class="list">
      <img height="auto" width="100px" src="Red2.png">
      <h4>France<br>$25</h4>
	  <p>Most french red wine is discribed as being rich, complex, tannic, and powerful, although this varies and depends on the regions, the blends etc... the main aromas of french red wine include things like cherry core, blueberry and even some ripe plums.</p>
      <button type="button">Order</button>
    </div>

	 <div class="list">
      <img height="auto" width="100px" src="White1.png">
      <h4>Lux Chardonnay<br>$15</h4>
	  <p>Highlighted by hints of green apple, tropical fruit and passion fruit. This bright Chardonnay delivers lively natural acid, gentle warmth and a smooth, buttery finish.</p>
      <button type="button">Order</button>
    </div>

	 <div class="list">
      <img height="auto" width="100px" src="White2.png">
      <h4>Pinot Gris<br>$17</h4>
	  <p>The typical pinot gris is full-bodied with a fresh, spicy flavor and notes of tropical fruit, stone fruit, or citrus.</p>
      <button type="button" onclick="Thank you! your order has been added to the cart.">Order</button>
    </div>

  </div>
</body>
</html>
