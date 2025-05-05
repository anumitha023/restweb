# Ex.07 Restaurant Website
## Date:05-05-2025

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

## frontpage :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AVJ Restaurant</title>
</head>

<style>

    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color:color-mix(in srgb, #ff002b 50%, #ffffff 50%);
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
    background-color:brown;
    border-radius: 10px;
}

.menu{
    background-color:rgb(221, 152, 62);
    align-items: center;
    color: rgb(146, 89, 114);
    padding: 25px;
    border-radius: 30px;
}
.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 50px;
    height: 80px;
    margin-right: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

.footer{
    padding: 10px 10px;
}

nav ul li a {
    text-decoration: none;
    font-family: 'Times New Roman', Times, serif;
    font-size: large;
    color: #0f1110;
    font-weight: bold;
}

.offer-txt{
    color: rgba(195, 64, 64, 0.47);
}
.hours{
    width: 300px;
    height: 80px;
}

.banner {
    text-align: center;
    background-image: url("Rest background.jpg");
    padding: 10px 40px;
    color: #4f9797;
    border-radius: 10px;
    margin: 25px;
}

.banner h2 {
    font-size: 2.5em;
    margin: 0 0 20px;
}

.features {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: rgb(52, 179, 162);
}

.feature {
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
    font-size: large;
    background-color: rgb(132, 171, 169);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgb(177, 98, 191);
    flex: 1;
    margin: 0 10px;
}

