<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>musthafa-website</title>
    <!-- link to loader css file  -->
    <link rel="stylesheet" href="./Css/loader.css">
    <link rel="stylesheet" href="./Css/style.css">
    <!-- link to dataaos cdn for scroll animation -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <!-- link to css file -->
    <link rel="stylesheet" href="./Css/style.css">
    <!-- Typed Js Cdn For Typing Animation  -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"></script>
    <!-- Iconify Cdn For Icons  -->
    <script src="https://code.iconify.design/2/2.0.4/iconify.min.js"></script>
</head>
<body>
    <div class="onloader" id="preloader">
        <div class="cup" id="onload"></div>
        <div class="loadertext" id="loadertext">
            <h1 id="preload-title" class="loading">
                <div class="loading-text">
                    <span class="loading-text-words">L</span>
                    <span class="loading-text-words">O</span>
                    <span class="loading-text-words">A</span>
                    <span class="loading-text-words">D</span>
                    <span class="loading-text-words">I</span>
                    <span class="loading-text-words">N</span>
                    <span class="loading-text-words">G</span>
                </div>
            </h1>
        </div>
    </div>
    <!-- Header Section Starts Here  -->
    <header class="navbar">
        <div class="nav-content">
            <div class="brand">
                <h1 class="logo"><span>{</span>Musthafa<span>}</span></span></h1>
            </div>
            <ul class="navlinks" id="navlinks">
                <li><a href="#home" class="active">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
        <div class="theme">
            <img src="./img/sun.png" alt="" id="theme-icon">
        </div>
        <ul class="foonavlinks" id="foonavlinks">
            <li><a href="#home" class="active"><span class="iconify" data-icon="heroicons-outline:home"></span></a></li>
            <li><a href="#about"><span class="iconify" data-icon="bi:person-lines-fill" ></span></a></li>
            <li><a href="#skills"><span class="iconify" data-icon="carbon:machine-learning-model"></span></a></li>
            <li><a href="#contact"><span class="iconify" data-icon="fluent:chat-mail-20-filled"></span></a></li>
        </ul>
    </header>
    <!-- Main Section Starts Here  -->
    <main>
        <section class="hero" id="home">
            <div class="main-container" data-aos="fade-right" data-aos-offset="300" data-aos-easing="ease-in-sine">
                <h3>hello world!!</h3>
                <h1>I'm <span>Musthafa</span></h1>
                <p><span class="typing"></span></p>
                <div class="btn">
                    <a href="http://wa.me/+91 80564 34813" target="_blank"><button>Hire Me</button></a>
                    <a href="#contact"><button>Contact Me</button></a>
                </div>
            </div>
        </section>
        <section class="about-widget" id="about">
                <div class="aboutimg" data-aos="zoom-in-right">
                    <img class="aboutlogo" src="./Img/musthafa.jpg" alt="aboutlogo">
                </div>
                <div class="about-des" data-aos="zoom-in-left">
                    <h1 class="abouttitle">About Me</h1>
                    <p class="aboutcont">I am dedicated with school and sports, Experienced Boxer with a strong sense of discipline. A strong ethic and excellent time management and people skills. Goal- Oriented and results-focused individual who has achieved success both in the classroom and outside of class.</p>
                    <p class="abouttagword">Find My Content On <a href="https://uwais-0x.github.io/uwais0x/" target="_blank">website</a></p>
                </div>
        </section>
        <section class="skills" id="skills">
            <h1 class="skilltitle">My Skills</h1>
             <div class="skill-container">
                 <div class="box1" data-aos="fade-up-right" data-aos-offset="100" data-aos-easing="ease-in-sine">
                     <div class="percent">
                        <svg>
                            <circle cx="70" cy="70" r="70"></circle>
                            <circle cx="70" cy="70" r="70"></circle>
                        </svg>
                        <div class="number">
                            <h2>95<span>%</span></h2>
                        </div>a
                     </div>
                     <h2 class="text">BOXING</h2>
                 </div>
                 <div class="box2" data-aos="fade-down-right" data-aos-offset="100" data-aos-easing="ease-in-sine">
                    <div class="percent">
                       <svg>
                           <circle cx="70" cy="70" r="70"></circle>
                           <circle cx="70" cy="70" r="70"></circle>
                       </svg>
                       <div class="number">
                           <h2>90<span>%</span></h2>
                       </div>
                    </div>
                    <h2 class="text">SELAMBAM</h2>
                </div>
                <div class="box3" data-aos="fade-up-left" data-aos-offset="100" data-aos-easing="ease-in-sine">
                    <div class="percent">
                       <svg>
                           <circle cx="70" cy="70" r="70"></circle>
                           <circle cx="70" cy="70" r="70"></circle>
                       </svg>
                       <div class="number">
                           <h2>80<span>%</span></h2>
                       </div>
                    </div>
                    <h2 class="text">KABADI</h2>
                </div>
                <div class="box3" data-aos="fade-down-left" data-aos-offset="100" data-aos-easing="ease-in-sine">
                    <div class="percent">
                       <svg>
                           <circle cx="70" cy="70" r="70"></circle>
                           <circle cx="70" cy="70" r="70"></circle>
                       </svg>
                       <div class="number">
                           <h2>90<span>%</span></h2>
                        </div>
                    </div>
                    <h2 class="text">COOKING</h2>
                </div>
                <div class="box3" data-aos="fade-up-right" data-aos-offset="100" data-aos-easing="ease-in-sine">
                    <div class="percent">
                       <svg>
                           <circle cx="70" cy="70" r="70"></circle>
                           <circle cx="70" cy="70" r="70"></circle>
                       </svg>
                       <div class="number">
                           <h2>80<span>%</span></h2>
                       </div>
                    </div>
                    <h2 class="text">VOLLEYBALL</h2>
                </div>
                <div class="box4" data-aos="fade-down-right" data-aos-offset="100" data-aos-easing="ease-in-sine">
                    <div class="percent">
                       <svg>
                           <circle cx="70" cy="70" r="70"></circle>
                           <circle cx="70" cy="70" r="70"></circle>
                       </svg>
                       <div class="number">
                           <h2>60<span>%</span></h2>
                       </div>
                    </div>
                    <h2 class="text">THROWBALL</h2>
                </div>
                <div class="box4" data-aos="fade-up-left" data-aos-offset="100" data-aos-easing="ease-in-sine">
                    <div class="percent">
                       <svg>
                           <circle cx="70" cy="70" r="70"></circle>
                           <circle cx="70" cy="70" r="70"></circle>
                       </svg>
                       <div class="number">
                           <h2>60<span>%</span></h2>
                       </div>
                    </div>
                    <h2 class="text">TENNIS</h2>
                </div>
                <div class="box5" data-aos="fade-down-left" data-aos-offset="100" data-aos-easing="ease-in-sine">
                    <div class="percent">
                       <svg>
                           <circle cx="70" cy="70" r="70"></circle>
                           <circle cx="70" cy="70" r="70"></circle>
                       </svg>
                       <div class="number">
                           <h2>15<span>%</span></h2>
                       </div>
                    </div>
                    <h2 class="text">CARROM</h2>
                </div>
             </div>
        </section>
        <section class="contact" id="contact">
            <h1 class="contacttitle">Contact Me</h1>
            <div class="contact-container">
                <div class="contactdes">
                    <form action="=https://formspree.io/f/xwkdwpbl" class="contactform" method="POST" id="my-form">
                        <input type="text" name="name" placeholder="Your Name" id="NAME" required>
                        <input type="email" placeholder="Your Email" name="mail from" id="EMAIL" required>
                        <textarea cols="32" rows="7" placeholder="Your Message" name="message" id="MESSAGE" required=""></textarea>
                        <p id="form-status" style="display: none;border: 1px solid black;padding: 5px 10px;margin: 10px 0px;background: black; box-shadow: 0 0 10px #E1E8EB;"></p>
                        <button type="submit" id="submitBtn">Send Message</button>
                    </form>
                </div>
                <div class="contactimg">
                    <h1>Get In Touch</h1>
                    <p class="description">Contact Me  Get in Touch with me. Message me for your Works & Doubts</p>
                    <div class="details">
                       <div class="row1">
                            <div class="column1">
                                <span class="iconify" data-icon="raphael:user" style="color: #E1E8EB;"></span>
                            </div>
                            <div class="column2">
                                <label><b>Name</b></label>
                                <p>Musthafa</p>
                            </div>
                       </div>
                        <div class="row2">
                            <div class="column3">
                                <span class="iconify" data-icon="carbon:location-person-filled" style="color: #E1E8EB;"></span>
                            </div>
                            <div class="column4">
                                <label><b>Address</b></label>
                                <p>Tenkasi, TamilNadu</p>
                            </div>
                        </div>
                        <div class="row3">
                            <div class="column5">
                                <span class="iconify" data-icon="fluent:mail-open-person-16-filled" style="color: #E1E8EB;"></span>
                            </div>
                            <div class="column6">
                                <label><b>Email</b></label>
                                <a href="musthaafaaa99@gmail.com"></a><p>musthaafaaa99@gmail.com</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>
    <!-- Footer Section Starts Here  -->
    <footer>
        <div class="copyright">
            <span>Made By<a href="https://varshafathima.github.io"> varsha</a></span>
        </div>
    </footer>
    <!-- link to js file -->
    <script src="./css/script.js"></script>
    <script src="themechanger.js"></script>
    <!-- link to dataaos js file -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init();
    </script>
