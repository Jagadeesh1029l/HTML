# HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header> 
        <marquee><h1>Yadavalli Jagadeesh Portfolio</h1></marquee>
    </header>
        <nav>
             <li><a href="#about">About</a></li>
             <li><a href="#Education">Education</a></li>
             <li><a href="#Skills">Projects</a></li>
             <li><a href="#Projects">Skills</a></li>
             <li><a href="#contact">Contact</a></li>
        </nav>
 
     <div class="container">
       <section id="About" class="profile">
         <img src="C:\Users\DELL\OneDrive\Pictures\Saved Pictures\My Pic.jpg" alt="Profile">
         <p>Hi, I'm Yadavalli Jagadeesh, an aspiring Java Full Stack Developer based in Veluru, Andhra Pradesh, India. I'm passionate about building efficient, scalable web applications and solving real-world problems through clean, maintainable code.</p>
       </section>
    
    <section id="education">
         <h2>Education</h2>
          <ul>
             <li><strong><h3>Btech :</h3></strong> Tirumala Engineering College
                <br> Electronics & Communication Engineering
                <br><strong>CGPA :</strong> 6.7
                <br><Strong>Year :</Strong> 2021-2024
             
             <li><strong><h4> Diploma :</h4></strong>Chundi Ranganayakulu Polytechnic College
                <br>Electronics & Communication 
                <br><strong>Percentage :</strong>79.5
                <br><strong>Year :</strong>2018-2021


             <li><strong><h5>SSC :</h5></strong> Chaitanya High School
                <br><strong>CGPA :</strong>9.2
                <br><strong>Year :</strong>2018
          </ul>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Core Java, OOPs, Collections, Exception Handling</li>
            <li>JDBC, Java Programming, DSA, MySQL</li>
            <li>HTML, CSS, JavaScript</li>
        </ul>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div id="project-list"></div>
      <ul>
        <li><strong>Tittle :</strong> Arduino-Based Voltage Protection System</li>
        <li><strong>Description:</strong> A prototype of an Arduino-based protection system designed to overcome voltage fluctuations and protect electrical appliances. By monitoring voltage in real-time, the system detects under-voltage and over-voltage conditions and disconnects the load using a relay to prevent damage. The setup includes an Arduino Uno, voltage and current sensors, LCD display, potentiometer, and buzzer. Voltage thresholds are adjustable, and alerts are provided for critical conditions. This cost-effective prototype aims to improve equipment longevity and reliability by automating voltage regulation for low-voltage applications.</li>
        <li><strong>Technologies Used:</strong> Java,MySQL, Arduino uno, HTML, CSS, JavaScript, Potentiometer , INA219 voltage and current sensor , 16*2 lcd , relay. etc. </li> 
        <img src="C:\Users\DELL\AppData\Local\Temp\40eaa91f-f569-48df-b564-8d16a15d47e3_archive (1).zip.7e3\bv6ujrspvrxgtrvjxvuy.jpeg" alt="photo">
        <img src="C:\Users\DELL\AppData\Local\Temp\013fbd3a-d8bc-4222-939e-fe0071539090_archive (1).zip.090\nwvvqjpf6yhaekgrlooe.jpeg" alt=" pic">
    </ul> 
    </section>
 
    <section id="contact">
        <h2>Contact Me</h2>
        <ul>
            <li><a href="Email">Email : jagadeeshyadavalli3@gmail.com</a></li>
            <li><a href="Phone No">Phone No : 7075146474</a></li>
            <li><a href="LinkedIn">LinkeIn : jagadeesh-yadavalli </a></li>
            <li><a href="GitHub">GitHub : Yadavalli-Jagadeesh</a></li>
        </ul>
        </form>
    </section>
