# Ex.07 Restaurant Website
# Date:05/10/2025
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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sunset Dine - Home</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <img src="images/banner.png" alt="Restaurant Banner" class="banner">
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="intro">
    <h1>Welcome to Sunset Dine</h1>
    <p>Where taste meets tradition — enjoy a cozy dining experience with our signature dishes made fresh every day.</p>
  </section>
</body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sunset Dine - Menu</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html" class="active">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <div class="food">
      <img src="images/pasta.png" alt="Pasta">
      <h3>Creamy Alfredo Pasta</h3>
      <p>₹250</p>
    </div>
    <div class="food">
      <img src="images/burger.png" alt="Burger">
      <h3>Grilled Chicken Burger</h3>
      <p>₹180</p>
    </div>
    <div class="food">
      <img src="images/pizza.png" alt="Pizza">
      <h3>Veggie Supreme Pizza</h3>
      <p>₹300</p>
    </div>
    <div class="food">
      <img src="images/biriyani.png" alt="Biryani">
      <h3>Hyderabadi Biryani</h3>
      <p>₹320</p>
    </div>
    <div class="food">
      <img src="images/salad.png" alt="Salad">
      <h3>Caesar Salad</h3>
      <p>₹150</p>
    </div>
    <div class="food">
      <img src="images/soup.png" alt="Soup">
      <h3>Tomato Basil Soup</h3>
      <p>₹120</p>
    </div>
    <div class="food">
      <img src="images/tandoori.png" alt="Tandoori">
      <h3>Tandoori Chicken</h3>
      <p>₹350</p>
    </div>
    <div class="food">
      <img src="images/paneer.png" alt="Paneer">
      <h3>Paneer Butter Masala</h3>
      <p>₹280</p>
    </div>
    <div class="food">
      <img src="images/dosa.png" alt="Dosa">
      <h3>Masala Dosa</h3>
      <p>₹100</p>
    </div>
    <div class="food">
      <img src="images/juice.png" alt="Juice">
      <h3>Fresh Lime Juice</h3>
      <p>₹70</p>
    </div>
    <div class="food">
      <img src="images/ice cream.png" alt="Ice Cream">
      <h3>Chocolate Sundae</h3>
      <p>₹120</p>
    </div>
    <div class="food">
      <img src="images/brownie.png" alt="Brownie">
      <h3>Walnut Brownie</h3>
      <p>₹130</p>
    </div>
  </section>

  <footer>
    <p>© 2025 Sunset Dine | Designed by <b>Gianna</b></p>
  </footer>
</body>
</html>


admin.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sunset Dine - Administration</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>Meet Our Team</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html" class="active">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="team">
    <div class="member"><img src="images/men 1.png"><h3>Mr. Rajesh</h3><p>Head Chef</p></div>
    <div class="member"><img src="images/women 1.png"><h3>Ms. Priya</h3><p>Manager</p></div>
    <div class="member"><img src="images/men 2.png"><h3>Mr. Ravi</h3><p>Assistant Chef</p></div>
    <div class="member"><img src="images/women 2.png"><h3>Ms. Latha</h3><p>Waitress</p></div>
    <div class="member"><img src="images/men 3.png"><h3>Mr. Arjun</h3><p>Cashier</p></div>
    <div class="member"><img src="images/men 4.png"><h3>Mr. Sanjay</h3><p>Cleaner</p></div>
  </section>

  <footer>
    <p>© 2025 Sunset Dine | Designed by <b>Gianna</b></p>
  </footer>
</body>
</html>


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sunset Dine - Contact Us</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>Contact Us</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html" class="active">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="contact">
    <h2>We'd Love to Hear From You!</h2>
    <p>📍 Address: No.45, Beach Road, Kanyakumari, Tamil Nadu</p>
    <p>📞 Phone: +91 98765 43210</p>
    <p>📧 Email: contact@sunsetdine.com</p>
  </section>

  <footer>
    <p>© 2025 Sunset Dine | Designed by <b>Gianna</b></p>
  </footer>
</body>
</html>

style.css

/* --- Global Styles --- */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');

body {
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #d4f3ff, #fbeeff);
  margin: 0;
  padding: 0;
  color: #333;
  overflow-x: hidden;
}

/* --- Header --- */
header {
  background: linear-gradient(90deg, #ff6a00, #ffb347);
  color: #fff;
  text-align: center;
  padding: 20px 10px;
  box-shadow: 0 3px 8px rgba(0,0,0,0.15);
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
  letter-spacing: 1px;
}

/* --- Navigation --- */
nav ul {
  list-style: none;
  padding: 0;
  margin: 15px 0 0;
}

nav li {
  display: inline-block;
  margin: 0 15px;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-weight: 600;
  font-size: 1.1rem;
  transition: color 0.3s, transform 0.3s;
}

nav a:hover,
nav a.active {
  color: #222;
  text-shadow: 0 0 5px #fff;
  transform: scale(1.1);
}

/* --- Banner Image --- */
.banner {
  width: 100%;
  height: 380px;
  object-fit: cover;
  border-bottom: 5px solid #ff6a00;
  box-shadow: 0 4px 15px rgba(0,0,0,0.2);
  animation: fadeIn 1.5s ease-in-out;
}

/* --- Sections --- */
section {
  text-align: center;
  padding: 40px 20px;
}

section h2 {
  color: #ff6a00;
  font-size: 2rem;
  margin-bottom: 25px;
}

/* --- Menu & Team Layout --- */
.menu, .team {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
}

/* --- Food & Member Cards --- */
.food, .member {
  background: #fff;
  border-radius: 18px;
  width: 230px;
  padding: 15px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.food:hover, .member:hover {
  transform: translateY(-10px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.2);
}

.food img, .member img {
  width: 100%;
  height: 160px;
  border-radius: 12px;
  margin-bottom: 10px;
  object-fit: cover;
}

.food h3, .member h3 {
  color: #ff6a00;
  margin-bottom: 5px;
}

.food p {
  font-weight: 600;
  color: #333;
}

/* --- Footer --- */
footer {
  background: linear-gradient(90deg, #333, #444);
  color: #fff;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
  font-size: 0.95rem;
  letter-spacing: 0.5px;
}

footer b {
  color: #ffb347;
}

/* --- Animations --- */
@keyframes fadeIn {
  from { opacity: 0; transform: scale(1.05); }
  to { opacity: 1; transform: scale(1); }
}
```
# OUTPUT

![alt text](<Screenshot 2025-10-05 132639.png>)
![alt text](<Screenshot 2025-10-05 132657.png>)
![alt text](<Screenshot 2025-10-05 132708.png>)
![alt text](<Screenshot 2025-10-05 132717.png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
