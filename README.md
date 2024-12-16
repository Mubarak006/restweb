# Ex.07 Restaurant Website
## Date:
15-12-2024
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
restweb.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Header Section */
        .header {
            background-color: #f8f9fa;
            padding: 20px;
            text-align: center;
        }
        .logo-container {
            display: inline-block;
        }

        .logo-container img {
            width: 50px;
            height: 50px;
            vertical-align: middle;
        }

        .logo-container.Restaurantname {
            display: inline-block;
            margin: 0;
            font-size: 1.8em;
            color: #333;
            vertical-align: middle;
        }

        /* Welcome Section */
        .image-section {
            background-color: #ffe4c4;
            padding: 40px 20px;
            text-align: center;
        }

        .image-section .content h2 {
            margin: 0;
            font-size: 2em;
            color: #7b4119;
        }

        .image-section .content p {
            margin-top: 10px;
            font-size: 1.2em;
            color: #333;
            max-width: 800px;
        }

        /* Card Section */
        .card-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
            background-color: #fff3e0;
        }

        .card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            margin: 10px;
            width: 300px;
            padding: 20px;
        }

        .card h3 {
            font-size: 1.5em;
            color: #7b4119;
        }

        .card img {
            width: 100%;
            height: 180px;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .card p {
            font-size: 1em;
            color: #555;
            margin-bottom: 10px;
        }

        .card a {
            text-decoration: underline;
            color: #007bff;
            font-weight: bold;
        }

        /* Footer Section */
        .footer {
            background-color: #f8f9fa;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        .footer img {
            width: 50px;
            height: 50px;
        }

        .footer hr {
            width: 80%;
            margin: 10px auto;
        }

        .footer p {
            font-size: 1em;
            color: #555;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <div class="header">
        <div class="logo-container">
            <img src="logo.jpeg" alt="Restaurant Logo" class="logo-img">
            <h2 class="Restaurant-name">Mubarak Restaurant</h2>
        </div>
    </div>

    <!-- Welcome Section -->
    <center>
    <div class="image-section">
        <div class="content">
            <h2>Welcome to Mubarak Restaurant</h2>
            <p></p>
        </div>
    </div>
    </center>

    <!-- Card Section -->
    <center>
        <div class="links-container">
            <a href="menu.html" class="link">Menu</a>
            <a href="table.html" class="link">Table </a>
            <a href="admin.html" class="link">Administration</a>
            <a href="contact.html" class="link">Contact Us</a>
        </div>
    <div class="card-container">
        <div class="card">
            <h3>Menu</h3>
            <img src="menu.jpeg" alt="Menu">
            <p><b>Explore our foods featuring everything from freshly maked dishes.</b></p>
            <a href="menu.html"><u>View Full Menu</u></a>
        </div>
    
        <div class="card">
            <h3>Book a Table</h3>
            <img src="booktable.jpeg" alt="Book a Table">
            <p><b>Reserve your table today and enjoy to eat our freshly maked dishes with peacefully.</b></p>
            <a href="booktable.html"><u>Book Now</u></a>
        </div>
    
        <div class="card">
            <h3>Opening Hours</h3>
            <img src="openining hours.jpeg" alt="Opening Hours">
            <p><b>You will book you table in our website page and come here.</b></p>
            <a href="#"><u>View Hours</u></a>
        </div>
    </div>
    </center>

    <!-- Footer Section -->
    <div class="footer">
        <div class="logo-section">
            <img src="logo.jpeg" alt="Bakery Logo">
        </div>
        <div class="hrline">
            <hr>
            <p><b>Mubarak R (24900694)</b></p>
        </div>
    </div>

</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - My Restaurant</title>
    <style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: rgb(234, 191, 208);
        color: #333;
    }
    
    header {
        background-color: #444;
        color: white;
        padding: 1em 0;
        text-align: center;
    }
    
    .main-image {
        width: 100%;
        max-width: 600px;
        height: auto;
        border-radius: 10px;
        margin: 20px auto;
        display: block;
    }
    
    section {
        padding: 2em;
        text-align: center;
    }
    
    .food-gallery {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
    }
    
    .food-item {
        margin: 10px;
        text-align: center;
        width: 200px;
    }
    
    .food-item img {
        width: 100%;
        height: auto;
        object-fit: cover;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    
    footer {
        background-color: #444;
        color: white;
        padding: 1em 0;
        text-align: center;
    }

 </style>   
</head>
<body>
    <header>
        <h1>Menu</h1>
    </header>
    <section id="menu">
        <h2>Our Delicious Menu</h2>
        <div class="food-gallery">
            <div class="food-item">
                <img src="Biriyani.jpeg" alt="Dish 1">
                <p>Chicken Biryani</p>
                <p>Rs-120</p>
            </div>
            <div class="food-item">
                <img src="Dish1.jpeg" alt="Dish 2">
                <p>Burger</p>
                <p>Rs-60</p>
            </div>
            <div class="food-item">
                <img src="muttonbiryani.jpeg" alt="Dish 3">
                <p>Mutton Biryani</p>
                <p>Rs-250</p>
            </div>
            <div class="food-item">
                <img src="meals.jpeg" alt="Dish 4">
                <p>Meals</p>
                <p>Rs-100</p>
            </div>
            <div class="food-item">
                <img src="chickenshawarma.jpeg" alt="Dish 5">
                <p>Chicken Shawarma</p>
                <p>Rs-90</p>
            </div>
            <div class="food-item">
                <img src="chickennoodles.jpeg" alt="Dish 6">
                <p>Chicken Noodles</p>
                <p>Rs-130</p>
            </div>
            <div class="food-item">
                <img src="muttonmandhi.jpeg" alt="Dish 7">
                <p>Mutton Mandhi</p>
                <p>Rs-350</p>
            </div>
            <div class="food-item">
                <img src="chickenfriedrice.jpeg" alt="Dish 8">
                <p>Chicken Fried Rice</p>
                <p>Rs-120</p>
            </div>
            <div class="food-item">
                <img src="beefbiryani.jpeg" alt="Dish 9">
                <p>Beef Biryani</p>
                <p>Rs-200</p>
            </div>
            <div class="food-item">
                <img src="Dish2.jpeg" alt="Dish 10">
                <p>French Fries</p>
                <p>Rs-75</p>
            </div>
            <div class="food-item">
                <img src="chieckenpizza.jpeg" alt="Dish 11">
                <p>Chicken Pizza</p>
                <p>Rs-200</p>
            </div>
            <div class="food-item">
                <img src="japanchicken.jpeg" alt="Dish 12">
                <p>Japan Chicken</p>
                <p>Rs-150</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Mubarak Restaurant. All rights reserved.</p>
    </footer>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - My Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #d887a3;
            color: #333;
        }
        header {
            background-color: #444;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        section {
            padding: 2em;
            text-align: center;
            color: black;
            
        }
        .admin-gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            color: rgb(28, 28, 27);
        }
        .admin-item {
            margin: 10px;
            text-align: center;
        }
        .admin-item img {
            width: 200px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #444;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Administration</h1>
    </header>
    <section id="administration">
        <h2>Meet Our Team</h2>
        <div class="admin-gallery">
            <div class="admin-item">
                <img src="mubarak.png" alt="Admin 1">
                <p>Founder and CEO</p>
            </div>
            <div class="admin-item">
                <img src="chefdamu.jpeg" alt="Admin 2">
                <p> chef Damu</p>
            </div>
            <div class="admin-item">
                <img src="chefbhat.jpeg" alt="Admin 3">
                <p>Chef  Venkatesh bhat</p>
            </div>
            <div class="admin-item">
                <img src="chefkowshik.jpeg" alt="Admin 4">
                <p>Chef Kowshik</p>
            </div>
            <div class="admin-item">
                <img src="sanjeevkapoor.jpeg" alt="Admin 5">
                <p>Chef SanjeevKapoor</p>
            </div>
            <div class="admin-item">
                <img src="madampaatyrangaraj.jpeg" alt="Admin 6">
                <p>Chef Madhampatty Rangaraj</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 My Restaurant. Designed by [Mubarak]. All rights reserved.</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - My Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #444;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        section {
            padding: 2em;
            text-align: center;
        }
        #contact {
            background-image: url('path-to-background-image.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 5em 2em;
        }
        .contact-box {
            background: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
            padding: 20px;
            max-width: 400px;
            margin: auto;
        }
        footer {
            background-color: #444;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <section id="contact">
        <div class="contact-box">
            <h2>Get in Touch</h2>
            <p>Address: 85 Bajar Street, Near Busstand, Tiruttani-<br>631209</p>
            <p>Phone: 9894769395,8525947945</p>
            <p>Email: mubarakrestaurant24.gmail.com</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 My Restaurant. Designed by [Mubarak R]. All rights reserved.</p>
    </footer>
</body>
</html>

```

### OUTPUT:
![alt text](<Screenshot (111).png>) 
![alt text](<Screenshot (105).png>)
![alt text](<Screenshot (109).png>)
![alt text](<Screenshot (103).png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
