# Ex.07 Restaurant Website
# Date: 08/11/24
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

# restaurant_proj.html

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
            <a href="admin.html">Admin</a>
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
            <p>Developed by Jayani N</p>
        </footer>
    
    </body>
    </html>



# OUTPUT:

![image](https://github.com/user-attachments/assets/e27709dd-505c-4731-bc4b-559b4909aa39)

![image](https://github.com/user-attachments/assets/65f1f7e7-5d5d-489e-a479-592d2a473604)

![image](https://github.com/user-attachments/assets/07d3a552-53b4-4e31-9cf9-4615bf46edfd)

![alt text](<Screenshot 2024-11-21 184959.png>) 

![alt text](<Screenshot 2024-11-21 185043.png>)

![alt text](<Screenshot 2024-11-21 185103.png>)

![image](https://github.com/user-attachments/assets/7a6da670-207a-479c-a7e1-18210184f207)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