</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Baloo+2:wght@400;500;600;700;800&display=swap');
/* Color Root Variables */
:root {
  --primary-color: #E1E8EB;
  --secondary-color: red;
  --bg-color: #343A40;
  --txt-color:#3D3D3D; 
  --main-color: #7952B3;
  --nav-color: black;
}
  .onloader {
    position: fixed;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    display: flex;
    width: 100%;
    height: 100%;
    background: var(--nav-color);
    z-index: 6;
    color: var(--primary-color);
  }
  .loadertext {
    position: relative;
    top: 30%;
    font-family: 'Baloo 2', cursive;
  }
  #preload-title {
    font-size: 30px;
  }
  #preload-des {
    font-size: 20px;
    text-align: center;
  }

  .loading {
    position: relative;
  }
  
  .loading-text {
    position: relative;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    margin: auto;
    text-align: center;
  }
  .loading-text span {
    display: inline-block;
    margin: 0 5px;
    color: var(--secondary-color);
  }
  .loading-text span:nth-child(1) {
    filter: blur(0px);
    -webkit-animation: blur-text 1.5s 0s infinite linear alternate;
            animation: blur-text 1.5s 0s infinite linear alternate;
  }
  .loading-text span:nth-child(2) {
    filter: blur(0px);
    -webkit-animation: blur-text 1.5s 0.2s infinite linear alternate;
            animation: blur-text 1.5s 0.2s infinite linear alternate;
  }
  .loading-text span:nth-child(3) {
    filter: blur(0px);
    -webkit-animation: blur-text 1.5s 0.4s infinite linear alternate;
            animation: blur-text 1.5s 0.4s infinite linear alternate;
  }
  .loading-text span:nth-child(4) {
    filter: blur(0px);
    -webkit-animation: blur-text 1.5s 0.6s infinite linear alternate;
            animation: blur-text 1.5s 0.6s infinite linear alternate;
  }
  .loading-text span:nth-child(5) {
    filter: blur(0px);
    -webkit-animation: blur-text 1.5s 0.8s infinite linear alternate;
            animation: blur-text 1.5s 0.8s infinite linear alternate;
  }
  .loading-text span:nth-child(6) {
    filter: blur(0px);
    -webkit-animation: blur-text 1.5s 1s infinite linear alternate;
            animation: blur-text 1.5s 1s infinite linear alternate;
  }
  .loading-text span:nth-child(7) {
    filter: blur(0px);
    -webkit-animation: blur-text 1.5s 1.2s infinite linear alternate;
            animation: blur-text 1.5s 1.2s infinite linear alternate;
  }
  
  @-webkit-keyframes blur-text {
    0% {
      filter: blur(0px);
    }
    100% {
      filter: blur(4px);
    }
  }
  
  @keyframes blur-text {
    0% {
      filter: blur(0px);
    }
    100% {
      filter: blur(4px);
    }
  }

  @keyframes filling {
    50% {background-position: 3000px 0px;}
    100% {background-position: 6000px 350px;}
  }

