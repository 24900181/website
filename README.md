# Ex.07 Restaurant Website
# Date:03.05.2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:

```
index.html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FOODOS CHEAP THRILLS - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="FOODOS CHEAP THRILLS">
            <h1>FOODOS CHEAP THRILLS</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h2>25% discount This Weekend</h2>
        <p>SERVICE OF APPETIZING FOODS AT ITS EARLIEST</p>
    </section>

    <section class="features">
        <div class="card">
            <h3>Our New Menu</h3>
            <p>jalapeno poppers</p>
            <img src="jalapeno-poppers-22992e4.jpg" alt="New Menu">
            <p>Your cravings called—we answered.</p>
            <a href="menu.html">See our new menu</a>
        </div>
        <div class="card">
            <h3>Book a table</h3>
            <img src="custom-restaurant-table.jpg" alt="Book a Table">
            <p>The table’s waiting. Are you?</p>
            <a href="#">Book your table now</a>
        </div>
        <div class="card">
            <h3>Opening Hours</h3>
            <img src="working hours.jpg" alt="Chef">
            <p>Mon - Fri: 3pm - 10pm<br>Sat: 12pm - 12am<br>Sun: 4pm - 8pm</p>
        </div>
    </section>

    <footer>
        <img src="logo.png" alt="FOODOS CHEAP THRILLS Icon" class="footer-logo">
        <p>Designed and Developed by NETHRA.K (212224230184) </p>
    </footer>
</body>
</html>
```

```
menu .html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - FOODOS CHEAP THRILLS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>FOODOS CHEAP THRILLS</header>
    <main class="menu">
        <h2>Our Menu</h2>
        <br>
        <div class="menu-grid">
            <div class="menu-item"><img src="item.1.jpg"><h4>TOMATO SOUP</h4><p>With herbs and fresh cream</p></div>
            <div class="menu-item"><img src="item.2.jpeg"><h4>MUSHROOM TIKKA</h4><p>Indian classic</p></div>
            <div class="menu-item"><img src="item.3.jpg"><h4>JALAPENO POPPERS</h4><p>Special menu</p></div>
            <div class="menu-item"><img src="item.4.jpeg"><h4>CRISPY BABY CORN ROAST</h4><p>Fresh & crunchy</p></div>
            <div class="menu-item"><img src="item.5.jpeg"><h4>DUM ALOO BIRIYANI</h4><p>Indian cuisine</p></div>
            <div class="menu-item"><img src="item.6.jpeg"><h4>CHINESE HAKKA NOODLES</h4><p>Chinese classic</p></div>
            <div class="menu-item"><img src="item.7.jpeg"><h4>SCHEZWAN FRIED RICE</h4><p>Chinese cuisine</p></div>
            <div class="menu-item"><img src="item.8.jpeg"><h4>BAKED SPAGETTI</h4><p>cheese-loaded</p></div>
            <div class="menu-item"><img src="item.9.jpeg"><h4> HOT MOCHA CHOCOLATE</h4><p>With maple syrup</p></div>
            <div class="menu-item"><img src="item.10.jpeg"><h4>BLUE CURACAO MOJITO</h4><p></p>with tangy lemon</div>
            <div class="menu-item"><img src="item.11.jpeg"><h4>TIRAMISU CAKE</h4><p>chocolate-overloaded </p></div>
            <div class="menu-item"><img src="item.12.jpeg"><h4>HOT SIZZLING BROWNIE</h4><p>Seasonal special</p></div>
        </div>
    </main>
    <footer>
        <img src="logo.png" alt="FOODOS CHEAP THRILLS" class="footer-logo">
        Developed by NETHRA K (212224230184)
    </footer>
</body>
</html>
```
```
admin.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - FOODOS CHEAP THRILLS </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>FOODOS CHEAP THRILLS </header>
    <main class="admin">
        <h2>Meet Our Team</h2>
        <div class="admin-grid">
            <div class="admin-card"><img src="chef1.jpeg"><h4>SANJAY RAMASAMY</h4><p>Head Chef</p></div>
            <div class="admin-card"><img src="chef2.jpeg"><h4>STELLA MARY</h4><p>Restaurant Manager</p></div>
            <div class="admin-card"><img src="chef3.jpeg"><h4>AMANDA</h4><p>Pastry Chef</p></div>
            <div class="admin-card"><img src="chef 4.jpeg"><h4>JAMESMITH</h4><p>Marketing Head</p></div>
            <div class="admin-card"><img src="chef5.jpeg"><h4>HAO JIAN</h4><p>Customer Relations</p></div>
            <div class="admin-card"><img src="chef6 (2).jpeg"><h4>LI</h4><p>Finance Officer</p></div>
        </div>
    </main>
    <footer>
        <img src="logo.png" alt="FOODOS CHEAP THRILLS " class="footer-logo">
        Developed by NETHRA.K (212224230184)
    </footer>
</body>
</html>
```

```
contact.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - FOODOS CHEAP THRILLS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>FOODOS CHEAP THRILLS</header>
    <main class="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> 3rd Face,2nd cross st, J.P. NAGAR, BENGALURU, India</p>
        <p><strong>Phone:</strong> +91 8807180260</p>
        <p><strong>Email:</strong> contact@FOODOS CHEAP THRILLS.com</p>
    </main>
    <footer>
        <img src="logo.png" alt="FOODOS CHEAP THRILLS" class="footer-logo">
        Developed by NETHRA.K (212224230184)
    </footer>
</body>
</html>
```
# OUTPUT:

![alt text](<index page.png>)


![alt text](<menu page.png>)


![alt text](<admin page.png>)


![alt text](<contact page.png>)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
