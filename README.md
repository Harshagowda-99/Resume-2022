# Resume-2022
 Build Resume Using Css and Html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <!-- Google Fonts--> 
   <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;1,100&
   display=swap" rel="stylesheet">
   <!-- Font Awesome (Icons) -->
<script src="https://kit.fontawesome.com/9c1b8dc99c.js" crossorigin="anonymous"></script>
<!-- Stylesheet-->  
<link rel="stylesheet" href="./style.css" />

<title>Resume</title>
</head>
<body>
    <div class="box">
        <div class="header">
            <div class="header-left">
                <div class="name">
                    <h2 class="first-name">SHYLASHREE</h2>
                    <h2 class="last-name">V</h2>
                </div>
            </div>
            <div class="header-right">
                <div class="email">
                    <p>shylashree@gmail.com</p>
                    <i class="fa-solid fa-envelope"></i>
                </div>
                <div class="linkedin">
                    <p>linkedin.com/in/shyla-shree-42860a185/</p>
                    <i class="fa-brands fa-linkedin"></i>
                </div>
                <div class="github">
                    <p>github.com/Shylasonu</p>
                    <i class="fa-brands fa-github"></i>
                </div>
                <div class="phone">
                    <p>+91-9916280741</p>
                    <i class="fa-solid fa-phone"></i>
                </div>
            </div>
        </div>
        <hr  />
        <div class="objective">
            <div class="obj-head grey">
                <i class="fa-solid fa-bullseye"></i>
                <h2>Objective</h2>
            </div>
            <p>Secure a responsible career opportunity to fully utilize my training and skills, while 
                making a significant contribution to the success of the company and 
                A highly organized and hard-working individual looking for a 
                responsible position to gain practical experience.</p>
        </div>
        <div class="education">
            <div class="ed-head grey">
                <i class="fa-solid fa-school"></i>
                <h2>Education</h2>
            </div>
            <table>
                <tr>
                    <th>Board</th>
                    <th>Institution</th>
                    <th>Year of Passing</th>
                    <th>Percentage</th>
                </tr>
                <tr>
                <td>MCA</td>
                <td>Sambhram Academy of Management Studies</td>
                <td>2021</td>
                <td>74%</td>
                </tr>
                <tr>
                <td>B.Sc</td>
                <td>Govt First Grade College</td>
                <td>2017</td>
                <td>50%</td>
                </tr>
                <tr>
                <td>Intermediate</td>
                <td>Govt PU College</td>
                <td>2013</td>
                <td>54%</td>
                </tr>
                <tr>
                <td>SSLC</td>
                <td>Govt High School</td>
                <td>2011</td>
                <td>56%</td>
                </tr>
            </table>
        </div>
        <div class="skills">
            <div class="skill-head grey">
                <i class="fa-solid fa-list-check"></i>
                <h2>Skills</h2>
            </div>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>Javascript</li>
                <li>React.JS</li>
            </ul>
        </div>
        <div class="achievements">
            <div class="achieve-head grey">
                <i class="fa-solid fa-trophy"></i>
                <h2>Achievements</h2>
            </div>
            <p>Worked with Project as E-commerce sales Forecasting</p>
        </div>
        <div class="Hobbies">
            <div class="hobby-head grey">
                <i class="fa-solid fa-rhombus"></i>
                <h2>Hobbies</h2>
            </div>
            </div>
            <ul>
                <li>Acting</li>
                <li>Listening Music</li>
                <li>Cooking</li>
                </ul>

    </div>



</body>
</html> 
 71  
style.css
@@ -0,0 +1,71 @@
body{
    margin: 0;
    padding: 0;
    background: rgb(14, 13, 13);
    font-family: 'Poppins', sans-serif;
}

h1{
    margin: 0;
    font-weight:400;
}
h2{
    margin: 0;
    font-weight: 400;
    display: inline;
}
.box{
    background: rgb(243, 241, 241);
    width: 50rem;
    padding: 3rem;
    margin: 1rem auto;
    border-radius:0.5rem;
}
.header{
    display: grid;
    grid-template-columns: 40% 60%;
}
.header-left{
    display: grid;
    justify-items: center;
    align-items: center;
    font-size: 2rem;
}
.first-name{
    font-weight: 200;
    margin: 0;
}
.last-name{
    font-weight: 200;
    margin: 0;
}
.header-right{
    width: 100%;
    display: grid;
    justify-items: end;
}
.header-right p{
    display: inline;
}
.icon{
    color: rgb(20, 20, 20);
    font-size: 1.5rem;
    margin-right: 0.5rem;
}
.grey{
    background: rgb(87, 86, 86);
    color: #fff;
    padding: 0.5rem;
    border-radius: 0.3rem;
}
table{
    border: 2px solid #000;
    margin: 1rem 0;
    width: 100%;
    text-align: center;
    border-collapse: collapse
}
td, th{
border: 1px solid #000;
padding: 0.4rem
} 



        <h1> PROJECTS</h1>
        <h2 style="margin-top: 1rem;">Campground Locator 1</h2>
        <h3 style="margin-top: 1rem;margin-bottom: 1rem;">Rock Paper scissor</h3>
        <a href="https://github.com/Harshagowda-99/rock-paper-scissor">GitHub</a>
        <a href="https://rock-scissor-paper-j.netlify.app/">Rock Paper Scissor</a>
         <h2 style="margin-top: 2rem;">Campground Locator 2</h2>
         <h4 style="margin-top: 1rem; margin-bottom: 1rem;">Testmonials gird section</h4>
         <a href=" https://github.com/Harshagowda-99/Testmonials-gird-section"> GitHub</a>
         <a href    =" https://project-testmonial.netlify.app/">Testmonials gird section</a>