/* For Mobile Device */
@media only screen and (max-width: 425px) {
  .cup {
    width: 120px;
    height: 160px;
  }
  .cup:before {
    width: 30px;
    height: 60px;
    right: -48px;
    border-top-right-radius: 35px;
    border-bottom-right-radius: 35px;
  }
  #preload-title {
    font-size: 25px;
  }
  #preload-des {
    font-size: 18px;
    text-align: center;
  }
}
// Preloader Animation Script
let cup = "cup";
// window.addEventListener("load",function () {
//     document.getElementById("onload").classList.add(cup);
//     setTimeout(() => {
//                 document.getElementById("onload").classList.remove(cup);
//                 document.getElementById("preloader").classList.remove("onloader");
//             },5000)
// })
let loadertext = document.getElementById("loadertext");
let pretitle = document.getElementById("preload-title");
let predes = document.getElementById("preload-des");
window.onload = () => {
    document.getElementById("onload").classList.add(cup);
    setTimeout(() => {
        document.getElementById("onload").classList.remove(cup);
        document.getElementById("preloader").classList.remove("onloader");
        pretitle.style.display = "none";
        predes.style.display = "none";
        loadertext.style.display = "none";
    },5000)
}

// Sticky Scroll Bar Script

var className = "sticky";
var scrollTrigger = 60;

window.onscroll = function() {
    if (window.scrollY >= scrollTrigger || window.pageYOffset >= scrollTrigger) {
        document.querySelector(".navbar").classList.add(className);
    }else {
        document.querySelector(".navbar").classList.remove(className);
    }
}

// Active Navbar Script

var sections = document.querySelectorAll('section');

onscroll = function() {
	var scrollPosition = document.documentElement.scrollTop;

	sections.forEach( section => {
		if(scrollPosition >= section.offsetTop - section.offsetHeight*0.25 && scrollPosition < section.offsetTop + section.offsetHeight - section.offsetHeight*0.25) {
			var currentId = section.attributes.id.value;
			removeAllActiveClasses();
			addActiveClass(currentId);
			removeAllFootClasses();
			addFootClass(currentId);
		}
	});
};

var removeAllActiveClasses = function() {
	document.querySelectorAll('#navlinks a').forEach((ele) => {
		ele.classList.remove("active");
	});
};

var removeAllFootClasses = function() {
	document.querySelectorAll('#foonavlinks a').forEach((el) => {
		el.classList.remove("active");
	});
};

var addActiveClass = function(id) {
	var selector1 = `#navlinks a[href="#${id}"]`;
	document.querySelector(selector1).classList.add("active");
}

var addFootClass = function(id) {
	var selector2 = `#foonavlinks a[href="#${id}"]`;
	document.querySelector(selector2).classList.add("active");
}

// Typing Effect Animation Script

var typed = new Typed(".typing", {
	strings: ["Boxer", "Kabbadi player", "chef", "selambam player"],
	typeSpeed: 100,
	backSpeed: 40,
	loop: true
});

// Contact Form Validation Script

