<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vershit-Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Comfortaa:wght@700&family=Sedgwick+Ave+Display&family=Tulpen+One&display=swap" rel="stylesheet">
    <style>
        *{
            margin:0;
            padding:0;
        }
        body{
            background-color: rgb(250, 207, 16);
            color:rgb(168,7,7);
            font-family: 'Comfortaa',cursive;
        }
         nav{
            font-family: 'Tulpen One',cursive;
            display: flex;
            justify-content: space-around;
            align-items: center;
            height:80px;
            background-color: rgb(168, 7, 7);
            color:white;
            font-size: 30px;
        }
        nav ul{
            display:flex;
            justify-content: center;
        }
         nav ul li{
            list-style: none;
            margin:0 23px;
         }
         nav ul li a{
            text-decoration: none;
            color: white;
         }
         nav ul li a:hover{
            color:rgb(250,207,16);
            font-size: 1.5rem;
            font-family:'Sedgwick Ave Display' ;
         }
         .left{
            font-size: 50px;
            font-family: 'Sedgwick Ave Display', cursive;
         }
         .firstSection{
            display:flex;
            justify-content: space-around;
            margin:80px 0;
            
         }
         .firstSection >div{
            width:40%;
         }
         .leftSection{
            font-size: 3rem;
            font-family: 'Comfortaa', cursive;
    
         }
         .leftSection .btn{
            padding:15px;
            font-family:'Comfortaa', cursive ;
            border:2px solid white;
            border-radius: 16px;;
            background-color:rgb(168,7,7);
            color:rgb(243, 245, 242);
            font-size: 20px;
            cursor:pointer
    
         }
         .leftSection .btn:hover{
            background-color: rgb(4, 4, 58);
            font-size: 25px;
         }
         .rightSection img{
            width:100%;
            height: 300px;
         }
         .name{
            color: rgb(240, 44, 9);
         }
         .textgrey{
            color:rgb(240,44,10);
         }
         main hr{
            background: rgb(168,7,7);
            height: 3px;
            margin:60px 10px;
            border:0;
         }
         .secondSection{
            max-width: 90vw;
            margin:auto;
            height: 80vh;
         }
         .secondSection h1{
            font-size: 1.9rem;
            font-family: 'Comfortaa',cursive;
         }
         .secondSection .box{
            display: flex;
            height:2px;
            background:black;
            width:85vw;
            margin:80px 0;
         }
         .secondSection .vertical{
            height:93px;
            width:1px;
            background: black;
            margin:0 100px;
         }
         .image-top{
            width:50px;
            height:50px;
            position: relative;
            top:-55px;
            left:-9px;
         }
         .vertical-title{
            position:relative;
            top:40px;
            left:-10px;
            color:black

         }
         .desc{
            position:relative;
            top:40px;
            left:-10px;
            font-size: 0.7rem;
            color:brown;
            width:150px;
         }
         footer{
            margin:200px 0 0 0;
            background-color:rgb(97,77,7);
            height:222px;
            color:beige;
            font-family: 'Courier New', Courier, monospace;
            
         }
         .footer{
            
            justify-content: space-evenly;
            display: flex;
            padding: 23px 122px;
         }
         .footer ul{
            list-style: none;
         }
         .footer-first{
            font-family: 'Sedgwick Ave Display', cursive;
         }
         .footer-center{
            text-align: center;
            color:grey;
            padding:30px;
         }
    </style>
</head>
<body >
<header >
    <nav>
        <div class="left">Vershit's Portfolio</div>
        <div class="right">
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/">About</a></li>
                <li><a href="/">Projects</a></li>
                <li><a href="/">Education</a></li>
                <li><a href="/">Contact</a></li>
            </ul>
        </div>
    </nav>
</header>
<main>
    <section class="firstSection">
        <div class="leftSection">
            Hi, My name is <span class="name">Vershit</span> and I am 
            <div>a Software Engineering Student</div>
            <span id="element"></span>
            <div class="buttons">
                <button class="btn">Download Resume</button>
                <button class="btn">Visit Github</button>
            </div>
        </div>
        <div class="rightSection">
            <img src="dev.png.png" alt="developer png" >
        </div>
    </section>
    
    <hr>
    <section class="secondSection">
        <span class="textgrey">what I have done so far?</span>
        <h1>Education and Experience</h1>
        <div class="box">
            <div class="vertical">
                <img src="high.png" alt="High School from CBSE board" class="image-top">
                <div class="vertical-title">
                    High-School (2017-2018)
                </div>
                <div class="desc">
                    I have completed my high school from central board of secondary education with 92.8%.
                </div>
            </div>
            <div class="vertical">
                <img src="inter.png" alt="Intermediate from CBSE board" class="image-top">
                <div class="vertical-title">
                    Intermediate (2019-2020)
                </div>
                <div class="desc">
                    I have completed my Intermediate from central board of secondary education with 94.4%.
                </div>
            </div>
            <div class="vertical">
                <img src="btech.png" alt="B.tech from SRMIST" class="image-top">
                <div class="vertical-title">
                    B.Tech(CSE) (2020-present)
                </div>
                <div class="desc">
                    I am pursuing B.Tech in CSE from SRM Institute of Science and Technology with current CGPA of 9.25.
                </div>
            </div>
            <div class="vertical">
                <img src="wellcure.webp" alt="wellcure" class="image-top">
                <div class="vertical-title">
                    Social Media Marketing intern(2021)
                </div>
                <div class="desc">
                    I have completed my Internship from Wellcure where I worked as a Social Media Marketing intern. I learned how 
                    social media can help businesses promote themselves through social media as a tool.
                </div>
            </div>
            <div class="vertical">
                <img src="aicte.webp" alt="wellcure" class="image-top">
                <div class="vertical-title">
                    AIML-intern at EduSkills and AICTE(2023)
                </div>
                <div class="desc">
                    In this 1-2 month of internship, I completed 2 courses provided by AWS(Amazon Web Services) that were 
                    AWS Cloud Foundation course and AWS AIML course.
                </div>
            </div>
            <div class="vertical">
                <img src="graduate.png" alt="graduate" class="image-top">
                <div class="vertical-title">
                    Engineering graduate in 2024
                </div>
            </div>
        </div>
    </section>
</main>
<footer>
    <div class="footer">
    <div class="footer-first">
        <h1>Vershit's Portfolio</h1>
    </div>
    <div class="footer-second"></div>
    <ul>
        <li>Home</li>
        <li>About</li>
        <li>Contact</li>
    </ul>
    <div class="footer-third">
        <ul>
            <li>Education</li>
            <li>Experiences</li>
            <li>Skills</li>
        </ul>
    </div>
    <div class="footer-fourth">
        <ul>
            <li>Projects</li>
            <li>Extra-Curricular</li>
            <li>Volunteer</li>
        </ul>
    </div>
    </div>
    <div class="footer-center">
        www.vershitsportfolio.com|All rights reserved.
    </div>
</footer>
<script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
<script>
    var typed = new Typed('#element', {
      strings: [' learning Data Science,', 'Machine Learning','Blockchain','and much more.',''],
      typeSpeed: 100,
    });
  </script>
</body>
</html>
