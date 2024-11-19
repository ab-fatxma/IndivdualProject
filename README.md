<style class="css">body {
    background-color: #f4f4f4; /* Background color */
    text-align: center; /* Center the content */
    font-family: Arial, sans-serif;
}

header {
    background-color: #9f1a1a; /* Banner color */
    padding: 20px;
}

footer {
    margin-top: 20px;
    padding: 10px;
    background-color: #333;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}

nav {
    margin: 20px 0;
}

nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #333;
}</style>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Restaurant Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Fatima Abdi's Restaurant</h1>
        <img src="https://marketplace.canva.com/EAFpeiTrl4c/1/0/1600w/canva-abstract-chef-cooking-restaurant-free-logo-9Gfim1S8fHg.jpg" alt="Restaurant Banner" style="width:15%; height:auto;">
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="contact_us.html">Contact Us</a>
        <a href="location.html">Location</a>
    </nav>
    <h2>Welcome to Our Restaurant!</h2>
    <p>At our restaurant, we take pride in serving delicious and satisfying meals that cater to every craving. Whether you’re in the mood for a juicy burger, a savory calzone, or a hearty lasagna, we have something for everyone. Our menu features a variety of flavors and ingredients, all crafted with care to provide you with a delightful dining experience. Join us and discover your new favorite dish today!</p>
    <footer>
        <p>&copy; 2024 Fatima Abdi. COMP213 Individual Project.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Your Restaurant Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Fatima Abdi's Restaurant</h1>
        <img src="https://marketplace.canva.com/EAFpeiTrl4c/1/0/1600w/canva-abstract-chef-cooking-restaurant-free-logo-9Gfim1S8fHg.jpg" alt="Restaurant Banner" style="width:25%; height:auto;">
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="contact_us.html">Contact Us</a>
        <a href="location.html">45 E St. & 32nd Ave T5E 3M5 Calgary, AB </a>
    </nav>
    <h2>Menu</h2>
    <ul>
        <li>Appetizers
            <ul>
                <li>GO2 Burger - $10 - Bun , Cheese , Patty , Lettuce & Ketchup</li>
                <li>Buffalo Chicken Sandwich  - $12 - Crispy chicken , Lettuce , Tomato & Buffalo sauce</li>
            </ul>
        </li>
        <li>Main Courses
            <ul>
                <li>Calzone - $15 - Cheese , Salami , pepporoni , Mushrooms , Spinach. Comes with pizza sauce or white sauce </li>
                <li>Lasagna - $18 - Meat , onion & garlic , tomato products , sugar , cheese & eggs</li>
            </ul>
        </li>
    </ul>
    <footer>
        <p>&copy; 2024 Fatima Abdi. COMP213 Individual Project.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Fatima's Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Fatima's Restaurant</h1>
        <img src="https://marketplace.canva.com/EAFpeiTrl4c/1/0/1600w/canva-abstract-chef-cooking-restaurant-free-logo-9Gfim1S8fHg.jpg" alt="Restaurant Banner" style="width:100%; height:auto;">
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="contact_us.html">Contact Us</a>
        <a href="location.html">Location</a>
    </nav>
    <h2>Buffalo Chicken Sandwich</h2>
    <img src="https://www.kitchensanctuary.com/wp-content/uploads/2024/09/Buffalo-Chicken-Burger-square-FS-2.jpg" alt="Dish Name" style="width:10%; height:auto;">
    <p>Ingredients: Crispy chicken , Lettuce , Tomato & Buffalo sauce</p>
    <p>Price: $12</p>
    <footer>
        <p>&copy; 2024 Fatima Abdi. COMP213 Individual Project.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Fatima Abdi's Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Fatima Abdi's Restaurant</h1>
        <img src="https://marketplace.canva.com/EAFpeiTrl4c/1/0/1600w/canva-abstract-chef-cooking-restaurant-free-logo-9Gfim1S8fHg.jpg" alt="Restaurant Banner" style="width:40%; height:auto;">
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="contact_us.html">Contact Us</a>
        <a href="location.html">Location</a>
    </nav>
    <h2>Contact Us</h2>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br>
        <label for="telephone">Telephone:</label><br>
        <input type="tel" id="telephone" name="telephone"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" required></textarea><br>
        <input type="submit" value="Submit">
    </form>
    <h3>Contact Information:</h3>
    <p>Email: FatimaAbdiRestaurant@example.com</p>
    <p>Telephone: (403) 456-7850</p>
    <p>Follow us on:</p> <!-- You can add social media icons here -->
    <footer>
        <p>&copy; 2024 Fatima Abdi. COMP213 Individual Project.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Location - Restaurant Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Fatima Abdi's Restaurant</h1>
        <img src="https://marketplace.canva.com/EAFpeiTrl4c/1/0/1600w/canva-abstract-chef-cooking-restaurant-free-logo-9Gfim1S8fHg.jpg" alt="Restaurant Banner" style="width:25%; height:auto;">
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="contact_us.html">Contact Us</a>
        <a href="location.html">Location</a>
    </nav>
    <h2>Our Location</h2>
    <p>Address: 45 E St. & 32nd Ave T5E 3M5 Calgary, AB</p>
    <h3>Find us on the map:</h3>
    <!-- Replace with Google Map Embed or clickable map -->
    <iframe src="https://www.google.com/maps/embed?pb=..." width="400" height="350" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    <footer>
        <p>&copy; 2024 Fatima Abdi. COMP213 Individual Project.</p>
    </footer>
</body>
</html>