var form = document.getElementById("my-form");
async function handleSubmit(event) {
	var emailRegEx = /^(([^<>()[\]\\.,;:\s@\"]+(\.[^<>()[\]\\.,;:\s@\"]+)*)|(\".+\"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;

	event.preventDefault();
	document.querySelector("#submitBtn").innerHTML = "SENDING ...";
	if (document.querySelector("#NAME").value.trim().length == 0) {
		isMessage("Please Fill out your Name", "#E1E8EB");
	} else if (!emailRegEx.test(document.querySelector("#EMAIL").value)) {
		isMessage("Please Check your Email Address", "#E1E8EB");
	} else if (document.querySelector("#MESSAGE").value.trim().length == 0) {
		isMessage("Please Fill out your Message", "#E1E8EB");
	} else {
		var data = new FormData(event.target);
		fetch(event.target.action, {
			method: form.method,
			body: data,
			headers: {
				Accept: "application/json",
			},
		})
			.then((response) => {
				isMessage("Thanks for your submission!", "#17ad11");
				form.reset();
			})
			.catch((error) => {
				isMessage(
					"Oops! There was a problem submitting your form",
					"red"
				);
			});
	}
}
function isMessage(Value, Color) {
	var status = document.querySelector("#form-status");
	status.innerHTML = Value;
	status.style.display = "block";
	status.style.color = Color;
	document.querySelector("#submitBtn").innerHTML = "Send";
}
form.addEventListener("submit", handleSubmit);
@import url('https://fonts.googleapis.com/css2?family=Baloo+2:wght@400;500;600;700;800&display=swap');
/* Reseting Page Defaults */
* {
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
    font-family: 'Baloo 2', cursive;
}
/* Color Root Variables */
:root {
    --primary-color: #E1E8EB;
    --secondary-color: red;
    --bg-color: #343A40;
    --txt-color:#3D3D3D; 
    --main-color: #7952B3;
    --nav-color: black;
}

/* HTML Scroll Smoothness */
html {
    scroll-behavior: smooth;
}

body {
    overflow-x: hidden;
}

/* All Similar Content Styling  */
a {
    text-decoration: none;
}
/* For Selection Portion  */
::selection {
    color: var(--nav-color);
    background: var(--secondary-color);
}
/* Header Section Starts Here  */
.navbar {
    position: fixed;
    display: flex;
    flex-direction: row;
    height: 12vh;
    width: 100%;
    justify-content: space-between;
    z-index: 3;
    user-select: none;
    background: var(--nav-color);
}
.navbar .nav-content {
    display: flex;
    width: 95%;
    justify-content: space-between;
}
.navbar .brand {
    display: flex;
    align-items: center;
    height: 12vh;
    padding-left: 50px;
    color: var(--primary-color);
}
.navbar .brand span {
    color: var(--secondary-color);
}
.navbar .navlinks {
    list-style-type: none;
    display: flex;
    width: 50vw;
    align-items: center;
    justify-content: space-around;
}
.navbar .navlinks a {
    position: relative;
    color: var(--primary-color);
    text-decoration: none;
    font-size: 18px;
    font-weight: 550;
}
.navbar .navlinks li:hover a{
    color: var(--secondary-color);
}
.navbar .navlinks a.active {
    color: var(--secondary-color);
}
.navbar .navlinks a.active:after {
    content: "";
    height: 2px;
    width: 100%;
    position: absolute;
    background-color: var(--secondary-color);
    left: 0px;
    top: 25px;
}
.navbar .foonavlinks {
    position: absolute;
    display: none;
}
/* Theme Changer Starts Here */
.navbar .theme {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 5%;
}
.navbar #theme-icon {
    height: 25px;
    cursor: pointer;
}
/* Main Content Starts Here  */
/* Home Section Starts Here  */
.hero {
    height: 100vh;
    width: 100%;
    position: relative;
    background: transparent;
    display: flex;
    align-items: center;
    justify-content: center;
}
.hero::before {
    content: "";
    position: absolute;
    background: url(https://images.unsplash.com/photo-1603366615917-1fa6dad5c4fa?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80);
    left: 0;
    height: 100vh;
    width: 100%;
    z-index: -1;    
    background-size: cover;
}
.hero .main-container {
    height: 400px;
    width: 400px;
    color: var(--primary-color);
    margin-left: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.hero .main-container h3 {
    color: var(--txt-color);
    font-size: 35px;
}
.hero .main-container h1 {
    color: var(--txt-color);
    font-size: 55px;
}
.hero .main-container span {
    color: var(--primary-color);
}
.hero .main-container .btn {
    display: flex;
    justify-content: space-around;
    width: 95%;
    padding-top: 20px;
}
.hero .main-container button {
    padding: 10px 10px;
    margin: 0px 10px;
    color: var(--primary-color);
    font-size: 20px;
    font-weight: 550;
    border-radius: 6px;
    background-color: transparent;
    box-shadow: 0 0 10px var(--primary-color);    
    border: 1px solid transparent;
}
.hero .main-container button:hover {
    box-shadow: 0 0 0px;    
    border: 1px solid var(--secondary-color);
    background: var(--secondary-color);
    color: var(--primary-color);
}
.hero .main-container p {
    font-size: 28px;
    font-weight: 600;
}
.hero .main-container .typing {
    color: var(--secondary-color);
}
.hero .main-container p span {
    color: var(--secondary-color);
}
/* About Section Starts Here  */
.about-widget {
    padding: 80px 0px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 80vh;
    width: 100%;
    background: var(--nav-color);
}
.about-container {
    display: flex;
    justify-content: space-evenly;
}
.aboutimg {
    height: 350px;
    width: 350px;
    user-select: none;
}
.aboutimg .aboutlogo {
    height: 100%;
    width: 100%;
}
.about-des {
    height: 350px;
    width: 650px;
}
.about-des .abouttitle {
    color: var(--primary-color);
    font-size: 35px;
    text-align: center;
}
.about-des .aboutcont {
    font-size: 20px;
    padding: 30px 0px;
    color: var(--txt-color);
}
.about-des .abouttagword {
    font-size: 20px;
    float: right;
    color: var(--primary-color);
}
.about-des .abouttagword a {
    color: var(--secondary-color);
    font-weight: 550;
}
.about-des .abouttagword a:hover {
    color: var(--txt-color);
}
/* Skills Section Starts Here  */
.skills {
    height: 150vh;
    width: 100%;
    background: var(--nav-color);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.skills .skilltitle {
    color: var(--primary-color);
    font-size: 35px;
    position: relative;
    top: 50px;
    text-align: center;
}
.skills .skill-container {
    height: 80%;
    width: 80%;
    margin: 100px 0px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
}
/* box1 starts here */
.skills .box1 {
    position: relative;
    margin:30px 0px;
    width: 250px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color: var(--primary-color);
    background: var(--nav-color);
    /* box-shadow: 0 30px 60px rgba(0,0,0,.2); */
    box-shadow: 0 0 10px var(--primary-color);    
    transition: 0.3s;
    border-radius: 10px;
}
.skills .box1:hover {
    transform: translateY(20px);
    /* box-shadow: 0 15px 35px rgba(0,0,0,.5); */
    box-shadow: 0 0 0px;    
}
.box1 .percent {
    position: relative;
    color: var(--primary-color);
    height: 150px;
    width: 150px;
}
.box1 .percent svg {
    position: relative;
    width: 150px;
    height: 150px;
}
.box1 .percent svg circle {
    width: 150px;
    height: 150px;
    fill: none;
    stroke-width: 10;
    stroke-dasharray: 440;
    stroke-dashoffset: 440;
    stroke-linecap: round;
    stroke-dashoffset: 0;
    stroke: var(--secondary-color);
    transform: translate(5px, 5px);
}
.box1 .percent svg circle:nth-child(1) {
    stroke: var(--primary-color);
}
.box1 .percent svg circle:nth-child(2) {
    stroke-dashoffset: calc(440 - (440 * 95) / 100);
    stroke: var(--secondary-color);
    opacity: 0.7;
}
.box1 .percent .number {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.box1 .percent .number h2 {
    font-size: 48px;
}
.box1:hover .percent .number h2 {
    font-size: 60px;
}
.box1:hover .percent svg circle:nth-child(2) {
    opacity: 1;
}
.box1 .percent .number h2 span{
    font-size: 24px;
}
.box1 .text {
    padding: 10px 0 0;
    font-weight: 700;
    letter-spacing: 1px;
}

/* box2 starts here*/
.skills .box2 {
    position: relative;
    width: 250px;
    margin:30px 0px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color: var(--primary-color);
    background: var(--nav-color);
    box-shadow: 0 0 10px var(--primary-color);
    /* background: var(--primary-color); */
    /* box-shadow: 0 30px 60px rgba(0,0,0,.2); */
    transition: 0.3s;
    border-radius: 10px;
}
.skills .box2:hover {
    transform: translateY(20px);
    /* box-shadow: 0 15px 35px rgba(0,0,0,.5); */
    box-shadow: 0 0 0px;
}
.box2 .percent {
    position: relative;
    height: 150px;
    width: 150px;
}
.box2 .percent svg {
    position: relative;
    width: 150px;
    height: 150px;
}
.box2 .percent svg circle {
    width: 150px;
    height: 150px;
    fill: none;
    stroke-width: 10;
    stroke-dasharray: 440;
    stroke-dashoffset: 440;
    stroke-linecap: round;
    stroke: var(--secondary-color);
    transform: translate(5px, 5px);
}
.box2 .percent svg circle:nth-child(1) {
    stroke-dashoffset: 0;
    /* stroke: #f3f3f3; */
    stroke: var(--primary-color);
}
.box2 .percent svg circle:nth-child(2) {
    stroke-dashoffset: calc(440 - (440 * 90) / 100);
    stroke: var(--secondary-color);
    opacity: 0.7;
}
.box2 .percent .number {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.box2 .percent .number h2 {
    font-size: 48px;
}
.box2:hover .percent .number h2 {
    font-size: 60px;
}
.box2:hover .percent svg circle:nth-child(2) {
    opacity: 1;
}
.box2 .percent .number h2 span{
    font-size: 24px;
}
.box2 .text {
    padding: 10px 0 0;
    font-weight: 700;
    letter-spacing: 1px;
}

/* box3 starts here*/
.skills .box3 {
    position: relative;
    margin: 30px 0px;
    width: 250px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color: var(--primary-color);
    background: var(--nav-color);
    box-shadow: 0 0 10px var(--primary-color);
    /* background: var(--primary-color); */
    /* box-shadow: 0 30px 60px rgba(0,0,0,.2); */
    transition: 0.3s;
    border-radius: 10px;
}
.skills .box3:hover {
    transform: translateY(20px);
    /* box-shadow: 0 15px 35px rgba(0,0,0,.5); */
    box-shadow: 0 0 0px;
}
.box3 .percent {
    position: relative;
    height: 150px;
    width: 150px;
}
.box3 .percent svg {
    position: relative;
    width: 150px;
    height: 150px;
}
.box3 .percent svg circle {
    width: 150px;
    height: 150px;
    fill: none;
    stroke-width: 10;
    stroke-dasharray: 440;
    stroke-dashoffset: 440;
    stroke-linecap: round;
    stroke: var(--secondary-color);
    transform: translate(5px, 5px);
}
.box3 .percent svg circle:nth-child(1) {
    stroke-dashoffset: 0;
    /* stroke: #f3f3f3; */
    stroke: var(--primary-color);
}
.box3 .percent svg circle:nth-child(2) {
    stroke-dashoffset: calc(440 - (440 * 80) / 100);
    stroke: var(--secondary-color);
    opacity: 0.7;
}
.box3 .percent .number {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.box3 .percent .number h2 {
    font-size: 48px;
}
.box3:hover .percent .number h2 {
    font-size: 60px;
}
.box3:hover .percent svg circle:nth-child(2) {
    opacity: 1;
}
.box3 .percent .number h2 span{
    font-size: 24px;
}
.box3 .text {
    padding: 10px 0 0;
    font-weight: 700;
    letter-spacing: 1px;
}
/* box4 starts here*/
.skills .box4 {
    position: relative;
    margin:30px 0px;
    width: 250px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color: var(--primary-color);
    background: var(--nav-color);
    box-shadow: 0 0 10px var(--primary-color);
    /* background: var(--primary-color); */
    /* box-shadow: 0 30px 60px rgba(0,0,0,.2); */
    transition: 0.3s;
    border-radius: 10px;
}
.skills .box4:hover {
    transform: translateY(20px);
    /* box-shadow: 0 15px 35px rgba(0,0,0,.5); */
    box-shadow: 0 0 0px;
}
.box4 .percent {
    position: relative;
    height: 150px;
    width: 150px;
}
.box4 .percent svg {
    position: relative;
    width: 150px;
    height: 150px;
}
.box4 .percent svg circle {
    width: 150px;
    height: 150px;
    fill: none;
    stroke-width: 10;
    stroke-dasharray: 440;
    stroke-dashoffset: 440;
    stroke-linecap: round;
    stroke: var(--secondary-color);
    transform: translate(5px, 5px);
}
.box4 .percent svg circle:nth-child(1) {
    stroke-dashoffset: 0;
    /* stroke: #f3f3f3; */
    stroke: var(--primary-color);
}
.box4 .percent svg circle:nth-child(2) {
    stroke-dashoffset: calc(440 - (440 * 60) / 100);
    stroke: var(--secondary-color);
    opacity: 0.7;
}
.box4 .percent .number {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.box4 .percent .number h2 {
    font-size: 48px;
}
.box4:hover .percent .number h2 {
    font-size: 60px;
}
.box4:hover .percent svg circle:nth-child(2) {
    opacity: 1;
}
.box4 .percent .number h2 span{
    font-size: 24px;
}
.box4 .text {
    padding: 10px 0 0;
    font-weight: 700;
    letter-spacing: 1px;
}
/* box5 starts here*/
.skills .box5 {
    position: relative;
    margin:30px 0px;
    width: 250px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color: var(--primary-color);
    background: var(--nav-color);
    box-shadow: 0 0 10px var(--primary-color);
    /* background: var(--primary-color); */
    /* box-shadow: 0 30px 60px rgba(0,0,0,.2); */
    transition: 0.3s;
    border-radius: 10px;
}
.skills .box5:hover {
    transform: translateY(20px);
    box-shadow: 0 0 0px;
    /* box-shadow: 0 15px 35px rgba(0,0,0,.5); */
}
.box5 .percent {
    position: relative;
    height: 150px;
    width: 150px;
}
.box5 .percent svg {
    position: relative;
    width: 150px;
    height: 150px;
}
.box5 .percent svg circle {
    width: 150px;
    height: 150px;
    fill: none;
    stroke-width: 10;
    stroke-dasharray: 440;
    stroke-dashoffset: 440;
    stroke-linecap: round;
    stroke: var(--secondary-color);
    transform: translate(5px, 5px);
}
.box5 .percent svg circle:nth-child(1) {
    stroke-dashoffset: 0;
    /* stroke: #f3f3f3; */
    stroke: var(--primary-color);
}
.box5 .percent svg circle:nth-child(2) {
    stroke-dashoffset: calc(440 - (440 * 15) / 100);
    stroke: var(--secondary-color);
    opacity: 0.7;
}
.box5 .percent .number {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.box5 .percent .number h2 {
    font-size: 48px;
}
.box5:hover .percent .number h2 {
    font-size: 60px;
}
.box5:hover .percent svg circle:nth-child(2) {
    opacity: 1;
}
.box5 .percent .number h2 span{
    font-size: 24px;
}
.box5 .text {
    padding: 10px 0 0;
    font-weight: 700;
    letter-spacing: 1px;
}

/* Contact Section Starts Here  */
.contact {
    padding: 80px 0px;
    height: 80vh;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: var(--nav-color); 
}
.contact .contacttitle {
    color: var(--primary-color);
    font-size: 35px;
    position: relative;
    bottom: 20px;
    text-align: center;
}
.contact .contact-container {
    display: flex;
    width: 90%;
    flex-direction: row;
}
.contactdes {
    width: 60%;
    padding: 10px 0px;
}
.contactform {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.contactdes input {
    height: 30px;
    width: 50%;
    margin-bottom: 10px;
    font-size: 16px;
    padding: 15px 10px;
    color: var(--nav-color);
}
.contactdes input:focus {
    outline: none;
}
.contactdes textarea {
    font-size: 16px;
    color: var(--nav-color);
    padding: 10px 10px;
}
.contactdes textarea:focus {
    outline: none;
}
.contactdes button {
    font-size: 16px;
    padding: 4px 10px;
    margin: 10px 0px;
    color: var(--primary-color);
    background-color: var(--nav-color);
    border: 1px solid var(--nav-color);
    box-shadow: 0 0 10px var(--primary-color);    
    border-radius: 4px;
    font-weight: 550;
}
.contactdes button:hover {
    box-shadow: 0 0 0px;    
    background-color: var(--secondary-color);
    border: 1px solid var(--secondary-color);
    border-radius: 4px;
}
.contactimg {
    height: 100%;
    width: 30%;
    color: var(--primary-color);
}
.contactimg .description {
    font-size: 18px;
    color: var(--txt-color);
}
.contactimg .contactbrand {
    height: 100%;
    width: 100%;
}
.contactimg .details {
    padding: 10px 10px;
    color: var(--txt-color);
}
.contactimg .details label {
    color: var(--primary-color);
}
.contactimg .row1 {
    display: flex;
    flex-direction: row;
}
.contactimg .column1 {
    font-size: 50px;
    margin-right: 20px;
}
.contactimg .row1:hover .column1 .iconify {
    color: var(--secondary-color) !important;
}
.contactimg .row2 {
    display: flex;
    flex-direction: row;
}
.contactimg .column3 {
    font-size: 50px;
    margin-right: 20px;
}
.contactimg .row2:hover .column3 .iconify {
    color: var(--secondary-color) !important;
}
.contactimg .row3 {
    display: flex;
    flex-direction: row;
}
.contactimg .column5 {
    font-size: 50px;
    margin-right: 20px;
}
.contactimg .row3:hover .column5 .iconify {
    color: var(--secondary-color) !important;
}
/* Footer Section Starts Here */
footer {
    height: 5vh;
    background: var(--nav-color);
    color: var(--primary-color);
}
footer .copyright {
    padding-top: 3px;
    font-size: 18px;
    text-align: center;
}
footer .copyright a {
    font-weight: 700;
    color: var(--secondary-color);
}
footer .copyright a:hover {
    color: var(--txt-color);
}

/* Responsive Design Starts */
/* For Small Screen */
@media only screen and (min-width: 992px) {
    .navbar {
        justify-content: flex-end;
        width: 100%;
    }
    .navbar .nav-content {
        /* width: 90%;  */
    }
    .navbar .theme {
        /* width:10%; */
        display: flex;
    }
    .hero .main-container .btn {
        display: flex;
        justify-content: space-around;
        width: 65%;
        padding-top: 20px;
    }
    .skills {
        height: 100%;
        width: 100%;
    }
}
/* For Tablet Device */
@media only screen and (max-width: 768px){
    .navbar {
        width: 100%;
        justify-content: space-between;
    }
    .navbar .nav-content {
        width: 85%; 
    }
    .navbar .theme {
        width: 10%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .navbar #theme-icon {
        height: 25px;
        width: 25px;
        cursor: pointer;
    }
    .navbar .brand {
        padding-left: 20px;
    }
    .navbar .nav-content .navlinks {
        width: 55%;
    }
    .hero .main-container {
        margin-left: 25%;
    }
    .hero .main-container h3 {
        font-size: 30px;
    }
    .hero .main-container h1 {
        font-size: 50px;
    }
    .hero .main-container .btn {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        width: 65%;
        padding-top: 15px;
    }
    .hero .main-container button {
        padding: 8px 8px;
        margin: 10px 10px;
        font-size: 18px;
    }
    .hero .main-container p {
        font-size: 25px;
    }
    .about-widget {
        padding: 0px 0px;
    }
    .aboutimg {
        height: 300px;
        width: 350px;
    }
    .aboutimg .aboutlogo {
        height: 100%;
        width: 100%;
    }
    .about-des {
        height: 350px;
        width: 650px;
    }
    .about-des .abouttitle {
        font-size: 30px;
    }
    .about-des .aboutcont {
        font-size: 18px;
        text-align: justify;
        padding: 10px 20px 0px 20px;
    }
    .about-des .abouttagword {
        font-size: 18px;
        padding: 0px 50px;
    }
    .skills {
        height: 100%;
    }
    .skills .skilltitle {
        font-size: 30px;
    }
    .contactdes {
        width: 45%;
    }
    .contactimg {
        width: 55%;
    }
    .contact .contacttitle {
        font-size: 30px;
    }
    .contactdes input {
        height: 30px;
        width: 90%;
        margin-bottom: 10px;
        font-size: 16px;
        padding: 5px 10px;
        color: var(--nav-color);
    }
    .contactdes textarea {
        width: 90%;
        font-size: 16px;
        color: var(--nav-color);
        padding: 5px 10px;
    }
    .contactimg .description {
        font-size: 18px;
    }
    .contactimg .column1 {
        font-size: 40px;
        margin-right: 15px;
    }
    .contactimg .column3 {
        font-size: 40px;
        margin-right: 15px;
    }
    .contactimg .column5 {
        font-size: 40px;
        margin-right: 15px;
    }
}
@media only screen and (min-width: 768px){
    .navbar {
        justify-content: space-around;
    }
    .navbar .nav-content {
        /* width: 90%;  */
    }
    .navbar .theme {
        /* width: 20%; */
        display: flex;
    }
    .skills {
        height: 100%;
    }
}
    /* For Mobile Device */
@media only screen and (max-width: 425px) {
    .navbar .brand {
        padding-left: 25px;
    }
    .navbar .navlinks {
        position: absolute;
        display: none;
    }
    .navbar .foonavlinks {
        background: var(--nav-color);
        position: fixed;
        bottom: 0px;
        list-style-type: none;
        display: flex;
        height: 8vh;
        width: 100vw;
        align-items: center;
        padding: 10px 0px 0px 0px;
        justify-content: space-around;
    }
    .navbar .foonavlinks a {
        color: var(--primary-color);
        text-decoration: none;  
        /* padding: 6px 25px; */
        font-size: 22px;
        position: relative;
    }
    .foonavlinks a .iconify {
        color: #e1e8eb;
    }
    .foonavlinks a:hover .iconify {
        color: var(--secondary-color);
    }
    .navbar .foonavlinks a.active .iconify {
        color: var(--secondary-color);
    }
    .navbar .foonavlinks a.active:after {
        content: "";
        height: 2px;
        width: 100%;
        position: absolute;
        background-color: var(--secondary-color);
        left: 0px;
        top: 30px;
    }
    .hero::before {
        content: "";
        position: absolute;
        background: url(/Images/logo2.jpg);
        background-size: cover;
        /* background-position: center; */
    }
    .hero .main-container h3 {
        font-size: 30px;
    }
    .hero .main-container h1 {
        font-size: 45px;
    }
    .hero .main-container button {
        padding: 8px 8px;
        margin: 10px 10px;
        font-size: 16px;
    }
    .hero .main-container p {
        font-size: 25px;
    }
    .hero .main-container {
        margin-left: 0px;
    }  
    .hero .main-container .btn {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 60%;
        padding-top: 15px;
    }   
    .about-widget {
        flex-direction: column;
        height: 80vh;
        width: 100%;
        padding: 40px 0px 40px 0px;
    }
    .aboutimg {
        height: 200px;
        width: 200px;
    }
    .about-des {
        width: 100%;
    }
    .about-des .aboutcont {
        font-size: 18px;
        padding: 10px 20px;
        text-align: justify;
    }
    .about-des .abouttagword {
        font-size: 18px;
        padding: 0px 50px;
    }
    .contact {
        padding: 80px 0px;
        height: 100%;
        width: 100%;
    }
    .contact .contact-container {
        flex-direction: column-reverse;
        justify-content: center;
        align-items: center;
    }
    .contactdes {
        width: 100%;
    }
    .contactimg {
        width: 100%;
    }
}
.navbar.sticky{
    background: var(--nav-color);
}

/* Theme Changer Code Starts Here */
.dark-theme {
    --primary-color: black;
    --secondary-color: red;
    --bg-color: #343A40;
    --txt-color:#3D3D3D; 
    --main-color: #7952B3;
    --nav-color:#E1E8EB;
}
.dark-theme::selection {
    color: var(--primary-color);
    background: var(--secondary-color);
}
.navbar.bgtheme .foonavlinks .iconify {
    color: var(--primary-color);
}
.hero.bgtheme::before {
    content: "";
    position: absolute;
    left: 0;
    height: 100vh;
    width: 100%;
    z-index: -1;    
    background: url(/Theme/themebg.png);
    background-size: cover;
}
.hero.bgtheme .main-container {
    color: var(--primary-color);
}
.hero.bgtheme .main-container h3 {
    color: var(--primary-color);
}
.hero.bgtheme .main-container h1 {
    color: var(--primary-color);
}
.hero.bgtheme .main-container span {
    color: var(--nav-color);
}
.hero.bgtheme .main-container .typing {
    color: var(--secondary-color);
}
.hero.bgtheme .main-container p span {
    color: var(--secondary-color);
}
.hero.bgtheme .main-container button {
    color: var(--primary-color);
    background: var(--nav-color);
    box-shadow: 0 0 10px var(--primary-color);    
}
.hero.bgtheme .main-container button:hover {
    border: 1px solid var(--secondary-color);
    background: var(--secondary-color);
    color: var(--primary-color);
    box-shadow: 0 0 0px;    
}
.hero.bgtheme .main-container .typing {
    color: var(--secondary-color);
}
.hero.bgtheme .main-container p span {
    color: var(--secondary-color);
}
.about-widget.bgtheme .about-des .aboutcont {
    color: var(--txt-color);
}
.about-widget.bgtheme .abouttagword {
    color: var(--primary-color);
}
.skills.bgtheme h2 {
    color: var(--primary-color);
}
.contact-container.bgtheme .contactform input {
    color: var(--primary-color);
}
.contact-container.bgtheme .contactform textarea {
    color: var(--primary-color);
}
.contact-container.bgtheme .contactimg {
    color: var(--primary-color);
}
.contact-container.bgtheme .contactimg .iconify{
    color: var(--primary-color) !important;
}
.contact-container.bgtheme .contactdes p {
    color: var(--primary-color) !important;
    border: 1px solid var(--nav-color) !important;
    background: var(--nav-color) !important;
    box-shadow: 0 0 10px var(--primary-color) !important;
}
