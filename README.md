<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
        href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,300;0,400;0,700;1,900&display=swap"
        rel="stylesheet" />

    <link rel="stylesheet" href="fuu.css" id="theme" />
    <link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="favicon-16x16.png">
    <link rel="manifest" href="site.webmanifest">
    <link rel="mask-icon" href="safari-pinned-tab.svg" color="#5bbad5">
    <meta name="msapplication-TileColor" content="#da532c">
    <meta name="theme-color" content="#ffffff">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    
    <title>Portfolio</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.js"></script>
</head>

<body>
  
   <div class="main-shit">

 
    <header class="header">
        <div class="container">
            <div class="header_inner">
                <div class="user">
                    <img class="user-avatar" src="images/logo-1.png" alt="" />
                    <div class="user-content">
                        <div class="user-name">
                            Nurislam<br /> Izbasar
                        </div>
                        <div class="user-prof">Useless piece of shit</div>
                    </div>
                </div>

                <div class="nav" id="nav">
                    <a class="nav-link" href="#" data-scroll="#work">My favourites</a>
                    <a class="nav-link" href="#" data-scroll="#about">about me</a>
                    <a class="nav-link" href="#" data-scroll="#courses">blog</a>
                    <a class="nav-link" href="mailto:nurisizbasar@gmail.com">contact</a>
                    <img class="nav-link" src="images/moon.png" id="icon" alt="">
                   
                   
                </div>
                

                

                

                
            </div>
        </div>
    </header>

    <div class="intro">
        <div class="container">
            <div class="intro-inner">
                <div class="intro-content">
                    <h2 class="intro-subtitle">Hello I'm</h2>
                    <h1 class="intro-title">Nurislam Izbasar</h1>
                    <div class="intro-text">Full-stack developer</div>

                    <div class="social">
                        <a class="social-link" href="https://www.youtube.com/watch?v=5qap5aO4i9A&ab_channel=LofiGirl">
                            <img src="images/youtube.png" alt="" />
                        </a>

                        <a class="social-link" href="#">
                            <img src="images/linkedin.png" alt="" />
                        </a>

                        <a class="social-link" href="#">
                            <img src="images/facebook.png" alt="" />
                        </a>

                        <a class="social-link" href="https://www.instagram.com/nurisovanny1/">
                            <img src="images/instagram.png" alt="" />
                        </a>

                        <a class="social-link" href="#">
                            <img src="images/twitter.png" alt="" />
                        </a>
                    </div>

                    <!-- ПРОСТО КНОПКА -->
                    <button class="btn" type="button" data-modal="#modal_resume">SEE MY RESUME</button>
                </div>

                <img class="intro-photo" src="images/me.png" alt="" />
            </div>
        </div>
    </div>

    <div class="works" id="work">
        <div class="container">
            <h3 class="text-center">My favourites</h3>
            <div class="portfolio">
                <div class="work">
                    <img class="work-photo" src="images/king.png" alt="" width="340px" height="230px" />
                    <div class="work-content">
                        <div class="work-category">category:anime characters</div>
                        <div class="work-title">
                            Kageyama
                            <div class="work-date">Tobio</div>
                        </div>
                    </div>
                </div>

                <div class="work">
                    <img class="work-photo" src="images/noya.png" alt="" width="350px" height="230px" />
                    <div class="work-content">
                        <div class="work-category">category:anime characters</div>
                        <div class="work-title">
                            Yu
                            <div class="work-date">Nishinoya</div>
                        </div>
                    </div>
                </div>

                <div class="work">
                    <img class="work-photo" src="images/hinata.png" alt="" width="340px" height="230px" />
                    <div class="work-content">
                        <div class="work-category">category:anime characters</div>
                        <div class="work-title">
                            Hinata
                            <div class="work-date">Shoyo</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="about" id="about">
        <div class="container">
            <div class="about-inner">
                <img class="about-photo" src="images/jstop-2.png" alt="" width="500px" height="580px">
                <div class="about-content">
                    <h3 class="about-title">About me</h3>
                    <h2 class="about-big-title">Who am I</h2>
                    <div class="about-text">
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptas molestiae alias
                            sapiente
                            quas enim labore recusandae eaque possimus rem neque excepturi doloribus, consequuntur
                            officiis aliquid voluptates quia optio quasi libero.</p>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptas molestiae alias
                            sapiente
                            quas enim labore recusandae eaque possimus rem neque excepturi doloribus, consequuntur
                            officiis aliquid voluptates quia optio quasi libero.</p>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptas molestiae alias
                            sapiente
                            quas enim labore recusandae eaque possimus rem neque excepturi doloribus, consequuntur
                            officiis aliquid voluptates quia optio quasi libero.</p>

                    </div>

                    <button class="btn" type="button" data-modal="#modal_resume">see my resume</button>
                </div>
            </div>
        </div>
    </div>

    <div class="reviews">
        <div class="container">
            <div class="reviews-inner">
                <div class="reviews-text">
                    <p>Awesome teacher! Learned way more than I expected to or even thought I was going to. Would
                        recommend the course to anyone looking to learn a front-end modern framework. Great
                        experience!
                    </p>
                    <p>Great course! I have learned a lot from this course. Very well structured and much better
                        than
                        class room teaching. Very lear explanation with practical examples. In one sentence " Simply
                        Amazing"!</p>
                </div>
            </div>

            <div class="reviews-author">
                <img class="reviews-logo" src="images/logo-1.2.png" alt="" width="100px" height="100px">
                <div class="reviews-company">nurisovanny</div>
                <div class="reviews-name">haters</div>
                <div class="reviews-rating">
                    <img class="reviews-star" src="images/star.png" alt="">
                    <img class="reviews-star-unactive" src="images/star.png" alt="">
                </div>
            </div>
        </div>
    </div>

    <div class="my-courses" id="courses">
        <div class="container">
            <h3 class="text-center margin">My courses</h3>
            <div class="subtitle">I am an instructor and teach students all over the world.</div>

            <div class="courses-inner">
                <div class="course">
                    <img class="course-photo" src="images/Angular logo.png" alt="">
                    <div class="course-content">
                        <h4 class="course-name">ANGULAR. PRACTICAL COURSE</h4>
                        <div class="course-category">WEB DEVELOPMENT</div>
                        <div class="course-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Doloribus
                            minima vitae, cupiditate nam nobis repudiandae cum blanditiis consectetur a. Eius
                            expedita
                            atque tenetur molestiae ex. Rem accusamus ab sunt cupiditate.</div>
                    </div>

                    <a href="https://html5.by/blog/flexbox/">
                        <button class="btn btn-edit" type="button">Show more</button></a>
                </div>

                <div class="course">
                    <img class="course-photo" src="images/Angular logo.png" alt="">
                    <div class="course-content">
                        <h4 class="course-name">ANGULAR. PRACTICAL COURSE</h4>
                        <div class="course-category">WEB DEVELOPMENT</div>
                        <div class="course-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Doloribus
                            minima vitae, cupiditate nam nobis repudiandae cum blanditiis consectetur a. Eius
                            expedita
                            atque tenetur molestiae ex. Rem accusamus ab sunt cupiditate.</div>
                    </div>

                    <a href="https://html5.by/blog/flexbox/">
                        <button class="btn btn-edit" type="button">Show more</button></a>
                </div>

                <div class="course">
                    <img class="course-photo" src="images/Angular logo.png" alt="">
                    <div class="course-content">
                        <h4 class="course-name">ANGULAR. PRACTICAL COURSE</h4>
                        <div class="course-category">WEB DEVELOPMENT</div>
                        <div class="course-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Doloribus
                            minima vitae, cupiditate nam nobis repudiandae cum blanditiis consectetur a. Eius
                            expedita
                            atque tenetur molestiae ex. Rem accusamus ab sunt cupiditate.</div>
                    </div>

                    <a href="https://html5.by/blog/flexbox/">
                        <button class="btn btn-edit" type="button">Show more</button></a>
                </div>
            </div>
            <div class="link">
                <a class="course-link"
                    href="https://www.udemy.com/?utm_source=adwords-brand&utm_medium=udemyads&utm_campaign=NEW-AW-PROS-Branded-Search-RU-RUS_._ci__._sl_RUS_._vi__._sd_All_._la_RU_._&tabei=7&utm_term=_._ag_58158836094_._ad_294734292909_._de_c_._dm__._pl__._ti_kwd-310556426868_._li_9069573_._pd__._&gclid=CjwKCAjwz_WGBhA1EiwAUAxIcQHZqs7O6D_ENtW3m5g0-QXwiQNTYEpJRWSmibpmNfzyZyPsx3ECgRoC7vIQAvD_BwE">Show
                    more courses</a>
            </div>
        </div>
    </div>

    <footer class="footer">
        <div class="container">
            <div class="footer-inner">

                <div class="footer-info">
                    <div class="footer-copyright">
                        &copy; 2021-Nurislam Izbasar
                    </div>
                    <div class="footer-social">
                        <a class="footer-link" href="">
                            <img src="images/linkedin-1.png" alt="">
                        </a>

                        <a class="footer-link" href="">
                            <img src="images/facebook-1.png" alt="">
                        </a>

                        <a class="footer-link" href="">
                            <img src="images/instagram-1png.png" alt="">
                        </a>

                        <a class="footer-link" href="">
                            <img src="images/twitter-1.png" alt="">
                        </a>
                    </div>
                </div>


                <div class="footer-nav">
                    <a class="footer-nav-link" href="#" data-scroll="#work">my favourites</a>
                    <a class="footer-nav-link" href="#" data-scroll="#about">about me</a>
                    <a class="footer-nav-link" href="#" data-scroll="#courses">blog</a>
                    <a class="footer-nav-link" href="mailto:nurisizbasar@gmail.com">contact</a>

                </div>
            </div>
        </div>
    </footer>

   <div class="modal" id="modal_resume">
       <div class="modal-dialog">
           <h3 class="modal-title">RESUME</h3>
           <img class="modal-photo" src="images/resume.jpg" alt="">
           <a class="btn btn-edit btn-modal" href="images/resume.jpg" download>Download</a>
       </div>
   </div>
</div> 


   
    <script src="mugen.js"></script>


</body>

</html>
