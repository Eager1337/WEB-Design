# Alusine G Dumbuya_905005223_BIT1102_SEM 3

# Figma Wire Frame
https://parrot-plank-32632060.figma.site/

# Sketch-Wireframe
Football Agency SierraLeone, the only football agency in the country that manages and sell local players


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Green Bean Coffee Shop</title>
    
    <style>
        /* 4. CSS Developer: Style elements according to UI designer's specifications */
        
        /* 4. CSS Developer: Apply: background-colors, width, height, font-family */
        body {
            font-family: Arial, sans-serif;
            background-color: #F5F5DC; /* Soft Cream */
            color: #4E342E; /* Dark Brown */
            margin: 0;
            line-height: 1.6;
        }

        header {
            background-color: #2E4D2C; /* Forest Green */
            color: #F5F5DC; /* Soft Cream */
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 48px; /* Designer Spec */
            margin: 0;
        }

        nav a {
            color: #F5F5DC;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        .container {
            width: 85%; /* Designer Spec: Width */
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }

        /* 3. HTML Developer: Include images (img) */
        .hero img {
            width: 100%;
            height: 400px; /* Designer Spec: Height */
            object-fit: cover;
            margin-bottom: 30px;
        }

        section {
            padding: 30px 0;
            border-bottom: 1px solid #ccc;
        }

        /* 4. CSS Developer: Style text: font-size */
        p {
            font-size: 18px; 
        }

        ul {
            list-style: disc;
            padding-left: 20px;
        }

        footer {
            background-color: #4E342E; /* Dark Brown */
            color: #F5F5DC;
            text-align: center;
            padding: 20px 0;
            margin-top: 30px;
        }

        footer a {
            color: #F5F5DC;
        }
    </style>
</head>

<body>
    <header>
        <h1 class="main-title">The Green Bean Coffee Shop</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#menu">Menu</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main class="container">
        
        <div class="hero">
            <img src="https://picsum.photos/id/1060/1200/400" alt="A steaming mug of coffee on a wooden table">
            
            <h2 style="text-align: center; color: #2E4D2C; font-style: italic;">Sip Slowly, Live Fully.</h2> 
        </div>

        <section id="about">
            <h2>Our Philosophy</h2>
            <p>At The Green Bean, we hand-select fair-trade beans and roast them in-house daily. Experience the rich difference in every cup. We believe coffee is more than a drink—it’s a ritual.</p>
            
            <img src="https://picsum.photos/id/1054/800/600" alt="A barista pouring latte art" style="max-width: 400px; display: block; margin: 30px auto; border-radius: 5px;">
        </section>

        <section id="menu">
            <h2>Our Signature Brews</h2>
            <ul>
                <li style="font-weight: 900;">The Daily Drip</li>
                <li>The Iced Lavender Latte</li>
                <li>Signature Cold Brew</li>
                <li>Classic Cappuccino</li>
            </ul>
        </section>
    </main>

    <footer id="contact">
        <h3>Visit Us</h3>
        <p>123 Bean Street, Coffee Town, CA 90210 | (555) BEAN-MUG</p>
        <p><a href="mailto:hello@thegreenbean.com">hello@thegreenbean.com</a></p>
    </footer>
</body>
</html>
