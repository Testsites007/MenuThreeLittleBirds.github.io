<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title style="font-family: 'Arial', sans-serif;">About Three Little Birds Catering</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Reset some default styles */
        body, h1, p {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: "Arial", sans-serif; /* Use a backup font if the specified font is not available */
            background-image: url('https://static.vecteezy.com/system/resources/previews/001/431/920/non_2x/abstract-green-background-free-vector.jpg');
            background-size: cover; /* Cover the entire viewport with the background image */
            background-repeat: no-repeat; /* Prevent the background image from repeating */
            color: #fff; /* Set text color to white for better contrast */
        }

        header {
            background-color: #006400; /* Set the background color of the header to dark green */
            color: #333;
            text-align: center;
            padding: 20px 0;
        }

        /* Remove font color and font family from header h1 */
        header h1 {
            font-size: 36px;
            text-align: center;
            margin: 0;
            padding: 10px;
            color: #FFA500; /* Set the text color to yellowish-orange */
        }

        nav ul {
            list-style-type: none;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff; /* Set link color to white */
            font-weight: bold;
        }

        section {
            padding: 40px;
            text-align: center; /* Center-align the content in the section */
        }

        section h2 {
            font-size: 24px;
            margin-bottom: 20px;
            font-family: 'cursive-font', cursive, "Lucida Handwriting", "Brush Script MT", sans-serif; /* Use cursive font for section titles */
            color: teal; /* Set the section title color to teal */
        }

        /* Teal blue dividers */
        .divider {
            background-color: teal; /* Change divider color to teal */
            height: 2px;
            margin: 20px 0;
        }

        /* Center-align the table within the section */
        table {
            margin: 0 auto; /* Center-align the table */
            background-color: red; /* Set the background color of the table to red */
            color: #fff;
        }

        table, th, td {
            border: 1px solid #fff;
        }

        table th, table td {
            padding: 10px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        /* Set the text color of p elements to black */
        p {
            color: #000;
        }
    </style>
</head>
<body>
    <header>
        <!-- Center-aligned title with specified text colors -->
        <h1><span style="color: #FFA500;">Three</span> <span style="color: #FFA500;">Little</span> <span style="color: #FFA500;">Birds</span> Catering</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="https://github.com/Testsites007/MenuThreeLittleBirds.github.io" target="_blank">Menu</a></li>
                <!-- The "target="_blank"" attribute opens the link in a new tab/window -->
                <li><a href="about.html">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section>
        <!-- Add your "About" content here -->
        <h2>About Three Little Birds Catering</h2>
        <p>Welcome to Three Little Birds Catering, where culinary artistry meets passion. Our journey began with a simple idea - to create exquisite dishes that delight the senses and warm the heart. With a team of dedicated chefs and a commitment to quality, we've been bringing joy to food lovers since our inception.</p>
        <p>Our philosophy revolves around the belief that great food is not just a meal; it's an experience. Every dish we craft tells a story of flavors, cultures, and creativity. We take pride in sourcing the finest ingredients, infusing innovation into traditional recipes, and serving you a memorable dining experience.</p>
        <p>Whether you're celebrating a special occasion, indulging in a romantic dinner, or simply seeking a delightful meal, Three Little Birds Catering welcomes you with open arms. Join us on this culinary journey, and let your taste buds soar with the melodies of flavors that define us.</p>

        <!-- Order Table -->
        <h2>Order Your Favorites</h2>
        <table>
            <thead>
                <tr>
                    <th>Item</th>
                    <th>Description</th>
                    <th>Price</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Chicken Soup</td>
                    <td>Delicious homemade chicken soup</td>
                    <td>$8.99</td>
                </tr>
                <tr>
                    <td>Tacos</td>
                    <td>Three soft tacos with your choice of filling</td>
                    <td>$10.99</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Teal blue divider -->
    <div class="divider"></div>

    <!-- Contact section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or would like to reach out to us, please feel free to contact us using the information below:</p>
        <ul>
            <li>Email: <a href="mailto:threelittlebirds110506@gmail.com">threelittlebirds110506@gmail.com</a></li>
            <li>Phone: <a href="tel:+13096211678">309-621-1678</a></li>
            <li>Address: 123 Main Street, Houston, TX</li> <!-- Note: I've added "TX" for the state abbreviation -->
        </ul>
    </section>

    <!-- Closing HTML Tags -->
</body>
</html>
