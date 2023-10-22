<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Bart Jason</title>

    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="header.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <link rel="stylesheet" href="https://unpkg.com/boxicons@latest/css/boxicons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.2.0/fonts/remixicon.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Permanent+Marker&family=Poppins:ital,wght@0,300;0,600;0,700;0,800;1,400;1,500&family=Roboto:ital,wght@0,300;0,400;1,300&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/17dbd0ab3f.js" crossorigin="anonymous"></script>

    <style>
        #header{
            width: 100%;
            height: 100vh;
            background-image: url(images/1st_photo-removebg-preview1.png);
            background-size: cover;
            background-position: center;
        }

        
    </style>

</head>

<body>
  
  
    <div id="header" data-aos="slide-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="1000" >
        <div class="container">
            
            <nav>
                <img li data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="1000"  src = "Black_White_Minimalist_Letter_BJ_Logo__1_-removebg-preview.png" class = "logo">
                <ul>
                    <li data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="1000" ><a href="#">Home</a></li>
                    <li data-aos="fade-down-right" data-aos-duration="1200"  data-aos-once="true"data-aos-delay="1200" ><a href="#about">About</a></li>
                    <li data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true"data-aos-delay="1400" ><a href="#education">Education</a></li>
                    <li data-aos="fade-down-right" data-aos-duration="1200" data-aos-once="true"data-aos-delay="1600"><a href="#porfolio">My Works</a></li>
                    <li data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true"data-aos-delay="1800"><a href="#contact">Contacts</a></li>
                </ul>
            </nav>
            <div class="header-text" data-aos="slide-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1500" >
                <p data-aos="slide-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1800" > An aspiring <span data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true"data-aos-delay="2400">Web Developer</span>  </p>
                <h1 data-aos="slide-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1800" > Hi, I'm <span data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true"data-aos-delay="3000">Bart Jason</span><br>from Our Lady Of Fatima<br>currently taking BSIT.</h1>
            </div>
            <div class ="icons">
                <a  href="#" target="_blank" >
                    <i class="fab fa-linkedin"></i>
                  </a>
                  <a  href="https://github.com/koise" target="_blank" >
                    <i class="fab fa-github" ></i>
                  </a>
                  <a href="mailto:qbartjason@gmail.com" >
                    <i class="far fa-envelope"></i>
                  </a>
            </div>
        </div>
    </div>

    