.feature h3 {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.feature img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

p {
    text-align: left;
}

ul {
    text-align: left;
}

.copy{
    margin-left: auto
}

.hyperlink{
    color: rgb(130, 121, 173);
}
    

</style>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="AVJ RESTAURANT Logo">
            <h1 style="font-family: 'Times New Roman', Times, serif;"> AVJ </h1>
        </div>
        <nav class="menu">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        
        <section class="banner" style="background-image: url(homepage.jpg)";>         
             <h2 class="offer-txt style="font-family: 'Times New Roman', Times, serif;">Where every flavor tells a story</h2>
            <h2 class="offer-txt" style="font-family: 'Times New Roman', Times, serif;">"It's [food] o'clock " WELCOME " Take a seat, grab a treat -THE INDIAN RESTAURANT! </h2>
            
            <p class = 'offer-txt' style="font-size: large ; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">The World's No. 1 high quality Indian Restaurant.Take back to memories
                To eat is a necessity, but to eat intelligently is an art</p>
        </section>
        <section class="features">
            <div class="feature">
                <h3>Today's menu</h3>
                <img src="food.png"Our New Menu">
                <p> Today’s menu offers a variety of dishes made with fresh ingredients. Enjoy flavorful starters, delicious main courses, indulgent desserts, chef’s specials, and refreshing drinks. 
                    Every bite is crafted to delight your taste buds!</p>
                
            </div>
            <div class="feature">
                <h3>Book a table</h3>
                <img src="table.png" alt="Book a table">
                <p>Reserve your table at Fusion feast for a memorable dining experience. Whether it’s a dinner, celebration, or casual gathering, enjoy our warm ambiance and delicious flavors.
                     Book now for the perfect meal!!</p>
                
            </div>
            <div class="feature">
                <h3>Opening timings</h3>
                <img src="timing.png" class="hours" alt="Opening Hours">
                <p> Visit us during our convenient hours</p>
                <ul>
                    Monday - Friday: 08:00 AM - 08:00 AM <br>
                    Saturday: 08:00 AM - 8:00 PM <br>
                    Sunday: 08:00 AM - 08:00 PM <br>
                </ul>
                <p> A place for hungry people....!</p>
            </div>
        </section>
        <footer>
            <div class="logo">
                <img src="logo.png" class="footer" alt="AVJ Restaurant Logo">
            </div>
            
                <palign="center" class="copy">&copy; Copyright Fusion feast</p>

            <h3align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
                Developed and designed by ANUMITHA MR</h3>
        </footer>
    </main>
</body>
</html>
```

## home.html: 
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOME</title>
</head>
<div class="logo">
    <top left>
    <img src="logo.png" width="50" height="50"alt="AVJ RESTAURANT LOGO">
</top left>

</div>
    <div class="nav-list">
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Admin</a>
        <a href="contact.html">Contact us</a>
    </div>


<style>
    header{
        font-size: 50px;
        font-style:initial;
        background-color:rgb(209, 144, 122);
    }
    .content{
        font-size: medium;
        padding: 10px;
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
    }
</style>


<body bgcolor="lavender">
    <center>
        <header style="color:rgb(111, 171, 151);">
        FUSION FEAST
        </header>

        <img src="restaurant.png" width="500" height="400">
        
        <div class="content">
        <h2> Welcome to RETRO RELISH Restaurant- A place where taste meets your expectations!!</h2>
        <h2>A short note about fusion feast</h2>
        <p style="font-family:cursive; font-size: large;">
            A retro-style restaurant offers a nostalgic journey back in time, often featuring vintage decor, neon signs,
              checkered floors, and jukeboxes that create a fun, old-school atmosphere. The food matches the vibe,
              with classic American diner fare like juicy burgers, crispy fries, milkshakes, 
              and hearty comfort dishes such as meatloaf or mac and cheese. 
              Everything from the menu design to the staff uniforms evokes a bygone era, 
              making it a unique and memorable dining experience for guests of all ages.
        </p>
        </div>

        <div class="content">
            
            <img src="kitchen.png" width="300" height="200">
            <img src="traditional.png" width="300" height="200">
            <img src="ambiance.png"300" height="200">
            <img src="fest.png" width="300" height="200">
            
        </div>
        <footer>
            
                <p align="center" class="copy">&copy; Copyright AVJ RESTAURANT</p>

            <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
                Developed and designed by ANUMITHA MR</h3>
        </footer>
    </center>
    <div class="logo">
        <img src="logo.png"50" height="50" class="footer" alt="AVJ Restaurant logo">
    </div>
    

</body>
</html>
```

## menu.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <div class="logo">
        <img src="logo.png" width="50" height="50" alt="AVJ RESTAURANT LOGO">
    </div>
    <title>RETRO RESTAURANT - Menu</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #2c3e50;
            color: white;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: white;
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #ff5722;
        }

        .menu-container {
            padding: 40px 20px;
            background: #ffffff;
            text-align: center;
        }

        .menu-container h1 {
            font-size: 2.5rem;
            color: #2c3e50;
            margin-bottom: 30px;
            font-family: 'Playfair Display', serif;
        }

        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .menu-item {
            background: white;
            border-radius: 15px;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: left;
        }

        .menu-item img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .menu-item:hover img {
            transform: scale(1.1);
        }

        .menu-details {
            padding: 15px;
        }

        .menu-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 10px;
            font-weight: 500;
        }

        .menu-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        .menu-details .price {
            font-weight: bold;
            font-size: 1.1rem;
            color: #e74c3c;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #ff5722;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ecf0f1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .menu-items {
                flex-direction: column;
                gap: 20px;
            }

            .menu-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>FUSION FEAST</h1>
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact us</a>
            
        </nav>
    </header>

    <div class="menu-container">
        <h1>OUR MENU</h1>
        <div class="menu-items">
            <div class="menu-item">
                <img src="idly.png" alt="Idly">
                <div class="menu-details">
                    <h3>Idly</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="pongal.png" alt="Pongal">
                <div class="menu-details">
                    <h3>Pongal</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="Dosa.png" alt="Dosa">
                <div class="menu-details">
                    <h3>Dosa</h3>
                    <p class="price">₹120/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="poori.png" alt="Poori">
                <div class="menu-details">
                    <h3>Poori</h3>
                    <p class="price">₹180/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="Biriyani.png" alt="Biriyani">
                <div class="menu-details">
                    <h3>chicken Biriyani</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="mutton biriyani.png" alt="Mutton Biriyani">
                <div class="menu-details">
                    <h3>Mutton Biriyani</h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>
            
            <div class="menu-item">
                <img src="chicken tandori.png" alt="chicken Tandoori">
                <div class="menu-details">
                    <h3>chicken Tandoori</h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="prawn.png" alt="prawn">
                <div class="menu-details">
                    <h3>Prawn</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="veg biriyani.png" alt="Veg biriyani">
                <div class="menu-details">
                    <h3>Veg biriyani</h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="full meal.png" alt="Full meals">
                <div class="menu-details">
                    <h3>Full meals/h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="veg noodles.png" alt="Veg noodles">
                <div class="menu-details">
                    <h3>Veg Noodles</h3>
                    <p class="price">₹250/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="sambar rice.png" alt="Sambar rice">
                <div class="menu-details">
                    <h3>Sambar rice</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="jamun.png" alt="Gulab jamun">
                <div class="menu-details">
                    <h3>Gulab jamun</h3>
                    <p class="price">₹350/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="rasmalai.png" alt="Rasmalai">
                <div class="menu-details">
                    <h3>Rasmalai</h3>
                    <p class="price">₹450/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="kaju katli.png" alt="kaju katli">
                <div class="menu-details">
                    <h3>kaju katli</h3>
                    <p class="price">₹300/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="coco pudding.png" alt="Chocolate pudding">
                <div class="menu-details">
                    <h3>Chocolate pudding</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="badam milk.png" alt="Badam milk">
                <div class="menu-details">
                    <h3>Badam milk</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="rose milk.png" alt="Rose milk">
                <div class="menu-details">
                    <h3>Rose milk</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="chocolate milkshake.png" alt="chocolate milkshake">
                <div class="menu-details">
                    <h3>chocolate milkshake</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="starwberry milkshake.png" alt="strawberry milkshake">
                <div class="menu-details">
                    <h3>strawberry milk</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
            
        <p align="center" class="copy">&copy; Copyright AVJ RESTAURANT</p>

    <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
        Developed and designed by ANUMITHA MR</h3>
