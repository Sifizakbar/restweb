# Ex.07 Restaurant Website
## Date:04.10.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
rest.html
<html>
<head>
  <title>FOODIE RESTAURANT</title>
  <link rel="stylesheet" href="home.css">
  
</head>
<body>
  <header>
    <div class="logo">FOODIE RESTAURANT</div>
    <nav>
      <a href="#">Home</a>
      <a href="#" onclick="menu.html">Menu</a>
      <a href="#">Admin</a>
      <a href="#">Contact</a>
    </nav>
  </header>
  <div class="image-wrapper">
    <img 
      src="restbg.jpg"
      class="restaurant-image" 
    />
  </div>
  <footer>© Sifiz A (25010152)</footer>
</body>
</html>

home.css

    body {
      margin: 0;
      height: 100%;
      background: url('restbg.jpg') no-repeat center center fixed;
      background-size: cover;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .contact-box {
      background-color: skyblue;
      padding: 20px 30px;
      border-radius: 4px;
      text-align: center;
      max-width: 320px;
      
    }
    .contact-box h1 {
      margin-bottom: 1rem;
      color: blue;
      font-weight: 700;
    
    }
    .contact-box p {
      margin: 0.3rem 0;
      color: blue; 
      font-size: 1rem;
    }
    footer {
      position: fixed;
      bottom: 8px;
      font-size: 15px;
      color:blue;
      width: 100%;
      text-align: center;
    }


menu.html

<html>
<head>

<title>Menu</title>
<link rel="stylesheet" href="menu.css">

</head>
<body>

<header>
  <h1>Our Menu</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#">Menu</a>
    <a href="#">Administration</a>
    <a href="#">Contact Us</a>
  </nav>
</header>

<div class="container">
  <h2 class="title">Food Items</h2>
  <div class="food-grid">
    <div class="food-card">
      <img src="chapathi.jpg" alt="Chapathi" />
      <p>Chapathi - $30</p>
    </div>
    <div class="food-card">
      <img src="idly.jpg" alt="Idli" />
      <p>Idli - $8</p>
    </div>
    <div class="food-card">
      <img src="parotta.jpg" alt="Parotta" />
      <p>Parotta - $12</p>
    </div>
    <div class="food-card">
      <img src="dosa.jpg" alt="Dosa" />
      <p>Dosa - $55</p>
    </div>
    <div class="food-card">
      <img src="chic65.jpg" alt="Chicken 65" />
      <p>Chicken 65 - $65</p>
    </div>
    <div class="food-card">
      <img src="biriyani.jpg" alt="chicken Biriyani" />
      <p>Chicken biriyani - $115</p>
    </div>

  </div>
</div>

<footer>© Sifiz A (25010152)</footer>

</body>
</html>

menu.css
header {
    background-color: blue;
    padding: 15px 0;
    text-align: center;
    
  }

  header h1 {
    color: white;
    font-weight: 1000;
    margin-bottom: 10px;
  }

  nav a {
    color: white;
    font-size: 14px;
    text-decoration: none;
    margin: 0 10px;
    font-weight: 500;
    transition: color 0.3s ease;
  }

  nav a:hover {
    color: yellow;
  }

  .container {
    max-width: 1000px;
    margin:20px 60px;
  }

  .title {
    text-align: center;
   
    font-weight: 700;
    font-size: 25px;
    color: blue;
  }

  .food-grid {
    display: flex;
    gap: 30px;
    justify-items: center;
  }

  .food-card {
    background-color:lightblue;
    border-radius: 10px;
    overflow: hidden;
    width: 230px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.4);
    transition: transform 0.3s ease;
  }

  .food-card:hover {
    transform: scale(1.05);
  }

  .food-card img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    display: block;
    border-bottom: 2px solid skyblue;
  }

  .food-card p {
    color: blue;
    text-align: center;
    padding: 10px 0;
    font-size: 14px;
  }

  footer {
      text-align: center;
      color: blue;
      font-size: 15px;
     
    }
  
home.html


<html>
<head>

<title>Admin</title>
<link rel="stylesheet" href="admin.css">