<!-- START OF PAGE 2 // ABOUT-->
    <div id = "about" >
        <div class ="container" data-aos="slide-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="300">
            <div class="row">
                <div class="col2">
                    <img data-aos="flip-up" data-aos-duration="1200" data-aos-once="false" data-aos-delay="500"src = "Images/hero.jpeg">
                </div>
                <div data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="true" data-aos-delay="700" class="col1" >
                    <h1 data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="true" data-aos-delay="900" class = "sub">About me</h1>
                    <p data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="true" data-aos-delay="1100"> An aspiring web developer with a passion for programming and a
                        strong desire to explore the IT industry.   
                    </p>

                    <div data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1300" class="tab-titles">
                        <p class = "tab-links active-link" onclick = "opentab('skills')">Skills</p>
                        <p class = "tab-links" onclick = "opentab('experience')">Experience</p>
                    </div>

                    <div data-aos="fade-up-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1500" class="tab-contents active-tab" id = "skills">
                        <li data-aos="fade-up-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1600"><span>Programming</span><br>Intermediate C language, Basic C#, Basic C++.</li>
                        <li data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1700" ><span>Web Development</span><br>Basic HTML, CSS,and Javascript.</li>
                        <li data-aos="fade-up-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1800"><span>Data Base Management</span><br>Basic mySQL.</li>
                        <li data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1900"><span>Multimedia</span><br>Photoshop and Premiere</li>
                    </div>
                    <div class="tab-contents" id = "experience">
                        <li data-aos="fade-up-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1600" ><span>2019</span><br> Crew member of MeoAsia: Flavors of Asia</li>
                        <li data-aos="fade-up-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1700"><span>2019</span><br> School Disaster Risk Management: Physical Head</li>
                        <li data-aos="fade-up-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1800" ><span>2019</span><br> Antipolo National Highschool: Head of Techcrew </li>
                  </div>

                </div>
                
            </div>
        </div>
    </div>
   

    <!-- PAGE 3 STARTS HEREEEEEEE-->
    <div id="education" >
        <div class="container" data-aos="slide-right" data-aos-duration="1200" data-aos-once="true" data-aos-delay="400">
        <h1 class = "sub" data-aos="slide-right" data-aos-duration="1200" data-aos-once="true"> Education </h1>
            <div class="education-list" >
                <div data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="false" data-aos-delay="700" >
                    <i class="fa-solid fa-school"></i>
                    <h2>
                        Elementary
                    </h2>
                    <p>Lord Jesus Blessed Academy </p>
                    <a href="https://www.facebook.com/ljbarecy" target="_blank" >Learn more</a>
                </div>
                <div data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="false"" data-aos-delay="1000" >
                    <i class="fa-solid fa-school"></i>
                    <h2>
                        Junior Highschool
                    </h2>
                    <p> Antipolo National Highschool </p>
                    <a href="https://www.facebook.com/kwentongMMCartist" target="_blank">Learn more</a>
                </div>

                <div data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1300">
                    <i class="fa-solid fa-graduation-cap"></i>
                    <h2>
                        Senior Highschool
                    </h2>
                    <p>Antipolo Institute of Technology </p>
                    <a href="https://www.facebook.com/AntipoloInstituteofTechnology" target="_blank" >Learn more</a>
                </div>

                <div data-aos="fade-up-right" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1800">
                    <i class="fa-solid fa-graduation-cap"></i>
                    <h2>
                       College
                    </h2>
                    <p>Our Lady Of Fatima </p>
                    <p> <br> Currently taking BSIT Course</p>
                    <a href="https://www.fatima.edu.ph/" target="_blank">Learn more</a>
                </div>
            </div>
        </div>
    </div>

    <div id="porfolio" data-aos="slide-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="400">
        <div class="container">
            <h1 class = "sub" data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="1400"> My Works </h1>
            <div class="work-list">
                <div class="work" class = "sub" data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="1800">
                    <img src="work-1.png" alt="work">
                    <div class="layer">
                    <h3> A like twitter in C language</h3>
                    <p> A like twitter purposes</p>
                    <a href = "https://drive.google.com/file/d/1BsgUi_3X2uABjjuREvl9npKb9CbB87Y_/view?usp=share_link" target="_blank" > <i class="fa-sharp fa-solid fa-link"></i></a>
                    </div>
                </div>
                <div class="work" class = "sub" data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="2000" >
                    <img src="work-2.png" alt="work">
                    <div class="layer">
                    <h3> My personal porfolio</h3>
                    <p> Show my personal details</p>
                    <a href = "#" > <i class="fa-sharp fa-solid fa-link"></i></a>
                    </div>
                    
                </div>
                <div class="work" class = "sub" data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="2200" >
                    <img src="work-3.png" alt="work">
                    <div class="layer">
                        <h3> ATM a like</h3>
                        <p> a transaction teller in C language</p>
                        <a href = "https://drive.google.com/file/d/1nDeSUOueWGC5PoqEhG4qq3mr0-qLGF9z/view?usp=share_link" target = "_blank"> <i class="fa-sharp fa-solid fa-link"></i></a>
                    </div>
                </div>
            </div>
            <a href = "https://drive.google.com/drive/folders/1G3Ht97Kb8dPkaWCjEtu7jJ5swPaWsNhE?usp=sharing" target="_blank" class = "btn" class = "sub" data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="false" data-aos-delay="2600" > See more </a>
        </div>
    </div>

    <!-- CONTACTS START HERE-->

    <div id="contact">
        <div class="container" data-aos="slide-right" data-aos-duration="1200" data-aos-once="true" data-aos-delay="100">
            <h1 class = "sub" data-aos="slide-right" data-aos-duration="1200" data-aos-once="true" data-aos-delay="1100" > Contact Me</h1>
            <div class="row">
                <div class="contact-left" data-aos="slide-right" data-aos-duration="1200" data-aos-once="true" data-aos-delay="1400">
                   
                    <p data-aos="slide-right" data-aos-duration="1200" data-aos-once="true" data-aos-delay="1600"><i class="fa-solid fa-envelope"></i><t>   qbartjason@gmail.com</t></p>
                    <p data-aos="slide-right" data-aos-duration="1200" data-aos-once="true" data-aos-delay="1800" > <i class="fa-solid fa-phone-volume"></i>   09504893347</p>
                    <div class="social-icons">
                        <a href="https://www.facebook.com/profile.php?id=100087179365224" data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="2000" ><i class="fa-brands fa-facebook-messenger"></i></a>
                        <a href="https://www.instagram.com/baaaaaarrtttttt/" data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="2300"  ><i class="fa-brands fa-square-instagram"></i></i></a>
                        <a href="https://twitter.com/koisbart" data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="2600"  ><i class="fa-brands fa-square-twitter"></i></i></a>
                        <a href="https://web.telegram.org/z/@Robwam" data-aos="fade-down-left" data-aos-duration="1200" data-aos-once="true" data-aos-delay="2900" ><i class="fa-brands fa-telegram"></i></i></a>
                        </div>
                </div>
                <c></c>
                <form>  
                    <input type = "text" name = "Name" placeholder="Your Name" required>
                    <input type = "email" name = "email" placeholder="Your email" required> 
                    <textarea name = "messsage" rows = "6" placeholder="Your Message"></textarea>
                    <button class = "submit">Submit</button>
                </form>
            </div>
        </div>


    <!-- Footer starts here-->
    <footer >
        <div class="footer-container" >
          <div class="footer-links">
            <a href="#" ">Home</a>
            <a href="#about"  >About</a>
            <a href="#education" >Education</a>
             <a href="#porfolio" >My Works</a>
            <a href="#contact"s>Contacts</a>
          </div
        </div>
        <p class="footer-text">© 2023 Bart Jason. All rights reserved.</p>
      </footer>
    </div>

<!-- LOADING SCREEN AND JS HERE-->
    <div class="loading" style="display: none;">
        <div class="loading-overlay"></div>
        <div class="loading-spinner">
          <svg width="64px" height="48px">
            <polyline points="0.157 23.954, 14 23.954, 21.843 48, 43 0, 50 24, 64 24" id="back"></polyline>
            <polyline points="0.157 23.954, 14 23.954, 21.843 48, 43 0, 50 24, 64 24" id="front"></polyline>
          </svg>
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

        const loading = document.querySelector('.loading');
      
        // Show loader when starting API request
        loading.style.display = 'flex';
      
        fetch('https://example.com/api/data')
          .then(response => response.json())
          .then(data => {
            // Process API response data
            console.log(data);
      
            // Hide loader after API request is complete
            loading.style.display = 'none';
          })
          .catch(error => {
            // Handle API request error
            console.error(error);
      
            // Hide loader after API request is complete
            loading.style.display = 'none';
          });
  
     </script>

    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
    AOS.init({
        duration: 3000
    });
    </script>


</body>
</html>