</footer>
</center>
<div class="logo">
<img src="logo.png" width="50" height="50" class="footer" alt=" AVJ Restaurant Logo">
</div>


</body>
</html>
```

## contact.html: 
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Contact Us - Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
             <center>
            <div class="logo">
                <img src="logo.png" width="100" height="100" alt="AVJ Restaurant Logo">
            </center>
            <h1>AVJ RESTAURANT</h1>
        <div class="container">
            <h1>Contact us</h1>
            <nav>
                <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact us</a></li>
                </ul>
            </nav>
        </div>
    </header>
<style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #66c0ca;
    color: #1956cf;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #d8a2e6;
    padding: 20px 0;
    color: #fff;
}

header h1 {
    text-align: center;
    font-size: 2.5em;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-size: 1.2em;
}

nav ul li a:hover {
    text-decoration: underline;
}

.contact-us {
    background-color: #fff;
    padding: 40px 0;
    margin-top: 20px;
}

.contact-us h2 {
    text-align: center;
    font-size: 2.5em;
    margin-bottom: 20px;
}

.contact-us p {
    text-align: center;
    font-size: 1.2em;
    margin-bottom: 40px;
}

form {
    width: 100%;
    max-width: 600px;
    margin: 0 auto;
    background-color: #ecf0f1;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.form-group {
    margin-bottom: 20px;
}

label {
    display: block;
    font-size: 1.1em;
    margin-bottom: 5px;
}

input, textarea {
    width: 100%;
    padding: 10px;
    font-size: 1em;
    border: 1px solid #ddd;
    border-radius: 4px;
    margin-top: 5px;
}

button {
    width: 100%;
    padding: 12px;
    background-color: #27dcd3;
    color: #fff;
    font-size: 1.2em;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #2775c4;
}

footer {
    background-color: #5b7fa2;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 40px;
}

</style>
    <section class="contact-us">
        <div class="container">
            <h2>Contact Us</h2>
            <p>"We'd love to hear from you! Need a reservation or have a query?"</p>
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" placeholder="Your Email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
                </div>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>
    <footer>
        <h1>Address-sriperambadu,chennai district</h1>
        <h1>email-retorelisht@gmail.com</h1>
        <h1>Phone-+919515127326</h1>
          <h2>Food that not only satisfies your hunger but also your soul</h2>  
        <p align="center" class="copy">&copy; Copyright AVJ RESTAURANT</p>

    <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
        Developed and designed by ANUMITHA MR</h3>
</footer>
    

</body>
</html>
```


## OUTPUT:

![Screenshot 2025-05-05 185713](https://github.com/user-attachments/assets/834042a9-3a8a-473f-8387-5a785c065fe0)

![Screenshot 2025-05-05 185826](https://github.com/user-attachments/assets/3e1c6e43-82c5-41e8-b72a-ecc9473a73fd)

![Screenshot 2025-05-05 190409](https://github.com/user-attachments/assets/4039834f-ba3c-42d9-ae01-286a607b63e8)

![Screenshot 2025-05-05 185740](https://github.com/user-attachments/assets/a4e77569-06fd-4da1-87d8-acea67075192)

![Screenshot 2025-05-05 185804](https://github.com/user-attachments/assets/246cebac-9b9a-4e26-81bc-b3bf12c486a0)





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