</head>
<body>

<header>
  <h1>Administration Team</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#">Menu</a>
    <a href="#">Administration</a>
    <a href="#">Contact Us</a>
  </nav>
</header>

<div class="container">
  <h2 class="title">Meet Our Team</h2>
  <div class="team-grid">
    <div class="team-card">
      <img src="sifizphoto.jpg" alt="Sifiz" />
      <p>Sifiz</p>
      <p>CEO</p>
    </div>
    <div class="team-card">
      <img src="akilesh.jpg" alt="Akilesh" />
      <p>Akilesh</p>
      <p>Marketing Manager</p>
    </div>
    <div class="team-card">
      <img src="arris.jpg" alt="Arris" />
      <p>Arris</p>
      <p>Operations Manager</p>
    </div>
    <div class="team-card">
      <img src="akshai.jpg" alt="Akshai" />
      <p>Akshai</p>
      <p>HR Manager</p>
    </div>
    <div class="team-card">
      <img src="yogesh.jpg" alt="Yogesh" />
      <p>Yogesh</p>
      <p>Executive Chef</p>
    </div>
    <div class="team-card">
      <img src="praniel.jpg" alt="Praniel" />
      <p>Customer Service Manager</p>
      <p>Praniel</p>
    </div>
    

  </div>
</div>

<footer>© Sifiz A (25010152)</footer>

</body>
</html>

admin.css

header {
    background-color: blue;
    padding: 15px 0;
    text-align: center;
    
  }

  header h1 {
    color: white;
    font-weight: 1000;
    margin-bottom: 10px;
    margin-left: 10px;
  }

  nav a {
    color: white;
    font-size: 14px;
    text-decoration: none;
    margin: 0 10px;
    font-weight: 500;
    transition: color 0.3s ease;
  }

  nav a:hover {
    color: yellow;
  }

  .container {
    max-width: 1000px;
    margin:20px 60px;
  }

  .title {
    text-align: center;
    margin-left: 150px;
    font-weight: 700;
    font-size: 25px;
    color: blue;
  }

  .team-grid {
    display: flex;
    gap: 30px;
    justify-items: center;
    align-items: space around;
  }

  .team-card {
    background-color:lightblue;
    border-radius: 10px;
    overflow: visible;
    width: 230px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.4);
    transition: transform 0.3s ease;
  }

  .team-card:hover {
    transform: scale(1.05);
  }

  .team-card img {
    width: 170;
    height: 300px;
    object-fit: cover;
    display: block;
    border-bottom: 2px solid skyblue;
  }

  .team-card p {
    color: blue;
    text-align: center;
    padding: 10px 0;
    font-size: 14px;
  }

  footer {
      text-align: center;
      color: blue;
      font-size: 15px;
     
    }
  
contact.html

<html lang="en">
<head>
  
  <title>Contact</title>
  <link rel="stylesheet" href="contact.css"
  
</head>
<body>
  <div class="contact-box">
    <h1 class="contact-title">Contact Us</h1>
    <p>Visit us at:</p>
    <p>10 Gandhiji Street, Cumbum, India</p>
    <p>Phone: 1234567890</p>
    <p>Email: sibirose19@gmail.com</p>
  </div>
  <footer>© Sifiz A(25010152)</footer>
</body>
</html>

contact.css


    body {
      margin: 0;
      height: 100%;
      background: url('restbg.jpg') no-repeat center center fixed;
      background-size: cover;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .contact-box {
      background-color: skyblue;
      padding: 20px 30px;
      border-radius: 4px;
      text-align: center;
      max-width: 320px;
      
    }
    .contact-box h1 {
      margin-bottom: 1rem;
      color: blue;
      font-weight: 700;
    
    }
    .contact-box p {
      margin: 0.3rem 0;
      color: blue; 
      font-size: 1rem;
    }
    footer {
      position: fixed;
      bottom: 8px;
      font-size: 15px;
      color:blue;
      width: 100%;
      text-align: center;
    }


```

## OUTPUT:
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (17).png>)

![alt text](<Screenshot (18).png>)

![alt text](<Screenshot (19).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
