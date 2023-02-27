<DOCTYPE! html>
<html>
  <head>
    <title> Personal Website</title>
    <link rel="stylesheet" href="style.css" />
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700;800;900&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
	<script src="https://kit.fontawesome.com/e41ac81a35.js" crossorigin="anonymous"></script>
	<style>
		body {
	  background-color: #939599;
	  font-family: 'Raleway', sans-serif;
	  font-weight: 450;
	}
	#about {
		background-color: white;
	}

	header {
	  background-color: #efc1de;
	}
	header h2 {
		font-family: 'Cinzel', serif;
		font-weight: 700;
	  color: #fff;
	  margin: 0;
	  padding: 40px;
	}
	nav ul {
	  list-style-type: none;
	  margin: 0;
	  padding: 0;
	  overflow: hidden;
	}

	nav li {
	  float: left;
	}

	nav li a {
	  display: block;
	  color: white;
	  text-align: center;
	  padding: 14px 36px;
	  text-decoration: none;
	}
	.active {
	  background-color: #dba3c6;
	}

	nav li a:hover {
	  background-color: #dba3c6;
	}
	footer {
	  background-color: #efc1de;
	  padding: 40px;
	}
	footer p {
	  color: #fff;
	  margin: 0;
	}

	#container {
	  width: 1100px;
	  margin: 0 auto;
	}
	.two-column {
	  display: grid;
	  grid-template-columns: 50% 50%;
	  padding: 40px;
	  background-color: #ffffff;
	  font-size: 100px;
	  color : #48486a;
	  display: flex;
	  flex-direction: column;
	  
	
	}
	.two-column div {
	  margin-right: 10px;
	  margin-left: 10px;
	  background-color: white;
	}
	#projects .two-column {
		background-color: red;
		padding: 10px 40px 10px 40px;
	}
	.whatsapp {
 width: 50px;
 border-radius: 50%;
 margin-top: 20px;
 margin-left: 20px;
}
.facebook {
 width: 50px;
 border-radius: 50%;
 margin-top: 20px;
 margin-left: 20px;
}
.gmail {
width: 50px;
border-radius: 50%;
margin-top: 20px;
margin-left: 20px;
}
.instagram {
width: 50px;
border-radius: 50%;
margin-top: 20px;
margin-left: 20px;
}


	
	</style>
  </head>
  <body>
    <div id="container">
      <header>
        <h2 style=font-size:40px;>Soyeon's Travel</h2>
        <nav>
			<ul>
			  <li><a class="active" href="index.html">Home</a></li>
			  <li><a href="about.html">About</a></li>
			  <li><a href="travel.html">Travel</a></li>
			  <li><a href="contacts.html">Contacts</a></li>
			</ul>
        </nav>
      </header>
      <main>
	  
        <div class="two-column">
			<div>
			<i class="fa-solid fa-plane" style= margin-left:100px;></i>
			</div>
			<div>
			<i class="fa-solid fa-earth-americas"></i>
			<i class="fa-solid fa-suitcase" style=margin:50px 0px 0px 80px; ></i>
			</div>
          <div>
            <p style=font-size:30px;>
             Life is a travel!
            </p>
			<p style=font-size:20px;>
             Go to a travel destination that Soyeon recommends.
            </p>
			<p style=font-size:20px;>
             Travel destinations will continue to be updated.
            </p>
          </div>
		   

     

      </main>
      <footer>
        <p style=font-weight:700;>
          Contacts
        </p>
		<div>
		<img class="whatsapp" src="https://1000logos.net/wp-content/uploads/2021/04/WhatsApp-logo-768x432.png" alt="whatsapp">
		<strong style=color:#5b5e64;> +370 6612-9828 </strong>
		<img class="gmail" src="https://1000logos.net/wp-content/uploads/2021/05/Gmail-logo-768x432.png" alt="gmail">
		<strong style=color:#5b5e64;> soh22@students.lcc.lt </strong>
		</div>
		<div>
		<img class="facebook" src="https://1000logos.net/wp-content/uploads/2021/04/Facebook-logo-768x480.png" alt="facebook">
		<strong style=color:#5b5e64;> so980501@naver.com </strong>
		<img class="Instagram" src="https://1000logos.net/wp-content/uploads/2017/02/Instagram-Logo-768x432.png" alt="instagram">
		<strong style=color:#5b5e64;> @little_kite_0501 </strong>
		</div>
		</div>
      </footer>
    </div>
  </body>
</html>
