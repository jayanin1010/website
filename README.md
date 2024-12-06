# Ex.07 Restaurant Website
# Date:
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

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Millets&More</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                margin: 0;
                padding: 0;
                background-color: #f4f4f4;
            }

            /* Header Section */
            .header {
                text-align: center;
                background-color: #e9ecef;
                padding: 20px;
            }

            .header img {
                width: 60px;
            }

            .nav {
                text-align: center;
                padding: 10px;
                background-color: #333;
            }

            .nav a {
                color: white;
                margin: 0 15px;
                text-decoration: none;
                font-size: 18px;
            }

            .promo {
                background-image: url('https://via.placeholder.com/'); 
                background-size: cover;
                background-position: center;
                color: white;
                padding: 40px 20px;
                text-align: center;
            }

            .promo h1 {
                font-size: 36px;
                margin-bottom: 20px;
            }

            .promo p {
                font-size: 16px;
                width: 80%;
                margin: 0 auto;
            }

            /* Cards Section */
            .cards {
                text-align: center;
                padding: 40px 0;
            }

            .card {
                display: inline-block;
                width: 300px;
                margin: 0 15px;
                background-color: #fefefe;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
                border-radius: 10px;
                text-align: left;
                padding: 20px;
            }

            .card img {
                width: 100%;
                border-radius: 10px 10px 0 0;
            }

            .card h3 {
                font-size: 20px;
                margin: 15px 0;
            }

            .card p {
                font-size: 14px;
                color: #666;
            }

    /* About Section */
    .about-section {
        padding: 50px;
        text-align: center;
    }

    .about-section h2 {
        font-size: 36px;
        margin-bottom: 20px;
    }

    .about-section p {
        font-size: 18px;
        max-width: 600px;
        margin: auto;
    }

    /* Contact Section */
    .contact-section {
        padding: 50px;
        text-align: center;
        background-color: #333;
        color: white;
    }

    .contact-section h2 {
        font-size: 36px;
        margin-bottom: 20px;
    }

    /* Footer */
    .footer {
        text-align: center;
        padding: 10px;
        background-color: #333;
        color: white;
    }
        </style>
    </head>
    <body>

        <!-- Header -->
        <div class="header">
            <img src="DALL·E 2024-10-20 22.23.26 - A modern logo for a restaurant named 'Millet & More'. The design features an elegant and minimalist style, incorporating elements of organic millet gr.webp" alt="Logo"> 
            <h1>Millet & More</h1>
        </div>

        <!-- Navigation Menu -->
        <div class="nav">
            <a href="#">Home</a>
            <a href="menu.html">Menu</a>
            <a href="booking.html">Book</a>
            <a href="#about">About</a>
        </div>
    c
        <!-- Promotional Section -->
        <div class="promo">
            <h1>30% Off This Weekend</h1>
            
        </div>

        <!-- Cards Section -->
        <div class="cards">
            <div class="card">
                <img src="DALL·E 2024-10-20 22.28.11 - A menu design for a restaurant named 'Millets & More'. The menu features a variety of healthy dishes made with millets, including salads, bowls, and d.webp" alt="Menu Image"> <!-- Replace with your menu image -->
                <a href="menu.html">Click here</a>
                <h3>Our New Menu</h3>
                
            </div>
            <div class="card">
                <img src="DALL·E 2024-10-20 22.28.26 - An image for 'Millets & More' restaurant depicting a table reservation. The design includes an elegant wooden table set for two with a stylish tablecl.webp" alt="Book a Table Image"> <!-- Replace with your booking image -->
                <a href="booking.html">Click here</a>
                <h3>Book a Table</h3>
            
            </div>
            <div class="card">
                <img src="image.png" alt="Opening Hours Image"> 
                <a href="opening.html">Click here</a>
                <h3>Opening Hours</h3>
            
            </div>
        </div>

    <BR></BR>


        <!-- About Us Section -->
        <section id="about" class="about-section">
            <h2>About Us</h2>
            <p>
                At Millets & More, we believe that food should not only nourish the body but also tantalize the taste buds. Our chefs craft each dish with care, using locally sourced, organic produce to ensure that every meal is as fresh and flavorful as possible. 
            </p>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact-section">
            <h2>Contact Us</h2>
            <p>Email: contact@millets&more.com</p>
            <p>Phone: +91 234 567 890</p>
            <p>Address: 123 Main Street, Foodville</p>
        </section>

        <!-- Footer -->
        <footer class="footer">
            <p>&copy; 2024 Millet&More Restaurant. All Rights Reserved.</p>
        </footer>

