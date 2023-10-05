# Portfolio
html, css, javascript
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pankaj Raj</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/e5023e2baf.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/Name Logo.png" alt="" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fa-solid fa-xmark"></i>
                </ul>
                <i class="fa-solid fa-bars"></i>
            </nav>
            <div class="header-text">
                <p>UI/UX Design</p>
                <h1>Hi, I`m <span>Pankaj</span> Raj <br> From India</h1>
            </div>
        </div>
    </div>
    <!--about-->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/Picsart_23-09-24_17-10-17-040.png" alt="">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p>Looking for a job offer in a dynamic firm that values my analytical and technical skills and provides 
                        scope for updating my knowledge, I seek a company that will help me contribute to its
                        development while concurrently aiding my personal growth. My proactive approach to problem solving and commitment learning drives me to excel in delivering efficient and user-centric
                        solution.
                    </p>
                     <div class="tab-title">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Experience</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                     </div>
                      <!--Skills-->
                     <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>UI/UX</span><br>Designing Web </li>
                            <li><span>Web Development</span><br>Web Pages Design/template</li>
                            <li><span>Code</span><br>HTNL, CSS, JS</li>
                            <li><span>Logo Design</span><br>Company logo, Logo Design, Icon Design </li>
                        </ul>
                     </div>
                     <!--Experience-->
                     <div class="tab-contents" id="experience">
                        <ul>
                            <li><span>2021 - Current</span><br>UI/UX Design Training ET Institude</li>
                            <li><span>2019 - 2021</span><br>Team lead at StarApp LLC.</li>
                            <li><span>2017 - 2019</span><br>UI/UX Design Executive at Coin Digital Ltd.</li>
                        </ul>
                     </div>
                      <!--Education-->
                     <div class="tab-contents" id="education">
                        <ul>
                            <li><span>2022-23</span><br>Advanced Diploma in Computer Applications</li>
                            <li><span>2022-25</span><br>B.Sc from M.J.P. ROHELKHAND UNIVERSITY, BAREILLY</li>
                            <li><span>2019-20</span><br>12th from k.v.b.m.i.c. Moradabad</li>
                        </ul>
                     </div>
                </div>
            </div>
        </div>
    </div>
    <!--services-->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="service-list">
                <div>
                    <!--web design-->
                    <i class="fas fa-code"></i>
                    <h2>Web Design</h2>
                    <p>UX designs help synchronise business goals with user needs.
                        A UX designer brings the customer`s perspective into the picture
                        making the product a lot more user friendly and coustomer-oriented.</p>
                        <a href="#">Learn more</a>
                </div>
                <!--ui/ux design-->
                <div>
                    <i class="fab fa-crop-alt"></i>
                    <h2>UI/UX Design</h2>
                    <p>UI/UX designs help synchronise business goals with user needs.
                        A UI/UX designer brings the customer`s perspective into the picture
                        making the product a lot more user friendly and coustomer-oriented.</p>
                        <a href="#">Learn more</a>
                </div>
                <!--app design-->
                <div>
                    <i class="fab fa-app-store"></i>
                    <h2>Logo Design</h2>
                    <p>
                        These high-quality transparent logo PNG images serve as essential assets
                        for creating a strong and recognizable brand presence. Whether you're designing
                        a logo for your business, website, or promotional materials, Logo PNG images offer
                         versatility and visual impact.
                       
                    </p>
                        <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <!---- portfolio ---->
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="images/design.jpg" alt="">
                    <div class="layer">
                        <h3>Social Media App</h3>
                        <p>The aap connect you the talented people aroumd the world.
                            Download it from play store. </p>
                            <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/design5.jpg" alt="">
                    <div class="layer">
                        <h3>Music App</h3>
                        <p>The aap connect you the talented people aroumd the world.
                            Download it from play store. </p>
                            <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/frant.jpg" alt="">
                    <div class="layer">
                        <h3>Online Shopping App</h3>
                        <p>The aap connect you the talented people aroumd the world.
                            Download it from play store. </p>
                            <a href="#"><i class="fas fa-external-link-alt"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn">See more</a>
        </div>
    </div>
<!--contact-->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p> <i class="fas fa-paper-plane"></i> pankajrajmbd54321@gmail.com</p>
                <p> <i class="fas fa-phone-square-alt"></i> +91-8789709088</p>
                <div class="social-icons">
                    <a href="https://www.facebook.com/profile.php?id=100092746149699&mibextid=ZbWKwL"><i class="fab fa-facebook"></i></a>
                    <a href="https://www.threads.net/@iimpankajraj"><i class="fa-brands fa-square-threads"></i></a>
                    <a href="https://instagram.com/iimpankajraj?igshid=YTQwZjQ0NmI0OA=="><i class="fab fa-instagram"></i></a>
                    <a href="https://www.linkedin.com/in/pankaj-raj-vishwakarma-a5b365248?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><i class="fab fa-linkedin"></i></a>
                </div>
                <a href="images/CV1.pdf" download class="btn btn2">Download CV</a>
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="email" name="Email" placeholder="Your Email" required>
                    <textarea name="Massage" rows="6" placeholder="Your Massage"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright:&copy; 2023 Made with <i class="fas fa-heart"></i> by Pankaj Raj</p>
    </div>
</div>





    <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");
        function opentab(tabname){
    for(tablink of tablinks){
        tablink.classList.remove("active-link");
    }
    for(tabcontent of tabcontents){
        tabcontent.classList.remove("active-tab");
    }
    event.currentTarget.classList.add("active-link");
    document.getElementById(tabname).classList.add("active-tab");
}

    </script>




    <script>
        

    
        
    </script>
      <!--contact google sheet--> 
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbw0osKBrGXOMiVJy3yDMc136J39g89un_EO4r52wtM9jwwAoFmvbZABWw8alNoejrgOAA/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")

        form.addEventListener('submit', e =>{
            e.preventDefault()
            fetch(scriptURL, {method: 'POST', body: new FormData(form)})
            .then(Response => {
                msg.innerHTML = "Message sent successfully"
                setTimeout(function(){
                    msg.innerHTML = ""
                },5000)
                form.reset()
            })
            .catch(error => console.error('Error!', error.message))
        })
    </script>
   
</body>
</html>

css code

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap');
*{
    margin: 0;
    padding: 0;
    font-family: 'poppins', sans-serif;
    box-sizing: border-box;
}

html{
    scroll-behavior: smooth;
}

body{
    background: #080808;
    color: #fff;
}
#header{
    width: 100%;
    height: 100vh;
    background-image: url(images/img1.png);
    background-size: cover;
    background-position: center;
}
.container{
    padding: 10px 10%;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}
.logo{
    width: 110px;
}
nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}
nav ul li a{
    color: #fff;
    text-decoration: none;
    font-size: 18px;
    position: relative;
}
nav ul li a::after{
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.5s;
}
nav ul li a:hover::after{
    width: 100%;
    
}
.header-text{
    margin-top: 20%;
    font-size: 30px;
}
.header-text h1{
    font-size: 60px;
    margin-top: 20px;
}
.header-text h1 span{
    color: #ff004f;

}

/*----------about-------*/

#about{
    padding: 80px 0;
    color: #ababab;
}
.row{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}
.about-col-1{
    flex-basis: 35%;
}
.about-col-1 img{
    width: 100%;
    border-radius: 15px;
}
.about-col-2{
    flex-basis: 60%;
}
.sub-title{
    font-size: 60px;
    font-weight: 600;
    color: #fff;
}
.tab-title{
    display: flex;
    margin: 20px 0 40px;
}
.tab-links{
    margin-right: 50px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    position: relative;
}
.tab-links::after{
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;
}
.tab-links.active-link::after{
    width: 50%;

    
}
.tab-contents ul li{
    list-style: none;
    margin: 10px 0;
}
.tab-contents ul li span{
    color: #b54769;
    font-size: 14px;
}
.tab-contents{
    display: none;
}
.tab-contents.active-tab{
    display: block;

}

/*----services---*/
#services{
    padding: 30px 0;

}
.service-list{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.service-list div{
    background: #262626;
    padding: 40px;
    font-size: 13px;
    font-weight: 300;
    border-radius: 10px;
    transition: background 0.5s, transform 0.5s;
}
.service-list div li{
    font-size: 50px;
    margin-bottom: 30px;
}
.service-list div h2{
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;
}
.service-list div a{
    text-decoration: none;
    color: #fff;
    font-size: 12px;
    margin-top: 20px;
    display: inline-block;
}
.service-list div:hover{
    background: #ff004f;
    transform: translateY(-10px);
}

/*   portfolio  */
#portfolio{
    margin: 50px 0;
}
.work-list{
    display: grid;
     grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
     grid-gap: 40px;
     margin-top: 50px;
}
.work{
    border-radius: 10px;
    position: relative;
    overflow: hidden;
}
.work img{
    width: 100%;
    border-radius: 10px;
    display: block;
    transition: transform 0.5s;
}
.layer{
    width: 100%;
    height: 0;
    background: linear-gradient(rgba(0,0,0,0.6), #ff004f);
    border-radius: 10px;
    position: absolute;
    left: 0;
    bottom: 0;
    overflow: hidden;
    display: flex;
    align-items: center;
    align-content: center;
    flex-direction: column;
    padding: 0 40px;
    text-align: center;
    font-size: 14px;
    transition: height 0.5s;

}
.layer h3{
    font-weight: 500;
    margin-bottom: 20px;
}
.layer a{
    margin-top: 20px;
    color: #ff004f;
    text-decoration: none;
    font-size: 18px;
    line-height: 60px;
    background: #fff;
    width: 60px;
    height: 60px;
    border-radius: 50%
}
.work:hover img{
    transform: scale(1.1);
}
.work:hover .layer{
    height: 100%;
}
.btn{
    display: block;
    margin: 50px auto;
    width: fit-content;
    border: 1px solid #ff004f;
    padding: 14px 50px;
    border-radius: 6px;
    text-decoration: none;
    color: #fff;
    transition: background 0.5s;
}
.btn:hover{
    background: #ff004f;
}

/*  contact   */
.contact-left{
    flex-basis: 35%;

}
.contact-right{
    flex-basis: 60%;
}
.contact-left p{
    margin-top: 30px;
}
.contact-left p i{
    color: #ff004f;
    margin-right: 15px;
    font-size: 25px;
}
.social-icons{
    margin-top: 30px;
}
.social-icons a{
    text-decoration: none;
    font-size: 30px;
    margin-right: 15px;
    color: #ff004f;
    display: inline-block;
    transition: transform 0.5s;
}
.social-icons a:hover{
    color: #ff004f;
    transform: translate(-5px);
}
.btn.btn2{
    display: inline-block;
    background: #ff004f;
}
.contact-right form{
    width: 100%;
}
form input, form textarea{
    width: 100%;
    border: 0;
    outline: none;
    background: #262626;
    padding: 15px;
    margin: 15px;
    color: #fff;
    font-size: 18px;
    border-radius: 6px;
}
form .btn2{
    padding: 14px 60px;
    font-size: 18px;
    margin-top: 20px;
    cursor: pointer;

}
.copyright{
    width: 100%;
    text-align: center;
    padding: 25px 0;
    background: #262626;
    margin-top: 20px;
}
.copyright i{
    color: #ff004f;
}

/* css for small screens */
nav .fa-solid{
    display: none;
}


@media only screen and (max-width:600){
    #header{
        background-image: url(images/img1.png);
    }
    .header-text{
        margin-top: 100%;
        font-size: 16px;
    }
    .header-text h1{
        font-size: 30px;
    }
    nav .fa-solid{
        display: block;
        font-size: 25px;
    }
    nav ul{
        background: #ff004f;
        position: fixed;
        top: 0;
        right: -200px;
        width: 200px;
        height: 100vh;
        padding-top: 50px;
    }
    nav ul li{
        display: block;
        margin: 25px;
    }
    nav ul .fa-solid{
        position: absolute;
        top: 25px;
        left: 25px;
        cursor: pointer;
    }
}
































































