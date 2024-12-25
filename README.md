# Ex.07 Restaurant Website
## Date:

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
home.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TASTEBUDS POPPERS</title>
    <style>
        body {
            background-color: rgb(189, 211, 213);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color:rgb(91, 199, 226);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color:rgb(54, 73, 210);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color:rgb(96, 135, 207);
        }
        .hero {
             background-color:rgb(18, 132, 145);
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 3rem;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .menu-item {
            border: 1px solid rgb(51, 170, 103);
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color:rgb(240, 247, 115);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>TASTEBUDS POPPERS</h1>
    </header>
    <nav>
        <a href="home.html">home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="hero">
        <h1>Welcome to TASTEBUDS POPPERS</h1>
    </div>
    <section id="about">
        <h2>About Us</h2>
        <p>We are passionate about serving delicious food made with fresh ingredients. Dine in with us to experience magic popping in your tastebuds!</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Phone:9036836856</p>
        <p>Email:tastebudspoppers@gmail.com</p>
        <p>Address: 27/4 jpr road ,koramangala ,bangalore</p>
    </section>
    <footer>
        <p>&copy; SWETHA S V</p>
    </footer>
</body>
</html>

menu.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - TASTEBUDS POPPERS</title>
    <style>
        body {
            background-color: rgb(112, 175, 206);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(86, 118, 133);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(73, 152, 236);
        }
        nav a {
            color: rgb(48, 106, 121);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(69, 224, 211);
        }
        section {
            padding: 20px;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            text-align: center;
        }
        .menu-item {
            border: 1px solid rgb(5, 52, 110);
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: rgb(6, 85, 101);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Our Specials</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="dosa.jpg" alt="DOSA">
                <h3>DOSA</h3>
                <p>Crispy, golden dosas with a perfect blend of tradition and flavor, served with mouthwatering accompaniments. </p>
            </div>
            <div class="menu-item">
                <img src="noodles.jpg" alt="NOODLES">
                <h3>NOODLES</h3>
                <p> Serving delicious, handcrafted noodles with bold flavors and fresh ingredients to satisfy every craving.</p>
            </div>
            <div class="menu-item">
                <img src="chapati.jpg" alt="CHAPPATI">
                <h3>CHAPPATI</h3>
                <p>Freshly made, soft, and wholesome chapatis crafted to perfection for a truly authentic taste.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; TASTEBUDS POPPERS</p>
        <p> designed and developed by: SWETHA S V</p>
    </footer>
</body>
</html>


index.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - TASTEBUDS POPPERS</title>
    <style>
        body {
            background-color: rgb(79, 164, 210);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(116, 206, 239);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(82, 170, 187);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(73, 163, 181);
        }
        .welcome {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 50px;
        }
        .welcome h1 {
            font-size: 2.5rem;
        }
        .welcome p {
            font-size: 1.2rem;
            margin: 20px 0;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
            text-align: center;
        }
        .feature {
            margin: 10px;
            padding: 20px;
            border: 1px solid silver;
            border-radius: 5px;
            width: 300px;
        }
        footer {
            background-color: rgb(4, 114, 6);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to TASTEBUDS POPPERS</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="welcome">
        <h1>Your Destination for Exquisite Cuisine</h1>
        <p>TASTEBUDS POPPERS offers a wide range of delicious dishes made from the freshest ingredients. Experience the taste of perfection with every bite!</p>
    </div>
    <section class="features">
        <div class="feature">
            <h3>Fresh Ingredients</h3>
            <p>We use only the freshest and highest-quality ingredients to prepare our dishes.</p>
        </div>
        <div class="feature">
            <h3>Family-Friendly</h3>
            <p>Enjoy a welcoming and comfortable atmosphere perfect for family gatherings.</p>
        </div>
        <div class="feature">
            <h3>Exceptional Service</h3>
            <p>Our friendly staff is here to make your dining experience unforgettable.</p>
        </div>
    </section>
    <footer>
        <p>&copy;TASTEBUDS POPPERS. All Rights Reserved.</p>
        <p> designed and developed by: SWETHA S V</p>
    </footer>
</body>
</html>


about.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - TASTEBUDS POPPERS</title>
    <style>
        body {
            background-color: rgb(94, 178, 193);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(103, 164, 180);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(103, 177, 186);
        }
        nav a {
            color: rgb(95, 192, 227);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(105, 209, 207);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
            text-align: justify;
        }
        footer {
            background-color: rgb(115, 212, 211);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>About TASTEBUDS POPPERS</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Our Story</h2>
        <div class="content">
            <p>Welcome to TASTEBUDS POPPERS (since 2007), where we bring together a love for fresh, delicious meals and a passion for hospitality. Established with the goal of creating memorable dining experiences, Tastebuds poppers is your go-to destination for a delightful culinary journey.</p>
            <p>Our team is committed to using the finest ingredients to prepare dishes that reflect authenticity and innovation. Whether you're here for a hearty meal, a light snack, or a sweet treat, our menu is designed to cater to every craving.</p>
            <p>We take pride in our warm and inviting atmosphere, perfect for family gatherings, friendly get-togethers, or a quiet meal on your own. At Tastebuds poppers, we believe food is more than just sustenance—it's an experience, and we are thrilled to share it with you.</p>
        </div>
    </section>
    <footer>
        <p>&copy;TASTEBUDS POPPERS. All Rights Reserved.</p>
        <p> designed and developed by: SWETHA S V</p>
    </footer>
</body>
</html>


contact.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - TASTEBUDS POPPERS</title>
    <style>
        body {
            background-color: rgb(88, 157, 172);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(120, 168, 194);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(119, 204, 205);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(128, 222, 217);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .contact-info {
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }
        footer {
            background-color: rgb(123, 220, 215);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>A warm welcome</h2>
        <div class="contact-info">
            <p><strong>Phone:</strong>9036836856</p>
            <p><strong>Email:</strong> tastebudspoppers@gmail.com</p>
            <p><strong>Address:</strong> 27/4 jpr road, koramangala , bangalore</p>
            <p>we value your feedback</p>
    </section>
    <footer>
        <p>&copy; TASTEBUDS POPPERS. All Rights Reserved.</p>
        <p> designed and developed by: SWETHA S V</p>
    </footer>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot (53).png>)
![alt text](<Screenshot (49).png>)
![alt text](<Screenshot (52).png>)
![alt text](<Screenshot (50).png>)
![alt text](<Screenshot (51).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