</body>
</html>

# opening.html

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Opening Hours</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div class="container">
            <div class="card">
                <h2>Opening Hours</h2>
                <p>We look forward to welcoming you during the following hours of operation:</p>

                <h3>Regular Hours</h3>
                <ul>
                    <li>Monday to Friday: 10:00 AM - 10:00 PM</li>
                    <li>Saturday: 9:00 AM - 11:00 PM</li>
                    <li>Sunday: 9:00 AM - 9:00 PM</li>
                </ul>

                <h3>Special Hours</h3>
                <p>We also operate extended hours during holidays and special events. Stay tuned for more updates on these occasions.</p>

                <h3>Contact Us</h3>
                <ul>
                    <li>Phone: +123-456-7890</li>
                    <li>Email: contact@restaurant.com</li>
                </ul>

                <h3>Location</h3>
                <p>123 Foodie Street, Culinary City, FC 45678</p>
            </div>
        </div>
    </body>
    </html>

# menu.html

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Menu</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div class="container">
            <div class="card menu">
                <h2>Our Menu</h2>
                <h3>Appetizers</h3>
                <ul>
                    <li>Garlic Bread - $4</li>
                    <li>Bruschetta - $5</li>
                    <li>Stuffed Mushrooms - $6</li>
                </ul>

                <h3>Main Courses</h3>
                <ul>
                    <li>Grilled Chicken Alfredo - $15</li>
                    <li>Margherita Pizza - $12</li>
                    <li>Vegetarian Lasagna - $13</li>
                    <li>Beef Burger with Fries - $14</li>
                </ul>

                <h3>Desserts</h3>
                <ul>
                    <li>Chocolate Lava Cake - $7</li>
                    <li>Tiramisu - $6</li>
                    <li>Cheesecake - $6</li>
                </ul>

                <h3>Beverages</h3>
                <ul>
                    <li>Coffee - $3</li>
                    <li>Fresh Lemonade - $4</li>
                    <li>Soft Drinks - $3</li>
                </ul>
            </div>
        </div>
    </body>
    </html>

# booking.html

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Book a Table</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div class="container">
            <div class="card">
                <h2>Book a Table</h2>
                <p>Reserve your spot at our restaurant for an amazing dining experience. Please provide your details below, and we will get back to you with confirmation.</p>

                <h3>Contact Information</h3>
                <ul>
                    <li>Phone: +123-456-7890</li>
                    <li>Email: reservations@restaurant.com</li>
                </ul>

                <h3>Online Booking Form</h3>
                <form>
                    <label for="name">Full Name:</label>
                    <input type="text" id="name" name="name" placeholder="Enter your name"><br><br>

                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email"><br><br>

                    <label for="phone">Phone Number:</label>
                    <input type="tel" id="phone" name="phone" placeholder="Enter your phone number"><br><br>

                    <label for="date">Reservation Date:</label>
                    <input type="date" id="date" name="date"><br><br>

                    <label for="time">Time:</label>
                    <input type="time" id="time" name="time"><br><br>

                    <label for="guests">Number of Guests:</label>
                    <input type="number" id="guests" name="guests" min="1" max="20" value="2"><br><br>

                    <input type="submit" value="Submit Reservation">
                </form>
            </div>
        </div>
    </body>
    </html>

# OUTPUT:

![alt text](<Screenshot 2024-11-21 185103.png>) 

![alt text](<Screenshot 2024-11-21 184914.png>) 

![alt text](<Screenshot 2024-11-21 184929.png>) 

![alt text](<Screenshot 2024-11-21 184942.png>) 

![alt text](<Screenshot 2024-11-21 184959.png>) 

![alt text](<Screenshot 2024-11-21 185043.png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
