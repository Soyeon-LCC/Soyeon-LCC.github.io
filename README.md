<!DOCTYPE html>
<html>
  <head>
    <title> Personal Website</title>
    <link rel="stylesheet" href="style.css" />
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700;800;900&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
	<style>
		body {
	  background-color: #939599;
	  font-family: 'Raleway', sans-serif;
	  font-weight: 400;
	}
	#about {
		background-color: white;
	}
	.city-picture {
	  width: 500px;
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
	  background-color: #efc1de;
	}

	nav li a:hover {
	  background-color: #efc1de;
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
	.three-column {
	  display: grid;
	  grid-template-columns: 33% 33% 33%;
	  padding: 40px;
	  background-color: white;
	}

	.three-column div {
	  background-color: #fff;
	  margin-righ: 10px;
	  margin-left: 10px;
	}
	</style>
  </head>
  <body>
    <div id="container">
      <header>
        <h2>Title of the website</h2>
        <nav>
			<ul>
			  <li><a class="active" href="index.html">Home</a></li>
			  <li><a href="about.html">About</a></li>
			  <li><a href="projects.html">Projects</a></li>
			  <li><a href="contacts.html">Contacts</a></li>
			</ul>
        </nav>
      </header>
      <main>
        <div class="two-column">
          <div>
            <h1>Hi, I'm Soyeon</h1>
            <p>
              Paragraph text goes here
            </p>
      </div>
          <div>
              <img class="city-picture" src="city.jpg" alt="City view at night" />
          </div>
      </div>
      <div class="three-column">
        <div>
          <p> Column 1 </p>
        </div>
        <div>
          <p> Column 2 </p>
        </div>
        <div>
          <p> Column 3 </p>
        </div>
      </div>

      </main>
      <footer>
        <p>
          Footer text
        </p>
      </footer>
    </div>
  </body>
</html>
