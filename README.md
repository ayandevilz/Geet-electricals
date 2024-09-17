# Geet-electricals
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Geet Electricals</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
            position: relative;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header img {
            max-width: 120px;
            position: absolute;
            top: 20px;
            left: 20px;
            border-radius: 50%;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        h1, h2 {
            color: #007bff;
        }
        .about img, .services img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        .about, .services, .contact {
            margin-bottom: 40px;
        }
        .contact p {
            margin: 10px 0;
        }
        .contact a {
            color: #007bff;
            text-decoration: none;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
        }
        footer p {
            margin: 0;
        }
        .cta-button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: #fff;
            background-color: #007bff;
            border-radius: 5px;
            text-decoration: none;
            transition: background-color 0.3s ease;
            margin-top: 20px;
        }
        .cta-button:hover {
            background-color: #0056b3;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product-item {
            flex: 1 1 calc(33% - 40px);
            background-color: #f1f1f1;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
        }
        .product-item img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 10px;
        }
        .product-item h3 {
            margin: 10px 0;
            color: #007bff;
        }
        .product-item p {
            margin: 0;
            color: #555;
        }
        .product-item .price {
            font-size: 18px;
            color: #333;
            font-weight: bold;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/120x120?text=Logo" alt="Geet Electricals Logo">
        <h1>Geet Electricals</h1>
        <p>Your Trusted Source for Electrical Products and Solutions</p>
    </header>
    <div class="container">
        <section class="about">
            <h2>About Us</h2>
            <img src="https://via.placeholder.com/1200x500?text=About+Us" alt="About Us">
            <p>Geet Electricals has been a cornerstone of quality and reliability in the electrical products market. With years of experience and a passion for excellence, we provide a diverse range of electrical items and solutions tailored to meet the unique needs of our customers. Our mission is to deliver top-notch products that ensure safety, efficiency, and innovation.</p>
            <a href="#contact" class="cta-button">Get in Touch</a>
        </section>
        
        <section class="services">
            <h2>Our Products</h2>
            <img src="https://via.placeholder.com/1200x500?text=Our+Products" alt="Our Products">
            <p>We offer a comprehensive selection of electrical products, each designed to meet the highest standards of quality and performance. Explore our diverse range to find everything you need for residential, commercial, and industrial applications.</p>
            
            <div class="product-list">
                <div class="product-item">
                    <img src="https://via.placeholder.com/300x200?text=Light+Bulbs" alt="Light Bulbs">
                    <h3>Light Bulbs</h3>
                    <p>Energy-efficient light bulbs available in various types and wattages.</p>
                    <p class="price">90 per rupees</p>
                </div>
                <div class="product-item">
                    <img src="https://via.placeholder.com/300x200?text=Electrical+Cables" alt="Electrical Cables">
                    <h3>Electrical Cables</h3>
                    <p>High-quality cables for safe and reliable electrical connections.</p>
                    <p class="price">1400 per rupees</p>
                </div>
                <div class="product-item">
                    <img src="https://via.placeholder.com/300x200?text=Switches+and+Outlets" alt="Switches and Outlets">
                    <h3>Switches and Outlets</h3>
                    <p>Anchor switches for all your electrical needs.</p>
                    <p class="price">15 per rupees</p>
                </div>
                <div class="product-item">
                    <img src="https://via.placeholder.com/300x200?text=Fans+and+Heaters" alt="Fans and Heaters">
                    <h3>Fans </h3>
                    <p>Efficient fans to keep your space comfortable.</p>
                    <p class="price">1409 per rupees</p>
                </div>
                <div class="product-item">
                    <img src="https://via.placeholder.com/300x200?text=Power+Strips" alt="Power Strips">
                    <h3>panel lights</h3>
                    <p>this feel u more luxary.</p>
                    <p class="price">200-300 per rupees</p>
                </div>
                <div class="product-item">
                    <img src="https://via.placeholder.com/300x200?text=Specialized+Equipment" alt="Specialized Equipment">
                    <h3>Specialized Equipment</h3>
                    <p>philips durro switches (modular).</p>
                    <p class="price">30-40 per rupees</p>
                </div>
            </div>
        </section>
        
        <section class="contact" id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or need assistance, feel free to get in touch with us:</p>
            <p>Email: <a href="mailto:ayankhan1234wtwgmail.com">ayankhan1234wtwgmail.com.com</a></p>
            <p>Phone: <a href="tel:9305675970">+9305675970</a></p>
            <p>Address: khinni chuara, alam nagar, rajajipuram, lucknow, INDIA</p>
            <a href="mailto:info@geetelectricals.com" class="cta-button">Send Us an Email</a>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Geet Electricals. All rights reserved.</p>
    </footer>
</body>
</html>
