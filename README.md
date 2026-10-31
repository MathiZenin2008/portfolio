# Ex01 Portfolio
## Date:31-10-2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

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
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```

<!DOCTYPE html>
<html>
<head>
    <title>Professional Student Portfolio</title>
</head>

<body bgcolor="#F4F6FA">

    <!-- HEADER -->
    <table width="100%" bgcolor="#14243A" cellpadding="25">
        <tr>
            <td align="center">
                <font color="white" size="6">
                    <b>MATHIYAZHAGAN A</b>
                </font>
                <br><br>
                <font color="#B9C9DD" size="3">
                    ENGINEERING STUDENT | ASPIRING SOFTWARE DEVELOPER
                </font>
                <br><br>
                <font color="white">
                    <a href="#about"><font color="white">About</font></a>
                    &nbsp;&nbsp; | &nbsp;&nbsp;
                    <a href="#education"><font color="white">Education</font></a>
                    &nbsp;&nbsp; | &nbsp;&nbsp;
                    <a href="#skills"><font color="white">Skills</font></a>
                    &nbsp;&nbsp; | &nbsp;&nbsp;
                    <a href="#projects"><font color="white">Projects</font></a>
                    &nbsp;&nbsp; | &nbsp;&nbsp;
                    <a href="#contact"><font color="white">Contact</font></a>
                </font>
            </td>
        </tr>
    </table>

    <br><br>

    <!-- INTRODUCTION -->
    <table width="85%" align="center" bgcolor="white" cellpadding="25">
        <tr>
            <td width="35%" align="center">
                <img src="c:\Users\acer\Pictures\port.jpg"
                     alt="My Profile Picture"
                     width="220"
                     height="250">
            </td>

            <td width="65%">
                <font color="#2878B5" size="3">
                    <b>WELCOME TO MY PORTFOLIO</b>
                </font>

                <h1>
                    <font color="#14243A">
                        Hello, I'm Your Name
                    </font>
                </h1>

                <h3>
                    <font color="#526579">
                        Computer Science / Engineering Student
                    </font>
                </h3>

                <p>
                    I am a passionate student interested in technology,
                    programming, and software development. I enjoy
                    exploring new technologies and building innovative
                    solutions through continuous learning.
                </p>

                <br>

                <a href="#contact">Get In Touch</a>
                &nbsp;&nbsp;&nbsp;
                <a href="#projects">Explore My Work</a>
            </td>
        </tr>
    </table>

    <br><br>

    <!-- ABOUT ME -->
    <table width="85%" align="center" cellpadding="15" bgcolor="white">
        <tr>
            <td>
                <a name="about"></a>
                <font color="#2878B5" size="2">
                    <b>01 / INTRODUCTION</b>
                </font>

                <h2><font color="#14243A">About Me</font></h2>

                <hr color="#DCE3EC">

                <p>
                    I am an enthusiastic engineering student with a
                    strong interest in computer science and emerging
                    technologies. I believe in learning through
                    practical experience and applying technical
                    knowledge to solve real-world problems.
                </p>

                <p>
                    I continuously work on improving my programming,
                    analytical thinking, communication, and
                    problem-solving abilities. My ambition is to
                    become a successful software professional.
                </p>
            </td>
        </tr>
    </table>

    <br>

    <!-- EDUCATION -->
    <table width="85%" align="center" cellpadding="15" bgcolor="white">
        <tr>
            <td>
                <a name="education"></a>
                <font color="#2878B5" size="2">
                    <b>02 / ACADEMIC BACKGROUND</b>
                </font>

                <h2><font color="#14243A">Education</font></h2>

                <hr color="#DCE3EC">

                <table width="100%" border="1" cellpadding="12">
                    <tr bgcolor="#EAF0F7">
                        <th>Qualification</th>
                        <th>Institution</th>
                        <th>Year</th>
                    </tr>

                    <tr>
                        <td>B.E. / B.Tech</td>
                        <td>Your College Name</td>
                        <td>2026 - Present</td>
                    </tr>

                    <tr>
                        <td>Higher Secondary</td>
                        <td>Your School Name</td>
                        <td>2025</td>
                    </tr>

                    <tr>
                        <td>SSLC</td>
                        <td>Your School Name</td>
                        <td>2023</td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>

    <br>

    <!-- TECHNICAL SKILLS -->
    <table width="85%" align="center" cellpadding="15" bgcolor="white">
        <tr>
            <td>
                <a name="skills"></a>
                <font color="#2878B5" size="2">
                    <b>03 / EXPERTISE</b>
                </font>

                <h2><font color="#14243A">Technical Skills</font></h2>

                <hr color="#DCE3EC">

                <table width="100%" cellpadding="10">
                    <tr>
                        <td width="30%"><b>Programming</b></td>
                        <td>C, Python</td>
                    </tr>

                    <tr>
                        <td><b>Web Development</b></td>
                        <td>HTML</td>
                    </tr>

                    <tr>
                        <td><b>Database</b></td>
                        <td>SQL</td>
                    </tr>

                    <tr>
                        <td><b>Tools</b></td>
                        <td>VS Code, GitHub</td>
                    </tr>

                    <tr>
                        <td><b>Soft Skills</b></td>
                        <td>Teamwork, Communication, Problem Solving</td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>

    <br>

    <!-- PROJECTS -->
    <table width="85%" align="center" cellpadding="15" bgcolor="white">
        <tr>
            <td>
                <a name="projects"></a>
                <font color="#2878B5" size="2">
                    <b>04 / MY WORK</b>
                </font>

                <h2><font color="#14243A">Featured Projects</font></h2>

                <hr color="#DCE3EC">

                <h3>01. Personal Portfolio Website</h3>
                <p>
                    Developed a personal portfolio using HTML to
                    present my profile, education, technical skills,
                    and achievements.
                </p>

                <hr color="#E5EAF0">

                <h3>02. Student Management System</h3>
                <p>
                    Designed a student information management system
                    to organize academic records and student details.
                </p>

                <hr color="#E5EAF0">

                <h3>03. Calculator Application</h3>
                <p>
                    Developed a basic calculator to perform
                    arithmetic operations and improve programming
                    fundamentals.
                </p>
            </td>
        </tr>
    </table>

    <br>

    <!-- CERTIFICATIONS -->
    <table width="85%" align="center" cellpadding="15" bgcolor="white">
        <tr>
            <td>
                <font color="#2878B5" size="2">
                    <b>05 / ACHIEVEMENTS</b>
                </font>

                <h2><font color="#14243A">Certifications & Activities</font></h2>

                <hr color="#DCE3EC">

                <ul>
                    <li>Programming and technical course certifications.</li>
                    <li>Participation in technical workshops.</li>
                    <li>Academic project development.</li>
                    <li>Continuous learning and skill development.</li>
                </ul>
            </td>
        </tr>
    </table>

    <br>

    <!-- CONTACT -->
    <table width="85%" align="center" cellpadding="20" bgcolor="white">
        <tr>
            <td>
                <a name="contact"></a>
                <font color="#2878B5" size="2">
                    <b>06 / LET'S CONNECT</b>
                </font>

                <h2><font color="#14243A">Contact Me</font></h2>

                <hr color="#DCE3EC">

                <p><b>Email:</b> yourname@gmail.com</p>

                <p><b>Phone:</b> +91 XXXXXXXXXX</p>

                <p><b>Location:</b> Chennai, Tamil Nadu, India</p>

                <p>
                    <b>LinkedIn:</b>
                    <a href="https://www.linkedin.com/">
                        LinkedIn Profile
                    </a>
                </p>

                <p>
                    <b>GitHub:</b>
                    <a href="https://github.com/">
                        GitHub Profile
                    </a>
                </p>
            </td>
        </tr>
    </table>

    <br><br>

    <!-- FOOTER -->
    <table width="100%" bgcolor="#14243A" cellpadding="20">
        <tr>
            <td align="center">
                <font color="white" size="3">
                    <b>YOUR NAME</b>
                </font>

                <br><br>

                <font color="#B9C9DD" size="2">
                    Building Skills. Creating Opportunities. Shaping the Future.
                </font>

                <br><br>

                <font color="white" size="2">
                    © 2026 All Rights Reserved.
                </font>
            </td>
        </tr>
    </table>

</body>
</html>

```

## OUTPUT

![alt text](port.jpg)
## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
