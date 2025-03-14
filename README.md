# Ex01 Portfolio
## Date: 14-03-25
SWETHA A
212223220114
B.TECH IT

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder in the APP and write the HTML code.

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Add CSS media queries for responsiveness.

### STEP 12
Make It Responsive.

### STEP 13
Use relative units like %, em, and rem.

### STEP 14
Apply media queries to adjust styles for different screen sizes.

### STEP 15
Test the program using runserver command.

### STEP 16
Open the HTML file in a browser to check layout and functionality.

### STEP 17
Fix styling issues and refine content placement.

### STEP 18
Deploy the Portfolio.

### STEP 19
Upload to GitHub Pages for free hosting.

## PROGRAM
```
PORT.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">MyPortfolio</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About Me</a></li>
                <li><a href="#">Portfolio</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h1>My Portfolio</h1>
            <p>Crafting digital dreams into innovation.</p>
            <div class="hero-buttons">
                <a href="#" class="btn">Explore Projects</a>
                <a href="#" class="btn secondary">Play Video</a>
            </div>
        </div>
        <div class="hero-image">
            <img src="c:\Users\admin\Documents\blswe.jpg" alt="Portfolio Image">
        </div>
    </section>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Section</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #576572;
            margin: 0;
            padding: 0;
        }
        .portfolio-container {
            max-width: 1100px;
            margin: auto;
            padding: 50px 20px;
        }
        h2 {
            font-size: 2rem;
            margin-bottom: 30px;
        }
        .portfolio-grid {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }
        .portfolio-item {
            background-color: #39424c;
            border-radius: 15px;
            width: 300px;
            text-align: center;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .portfolio-item img {
            width: 60px;
            height: 60px;
            margin-bottom: 10px;
        }
        .portfolio-item .number {
            background-color: #ffcc00;
            color: #5586d0;
            border-radius: 50%;
            width: 30px;
            height: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin: 10px auto;
        }
        .portfolio-item h3 {
            margin: 10px 0;
        }
        .portfolio-item p {
            color: #333;
        }
    </style>
</head>
<body>

    <div class="portfolio-container">
        <h2>Our Portfolio</h2>
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <img src="icon1.png" alt="Project 1">
                <div class="number">1</div>
                <h3>Internet Of Things</h3>
                <p>IoT (Internet of Things) refers to a vast network of interconnected devices that collect, share, and process data via the internet. These devices range from smart home appliances and wearable gadgets to industrial sensors and autonomous vehicles.</p>
            </div>
            <div class="portfolio-item">
                <img src="icon2.png" alt="Project 2">
                <div class="number">2</div>
                <h3>M2M</h3>
                <p>M2M (Machine-to-Machine) Communication is a subset of IoT where devices communicate directly with each other without human intervention. This is commonly used in industrial automation, vehicle tracking, and remote monitoring systems</p>
            </div>
            <div class="portfolio-item">
                <img src="icon3.png" alt="Project 3">
                <div class="number">3</div>
                <h3>IOT Service</h3>
                <p>Cloud Services

                    AWS IoT Core
                    Google Cloud IoT
                    Microsoft Azure IoT Hub
                    IBM Watson IoT
                    Connectivity Protocols
                    
                    MQTT (Message Queuing Telemetry Transport)
                    CoAP (Constrained Application Protocol)
                    LoRaWAN (Low Power Wide Area Network)
                    NB-IoT (Narrowband IoT)</p>
            </div>
        </div>
    </div>

</body>
</html>


















<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Intellectual Property Rights</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #1d2e43; /* Light blue background */
            margin: 0;
            padding: 20px;
        }
        .container {
            background: rgb(73, 132, 147);
            padding: 30px;
            border-radius: 10px;
            max-width: 600px;
            margin: auto;
            box-shadow: 0px 4px 10px rgba(101, 225, 225, 0.2);
        }
        h1 {
            font-size: 24px;
        }
        h2 {
            font-size: 22px;
            text-decoration: underline;
        }
        img {
            width: 120px;
            margin: 20px 0;
        }
        p {
            font-size: 18px;
            margin: 5px 0;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Saveetha engineering College</h1>
        <img src="c:\Users\admin\Documents\images (1).jpeg" alt="University Logo">
        <p><strong>SWETHA A(212223220114)</strong></p>
        <p>Department of Information Technology</p>
        <p><strong>Github Link:https://github.com/aswethaashok</strong></p>
        <p>Connect me for collabration </p>
        <h2>swetha@Copy Rights</h2>
    </div>

</body>
</html>
style.css
```
```
/* General Styles */
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: #405c7c;
    color: #fff;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
    background-color: #50acd4;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Hero Section */
.hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 50px;
}

.hero-text {
    max-width: 50%;
}

.hero-text h1 {
    font-size: 3rem;
}

.hero-buttons {
    margin-top: 20px;
}

.btn {
    display: inline-block;
    background-color: white;
    color: black;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-right: 10px;
}

.btn.secondary {
    background-color: transparent;
    border: 2px solid white;
    color: white;
}

.hero-image img {
    max-width: 400px;
    border-radius: 10px;
}

```

## OUTPUT

![Screenshot 2025-03-14 181844](https://github.com/user-attachments/assets/1be128ab-e01a-4c02-ad42-b5e1b8ad5dac)
![Screenshot 2025-03-14 181854](https://github.com/user-attachments/assets/643d0809-da3c-4a30-8947-458ae16acabe)
![Screenshot 2025-03-14 184242](https://github.com/user-attachments/assets/1e111c79-1015-4990-8c80-791278340c7c)





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
