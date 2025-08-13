# Ex01 Portfolio
## Date: 13-08-25
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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My RESUME</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: hsl(0, 4%, 46%);
            color: #a19696;
        }
        header {
            background: #d0d3d6;
            color: rgb(79, 131, 100);
            padding: 20px;
            font-size: 2em;
            font-weight: bold;
 }
        .container {
            width: 60%;
            margin: auto;
            padding: 20px;
        }
        .section {
            margin: 20px 0;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px white
            text-align: left;
        }
        .about img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        h2 {
            color: #2c3e50;
        }
ul {
            list-style-type: none;
            padding: 0;
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
        li {
            margin: 5px 0;
        }
contact {
            background: #2c3e50;
            color: white;
            padding: 15px;
            border-radius: 8px;
        }
        footer {
            background: #cfd6dc;
            color: rgb(222, 201, 204);
            padding: 10px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        MY RESUME
        <nav>
            <nav>
                <ul>
                <li><a href="#aboutme">About me</a> </li>|
                <li><a href="#skill">Skills</a></li> |
                <li><a href="#experience">Experience</a></li>|
                <li><a href="#education">Education</a></li>|
                <li><a href="#contactme">Contact Me</a></li>
 </ul>
              </nav>
    </header>
    
<section id="aboutme">
    <h2>About Me</h2>
    <img src="c:\Users\User\Documents\SK photo.jpg" alt="My Photo">
    <p>NAME: Keerthika S
       Email id: keerthigasudhagar@gmail.com
       CONTACT NO: 9600475833
       I am a Software Developer
    </p>
</section>
<section id="skill">
    <h2>Skills</h2>
    <ul>
        <li>HTML, CSS</li>
        <li>C,JAVA,C++,PYTHON</li>
     
    </ul>
</section>
<section id="experience">
    <h2>Experience</h2>
    <p><strong>I completed my Internship in Arjun tech (30 days)</p>
</section>
        
        
            
       
<section id="education">
            <h2>Education</h2>
            <p><strong>Bachelor's in Computer Science</strong> - Saveetha Engineering College(2023-2027)</p>
</section>
       
            
      
        
<section id="contactme">
        <h2>Contact Me</h2>
        <p>Email: keerthigasudhagar@gmail.com</p>
        <p>LinkedIn: keerthika.com/in/myprofile</p>
       </section>
          
       
    </div>
    
    <footer>
        <p>&copy; 2025 My Resume | All Rights Reserved</p>
    </footer>
</body>
</html>


```

## OUTPUT
<img width="882" height="122" alt="MW 01" src="https://github.com/user-attachments/assets/0a6080c3-6041-45cb-9987-1e9d72c2ecde" />

<img width="672" height="440" alt="MW 02" src="https://github.com/user-attachments/assets/40677019-cab4-4b5e-874c-421ce933cf27" />

<img width="683" height="30" alt="MW 03" src="https://github.com/user-attachments/assets/b046b840-b199-4430-b6a8-f721ac7fb367" />

<img width="303" height="79" alt="MW 04" src="https://github.com/user-attachments/assets/738ef334-6bd9-4623-8347-c0c7c1b52acf" />

<img width="357" height="57" alt="MW 05" src="https://github.com/user-attachments/assets/56d37efe-4b06-4e4d-9d53-429001c53c9c" />

<img width="486" height="77" alt="MW 06" src="https://github.com/user-attachments/assets/8f926661-2e4f-48df-bbfe-c043f493aff0" />










## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
