# Ex.07 Restaurant Website
## Date: 4-11-2024

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Restaurant</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Lan Delight Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Discover Delicious Meals!</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="images/pasta.jpeg" alt="Delicious Pasta">
                    <h4>Italian Pastas</h4>
                    <p>A creamy delight with fresh herbs and parmesan cheese.</p>
                </div>
                <div class="food-item">
                    <img src="images/burger.jpeg" alt="Juicy Burger">
                    <h4>Burgers</h4>
                    <p>Juicy beef patty with lettuce, tomato, and our special sauce.</p>
                </div>
                <div class="food-item">
                    <img src="images/salad.jpeg" alt="Fresh Salad">
                    <h4>Garden Salads</h4>
                    <p>A mix of fresh greens and seasonal vegetables.</p>
                </div>
                <div class="food-item">
                    <img src="images/dessert.jpeg" alt="Dessert">
                    <h4>Chocolate Cakes</h4>
                    <p>Rich and moist chocolate cake with a creamy frosting.</p>
                </div>
            </section>
        </main>
        
        
        <footer>
            <p>Atluru Sai Vardhan Reddy</p>
            <p>212221040022</p>
        </footer>
    </div>
</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Menu</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Lan Delight Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Delicious Food Items</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="images/pasta_primavera.jpg" alt="Pasta Primavera">
                    <h4>Pasta Primavera</h4>
                </div>
                <div class="food-item">
                    <img src="images/margherita_pizza.jpg" alt="Margherita Pizza">
                    <h4>Margherita Pizza</h4>
                </div>
                <div class="food-item">
                    <img src="images/caesar_salad.jpg" alt="Caesar Salad">
                    <h4>Caesar Salad</h4>
                </div>
                <div class="food-item">
                    <img src="images/grilled_salmon.jpg" alt="Grilled Salmon">
                    <h4>Grilled Salmon</h4>
                </div>
                <div class="food-item">
                    <img src="images/spaghetti_carbonara.jpg" alt="Spaghetti Carbonara">
                    <h4>Spaghetti Carbonara</h4>
                </div>
                <div class="food-item">
                    <img src="images/vegetable_stirfry.jpg" alt="Vegetable Stir-fry">
                    <h4>Vegetable Stir-fry</h4>
                </div>
                <div class="food-item">
                    <img src="images/cheeseburger.jpg" alt="Cheeseburger">
                    <h4>Cheeseburger</h4>
                </div>
                <div class="food-item">
                    <img src="images/chicken_tikka_masala.jpg" alt="Chicken Tikka Masala">
                    <h4>Chicken Tikka Masala</h4>
                </div>
                <div class="food-item">
                    <img src="images/stuffed_peppers.jpg" alt="Stuffed Peppers">
                    <h4>Stuffed Peppers</h4>
                </div>
                <div class="food-item">
                    <img src="images/fish_and_chips.jpg" alt="Fish and Chips">
                    <h4>Fish and Chips</h4>
                </div>
                <div class="food-item">
                    <img src="images/tacos_al_pastor.jpg" alt="Tacos al Pastor">
                    <h4>Tacos al Pastor</h4>
                </div>
                <div class="food-item">
                    <img src="images/chocolate_lava_cake.jpg" alt="Chocolate Lava Cake">
                    <h4>Chocolate Lava Cake</h4>
                </div>
            </section>
        </main>
        
        <footer>
            <p>Atluru Sai Vardhan Reddy</p>
            <p>212221040022</p>
        </footer>
    <div>
    
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Contact Us</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Lan Delight Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Get in Touch</h2>
            <p>Address: 123 Delicious St, Food City, Chennai</p>
            <p>Phone: 456-7890</p>
            <p>Email: landelight@restaurant.com</p>
        </main>
        <footer>
            <p>Atluru Sai Vardhan Reddy</p>
            <p>212221040022</p>
        </footer>

    </div>
    
</body>
</html>
```
administration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Administration</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Lan Delight Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Meet Our Team</h2>
            <div class="team">
                <div class="member">
                    <img src="images/admin1.jpeg" alt="Admin 1">
                    <p>John Doe - Manager</p>
                </div>
                <div class="member">
                    <img src="images/admin2.jpeg" alt="Admin 2">
                    <p>Jane Smith - Chef</p>
                </div>
                <div class="member">
                    <img src="images/admin3.jpeg" alt="Admin 3">
                    <p>Emily Johnson - Waiter</p>
                </div>
                <div class="member">
                    <img src="images/admin4.jpeg" alt="Admin 4">
                    <p>Michael Brown - Bartender</p>
                </div>
                <div class="member">
                    <img src="images/admin5.jpeg" alt="Admin 5">
                    <p>Jessica Wilson - Hostess</p>
                </div>
                <div class="member">
                    <img src="images/admin6.jpeg" alt="Admin 6">
                    <p>David Lee - Accountant</p>
                </div>
            </div>
        </main>
        <footer>
            <p>Atluru Sai Vardhan Reddy</p>
            <p>212221040022</p>
        </footer>

    </div>
    
</body>
</html>
```
styles.css
```
* {
    box-sizing: border-box;
}

html, body {
    height: 100%;
    margin: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #ecf0f1;
    color: #2c3e50;
}

.container {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

header {
    background-color:lightskyblue;
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

h1, h2 {
    margin: 10px 0;
}

main {
    flex: 1; 
    padding: 20px;
}

.team {

    display: flex;
    flex-wrap: wrap;
}

.member {
    width: 30%;
    margin: 10px;
    text-align: center;
}

.member img {
    width: 100%;
    height: auto;
    border-radius: 50%;
}

footer {
    text-align: center;
    padding: 20px;
    background-color:lightskyblue;
    color: white;
}
.member
{
    border-radius:50%;
    width: 10%;
    height: 10%;
}
.menu-items {
    display: flex;
    flex-wrap: wrap; 
    justify-content: space-between; 
    margin: 20px 0; 
}

.food-item {
    flex: 1 1 200px; 
    margin: 10px; 
    text-align: center; 
}

.food-item img {
    width: 80%; 
    height: 80%; 
    border-radius: 8px; 
}
.menu-items {
    display: flex;
    flex-wrap: wrap; 
    justify-content: space-between; 
    margin: 20px 0; 
}

.food-item {
    width:10%;
    height: 10%;
    flex: 1 1 200px;
    margin: 10px; 
    text-align: center; 
}

.food-item img {
    width: 50%; 
    height: 50%; 
    border-radius: 8px; 
}
```


## OUTPUT:
![alt text](<Screenshot 2024-10-28 154420.png>)
![alt text](<Screenshot 2024-10-28 154427.png>)
![alt text](<Screenshot 2024-10-28 154432.png>)
![alt text](<Screenshot 2024-10-28 154440.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
