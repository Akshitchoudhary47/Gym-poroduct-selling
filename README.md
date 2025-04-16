<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="VFitClub - A sleek fitness website designed with HTML5, CSS3, and Javascript, featuring grid and flexbox layout techniques and stylish animations." />

  <title>BFITClub - Elevate Your Fitness Journey</title>
  <link rel="icon" type="https://bfitclub.netlify.app/image/png" sizes="32x32" href="https://bfitclub.netlify.app/image/favicon.png" />
  <link rel="stylesheet" href="style.css" media="screen" />
  <link href="https://cdn.rawgit.com/michalsnik/aos/2.1.1/dist/aos.css" rel="stylesheet" />
</head>

<body>
  <!-- HEADER -->
  <header class="header">
    <div class="container">
      <nav class="header-nav" aria-label="navigation">
        <div class="logo-content">
          <img src="logo.jpg" alt="Logo" class="nav-icon" width="70" height=60 />
          <div class="logo">BFIT</div>
        </div>
        <img src="https://bfitclub.netlify.app/image/nav-icon.svg" alt="navigation icon" class="nav-hamburger" width="30" height="30" />
        <ul>
          <li>
            <a href="#aboutus">About</a>
          </li>
          <li>
            <a href="#memberships">Memberships</a>
          </li>
          <li>
            <a href="#ourteam">Our Team</a>
          </li>
          <li>
            <a href="#contact">Join Us</a>
          </li> 
        </ul>
      </nav>
    </div>
  </header>
  <main>
    <!-- MAIN SECTION -->
    <section class="section-hero" id="section-hero">
      <div class="container hero-box">
        <div class="hero-image-content">
          <h1 class="heading">Unlock Your Best Self at BFitClub. Embrace Wellness, Transform Your Life</h1>
          <p class="description">Experience the Ultimate Fitness Journey with Functional Training, Plyometric Boxes, Aerobics Classes, TRX, and More</p>
          <div class="hero-box-buttons"><button>Discover Classes</button><button>See Our Offerings</button></div>
        </div>
      </div>

    </section>
    <section class="section-aboutus" id="aboutus">
      <div class="container aboutus">
        <div class="section-aboutus-info" data-aos="fade-down">
          <h2>About BFitClub</h2>
          <p>
            At BFitClub, we're not just a fitness center; we're a community dedicated to transforming lives through health and wellness. Founded with a passion for helping individuals
            achieve their fitness goals, our mission is to empower, inspire, and support you on your journey to a healthier, happier life.
          </p>
          <h2>Our Vision</h2>
          <p>
            Our vision is to be your trusted partner in achieving optimal well-being. We believe that a strong and healthy body is the foundation for a successful, fulfilling life.
            Whether you're new to fitness or a seasoned athlete, we're here to guide you on your path to success.
          </p>
        </div>
        <div class="section-aboutus-images">
          <figure class="about-box__image">
            <img src="blog-1.jpg" alt="navigation icon" class="nav-hamburger" width=320" height="190" style="--i: 0" data-aos="fade-down-right" />
            <img src="blog-3.jpg" alt="navigation icon" class="nav-hamburger" width="320" height="190" style="--i: 1" data-aos="fade-down" />
            <img src="blog-4.jpg" alt="navigation icon" class="nav-hamburger" width="320" height="190" style="--i: 2" data-aos="fade-down-left" />
          </figure>
        </div>
      </div>
    </section>

    <section class="section-ourteam" id="ourteam">
      <div class="container ourteam" data-aos="fade-down">
        <h2 class="title">Our Team</h2>
        <div class="team-members">
          <div class="team-member">
            <img src="trainer-1.jpg" alt="Logo" class="member-logo" />
            <div class="team-memmber-info">
              <div class="member-name">Joe Bloggs</div>
              <div class="member-desg">Weight Lifting Coach</div>
              <div class="member-desc">Specializes in sculpting strength and muscle with precision</div>
            </div>
          </div>
          <div class="team-member">
            <img src="trainer-3.jpg" alt="Logo" class="nav-icon img-11" />
            <div class="team-memmber-info">
              <div class="member-name">Charlie Watson</div>
              <div class="member-desg">MMA Coach</div>
              <div class="member-desc">Hones combat skills and self-defense with expertise</div>
            </div>
          </div>
          <div class="team-member">
            <img src="trainer-2.jpg" alt="Logo" class="nav-icon" />
            <div class="team-memmber-info">
              <div class="member-name">Rachel Danielle</div>
              <div class="member-desg">Yoga Instructor</div>
              <div class="member-desc">Guides you to inner peace and flexibility through mindful yoga practice</div>
            </div>
          </div>
          <div class="team-member">
            <img src="trainer-4.jpg" alt="Logo" class="nav-icon" />
            <div class="team-memmber-info">
              <div class="member-name">Taylor Melé</div>
              <div class="member-desg">Personal Trainer</div>
              <div class="member-desc">Your path to achieving fitness goals, one personalized session at a time</div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section-memberships" id="memberships">
      <div class="container memberships">
        <h2 class="title">Memberships</h2>
        <div class="classes">
          <div class="class" data-aos="flip-left">
            <h2 class="class-name">3 Months</h2>
            <div class="class-price">₹ 1,000MON USD</div>
            <hr />
            <div class="class-name">
              <ul>
                <li>5 Classes</li>
                <li>5 In Personal Training Sessions</li>
                <li>Full Gym & Facilities Access</li>
                <li>Gym Tour & Training Instruction</li>
              </ul>
            </div>
            <a>Get Started</a>
          </div>
          <div class="class" data-aos="flip-up">
            <h2 class="class-name">6 Months</h2>
            <div class="class-price">₹ 2,000MON USD</div>
            <hr />
            <div class="class-name">
              <ul>
                <li>10 Classes</li>
                <li>10 In Personal Training Sessions</li>
                <li>Full Gym & Facilities Access</li>
                <li>Boxing Ring, Free Events</li>
                <li>Gym Tour & Training Instruction</li>
              </ul>
            </div>
            <a>Get Started</a>
          </div>
          <div class="class" data-aos="flip-right">
            <h2 class="class-name">1 Whole Year</h2>
            <div class="class-price">₹ 6,000/MON USD</div>
            <hr />
            <div class="class-name">
              <ul>
                <li>10 Classes</li>
                <li>15 In Personal Training Sessions</li>
                <li>Full Gym & Facilities Access</li>
                <li>Boxing Ring, Free Events</li>
                <li>Gym Tour & Training Instruction</li>
              </ul>
            </div>
            <a>Get Started</a>
          </div>
        </div>
      </div>
    </section>
    <section class="section-reviews" id="reviews">
      <div class="container reviews">
        <h2 class="title">Customer Reviews</h2>
        <div class="review">
          <div class="review-info">
            <div class="review-image" data-aos="image-rotateIn"><img src="pic-2.png" alt="Logo" class="review-icon" width="130" height="130" /></div>
            <div class="review-details" data-aos="fade-down">
              <div>Samantha R</div>
              <div>
                I can't say enough good things about BFitClub. The trainers are exceptional, and the community is so welcoming. I've made incredible progress in my fitness journey
                here
              </div>
            </div>
          </div>
          <div class="review-info">
            <div class="review-image" data-aos="image-rotateIn"><img src="pic-1.png" alt="Logo" class="review-icon" width="130" height="130" /></div>
            <div class="review-details" data-aos="fade-down">
              <div>Vinay U</div>
              <div>Charlie, the MMA coach, is a true expert. He pushes you to your limits while ensuring safety. I've learned so much and gained newfound confidence</div>
            </div>
          </div>
          <div class="review-info">
            <div class="review-image" data-aos="image-rotateIn"><img src="pic-3.png" alt="Logo" class="review-icon" width="130" height="130" /></div>
            <div class="review-details" data-aos="fade-down">
              <div>Michael S</div>
              <div>
                </B>BFitClub is not just a gym; it's a lifestyle. The facility is top-notch, and the trainers are top-level. I've never felt more motivated and supported in my fitness
                journey
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section-contact" id="contact">
      <div class="container contact">
        <div class="contactus">
          <!-- <form>
            <h2 class="title">GET IN TOUCH</h2>
            <div class="class-input"><input type="text" placeholder="Name" /></div>
            <div class="class-input"><input type="email" placeholder="Email" /></div>

            <div class="class-input"><input type="number" placeholder="Number" /></div>
            <div class="class-input"><textarea placeholder="Message"></textarea></div>
            <button>SEND</button>
          </form> -->
        </div>
        <!-- <div class="map">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6208.882633670527!2d-77.03822868422614!3d38.914011108427125!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89b7b7e5bf2241b3%3A0xeee16e72747760aa!2sU%20Street%2FAfrican-Amer%20Civil%20War%20Memorial%2FCardozo!5e0!3m2!1sen!2sin!4v1699174834310!5m2!1sen!2sin" allowfullscreen="" loading="lazy" style="border: 0" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div> -->
      </div>
    </section>
  </main>
  <footer class="section-footer" id="footer">
    <div class="footer-box container">
      <div class="contact-details">
        <h2>BFitClub</h2>
        <div class="contact-company-address">
          123 Wellness Way Activeville,<br />
          Fitnessland 56789<br />United States
        </div>
        <div class="contact-social-links">
          <img src="Image.jpg" alt="navigation icon" class="nav-hamburger" width="35" height="35" /> <img src="Image 1.jpg" alt="navigation icon" class="nav-hamburger" width="35" height="35" /> <img src="image (2).avif" alt="navigation icon" class="nav-hamburger" width="35" height="35" /> <img src="Image 3.jpg" alt="navigation icon" class="nav-hamburger" width="35" height="35" />
        </div>
      </div>
      <nav class="footer-nav" aria-label="navigation">
        <h3>Quick Links</h3>
        <ul>
          <li>
            <a href="#aboutus">About</a>
          </li>
          <li>
            <a href="#memberships">Memberships</a>
          </li>
          <li>
            <a href="#ourteam">Our Team</a>
          </li>
          <li>
            <a href="#contact">Contact </a>
          </li>
          <li>
            <a href="#reviews">Reviews</a>
          </li>
        </ul>
      </nav>
      <div class="newsletter">
        <h3>News Letter</h3>
        <input type="email" placeholder="email@domain.com" /><button>&#10003;</button>
      </div>
    </div>
    <hr />
    <div class="container copyrights">
      <div>Copyright © by Akshit</div>
      <div>All Rights Reserved</div>
      <div>Designed by Akshit Choudhary</div>
      
      <a href="https://github.com/Akshitchoudhary47/Gym-poroduct-selling" target="_blank" > <i class="fa-brands fa-github "></i></a>
    </div>
  </footer>
  <!-- <div id="offerModal" class="offerModal">
    <div class="modal-content">
      <h2>Got hiit</h2>
      <p>Experience our new high-intensity interval
        training facility to boost endurance and agility!</p>
      <h1>70%OFF FOR NEW GYM MEMBERS</h1>
      <div><button>Unlock 70% Off</button><button class="close-button">Maybe Later</button></div>
    </div> -->
  </div>
  <script src="./index.js"></script>
  <script src="https://cdn.rawgit.com/michalsnik/aos/2.1.1/dist/aos.js"></script>
  <script>
    AOS.init({
      offset: 120,
      delay: 50,
      duration: 400,
      once: true,
    });
  </script>
</body>

</html>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@100;200;400;500;900&family=Poppins&display=swap");
:root {
  --color-yellow: #86d66e;
  --color-yellow-dark: hsl(56, 100%, 33%);
  --color-yellow-light: hsl(55, 67%, 78%);
  --color-black: hsl(0, 0%, 13%);
  --color-black-light: hsl(0, 0%, 18%);
  --color-black-light-text: hsl(0, 0%, 27%);
  --two-col-layout: 2;
  --four-col-layout: 4;
  --three-col-layout: 3;
  --total-stack-size: 10;
}

@media only screen and (max-width: 56.25em) {
  :root {
    --two-col-layout: 1;
    --four-col-layout: 1;
    --three-col-layout: 1;
  }
}

@media only screen and (max-width: 59em) {
  :root {
    --two-col-layout: 1;
    --four-col-layout: 1;
    --three-col-layout: 1;
  }
}

*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  -webkit-box-sizing: inherit;
  box-sizing: inherit;
}

html {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  font-size: 62.5%;
  scroll-behavior: smooth;
}

h1 {
  font-size: 3.5rem;
}

a {
  text-decoration: none;
  color: inherit;
}

hr {
  border: 0;
  margin: 0;
  width: 100%;
  height: 2px;
  background: #606060;
  margin-bottom: 10px;
}

body {
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  font-size: 1.6rem;
  line-height: 1.9;
  color: #ffffff;
}

body .container {
  max-width: 1440px;
  padding: 0 1.4rem;
  margin: 0 auto;
}

body button {
  padding: 8px 25px;
  font-style: italic;
  text-transform: uppercase;
  background-color: var(--color-yellow);
  border: none;
  color: #000;
  font-weight: 600;
  margin-bottom: 5px;
  cursor: pointer;
  -webkit-backdrop-filter: blur(5px);
  backdrop-filter: blur(5px);
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  -webkit-clip-path: polygon(5% 0, 100% 0%, 95% 100%, 0% 100%);
  clip-path: polygon(5% 0, 100% 0%, 95% 100%, 0% 100%);
}

body button:hover {
  background-color: #000;
  color: var(--color-yellow);
  -webkit-clip-path: polygon(5% 0, 100% 0%, 95% 100%, 0% 100%);
  clip-path: polygon(5% 0, 100% 0%, 95% 100%, 0% 100%);
}

body section:nth-child(odd) {
  background-color: var(--color-black);
}

body section:nth-child(even) {
  background-color: var(--color-black-light);
}

body .header {
  position: absolute;
  top: 0;
  z-index: 10;
  width: 100%;
  background-image: -webkit-gradient(
    linear,
    left top,
    left bottom,
    from(black),
    to(rgba(0, 0, 0, 0))
  );
  background-image: linear-gradient(black, rgba(0, 0, 0, 0));
}

body .header .header-nav {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  padding: 10px 0px;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

body .header .header-nav .nav-hamburger {
  display: none;
}

@media only screen and (max-width: 50em) {
  body .header .header-nav .nav-hamburger {
    display: block;
  }
}

body .header .header-nav .logo-content {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  gap: 5px;
}

body .header .header-nav .logo {
  font-size: 3rem;
  font-weight: 600;
  letter-spacing: 3px;
}

@media only screen and (max-width: 50em) {
  body .header .header-nav .logo {
    font-size: 2.5rem;
  }
}

body .header .header-nav .nav-icon {
  -webkit-transition: all 0.5s;
  transition: all 0.5s;

}

@media only screen and (max-width: 50em) {
  body .header .header-nav .nav-icon {
    height: 40px;
    width: 40px;
  }
}

body .header .header-nav:hover > .nav-icon {
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg);
}

body .header ul {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  gap: 15px;
  list-style: none;
  text-transform: uppercase;
}

@media only screen and (max-width: 50em) {
  body .header ul {
    display: none;
  }
}

body .header ul li {
  position: relative;
  padding: 5px;
  overflow: hidden;
  font-size: 1.8rem;
  font-style: italic;
  font-weight: 600;
  letter-spacing: 1.2px;
  cursor: pointer;
}

body .header ul li:hover {
  color: var(--color-yellow);
}

body .header ul li a:after {
  background-color: var(--color-yellow);
  content: "";
  position: absolute;
  width: 90%;
  left: -100%;
  height: 3px;
  border-radius: 30px;
  bottom: 0px;
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

body .header ul li a:hover:after {
  left: 5%;
}

body .header ul li:last-child {
  background-color: var(--color-yellow);
  border: 2px solid var(--color-yellow);
  border-radius: 5px;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  color: #000;
  cursor: pointer;
  padding: 3px 10px;
}

body .header ul li:last-child:hover {
  background-color: inherit;
  color: #fff;
}

body .header ul li:last-child a:after {
  content: none;
}

body .section-hero {
  position: relative;
  overflow: hidden;
  height: 100vh;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  background-image: url("Background.jpg");
  -webkit-backdrop-filter: blur(10px);
  backdrop-filter: blur(10px);
  background-size: cover;
}

@media only screen and (max-width: 50em) {
  body .section-hero {
    background-image: url("home-bg-3.jpg"),
      url("https://vfitclub.netlify.app/image/hero-background.webp");
    background-position: bottom, center;
    background-size: cover;
    background-repeat: no-repeat;
  }
}

body .section-hero .hero-box {
  height: 100%;
  width: 100%;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  background-image: url("home-bg-3.jpg");
  background-repeat: no-repeat;
  background-position: bottom;
  background-size: contain;
}

@media only screen and (max-width: 50em) {
  body .section-hero .hero-box {
    background-image: none;
  }
}

body .section-hero .hero-box .hero-image-content {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: start;
  -ms-flex-align: start;
  align-items: start;
  gap: 15px;
}

body .section-hero .hero-box h1 {
  text-transform: uppercase;
  font-size: clamp(2.5rem, 3vw, 3rem);
  text-shadow: 2px 5px 5px rgba(0, 0, 0, 0.7), 0px -4px 12px rgba(0, 0, 0, 0.5);
  -webkit-animation: moveInLeft 0.5s ease-out;
  animation: moveInLeft 0.5s ease-out;
}

@media only screen and (max-width: 50em) {
  body .section-hero .hero-box h1 {
    text-shadow: none;
  }
}

body .section-hero .hero-box p {
  font-size: 1.8rem;
  text-shadow: 2px 7px 5px rgba(0, 0, 0, 0.4), 0px -4px 10px rgba(0, 0, 0, 0.5);
  -webkit-animation: moveInRight 0.5s ease-out;
  animation: moveInRight 0.5s ease-out;
}

body .section-hero .hero-box .hero-box-buttons {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  gap: 10px;
}

body .section-hero .hero-box .hero-box-buttons button {
  font-size: 1.6rem;
}

body .section-hero .hero-section-mouseClick {
  position: absolute;
  -webkit-animation: onclick 0.1s;
  animation: onclick 0.1s;
  z-index: -1;
  -webkit-box-shadow: rgba(195, 184, 34, 0.15) 0px 0px 30px 30px;
  box-shadow: rgba(195, 184, 34, 0.15) 0px 0px 30px 30px;
}

body .section-aboutus {
  padding-top: clamp(4rem, 10vw, 10rem);
}

body .section-aboutus .aboutus {
  overflow: hidden;
  padding: 3rem 3rem;
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: (minmax(min-content, 1fr)) [var];
  grid-template-columns: repeat(
    var(--two-col-layout),
    minmax(-webkit-min-content, 1fr)
  );
  grid-template-columns: repeat(
    var(--two-col-layout),
    minmax(min-content, 1fr)
  );
  grid-row-gap: 0rem;
  grid-column-gap: 5rem;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  text-align: justify;
}

body .section-aboutus .aboutus .section-aboutus-images {
  -webkit-box-align: baseline;
  -ms-flex-align: baseline;
  align-items: baseline;
  -webkit-box-pack: baseline;
  -ms-flex-pack: baseline;
  justify-content: baseline;
}

body .section-aboutus .aboutus .section-aboutus-images figure {
  display: -ms-grid;
  display: grid;
  -ms-grid-rows: 150px 150px 150px;
  grid-template-rows: 150px 150px 150px;
}

@media only screen and (max-width: 50em) {
  body .section-aboutus .aboutus .section-aboutus-images figure {
    -ms-grid-rows: 190px 190px 190px;
    grid-template-rows: 190px 190px 190px;
    grid-row-gap: 3rem;
  }
}

body .section-aboutus .aboutus .section-aboutus-images figure img {
  position: relative;
  top: calc(var(--i) * -55px);
  left: calc(var(--i) * 90px);
  outline: 5px solid #fff;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  cursor: pointer;
}

@media only screen and (max-width: 50em) {
  body .section-aboutus .aboutus .section-aboutus-images figure img {
    top: 0px;
    left: 0px;
  }
}

body .section-aboutus .aboutus .section-aboutus-images figure img:hover {
  z-index: calc(var(--total-stack-size) - var(--i));
  -webkit-transform: scale(1.1);
  transform: scale(1.1);
}

@media only screen and (max-width: 50em) {
  body .section-aboutus .aboutus .section-aboutus-images figure img:hover {
    -webkit-transform: none;
    transform: none;
  }
}

body .section-aboutus .aboutus .section-aboutus-info {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
}

body .section-aboutus .aboutus .section-aboutus-info h2 {
  margin-bottom: 1rem;
  text-transform: uppercase;
}

body .section-aboutus .aboutus .section-aboutus-info p {
  margin-bottom: 2rem;
}

body .section-ourteam {
  padding: clamp(4rem, 10vw, 12rem) 0;
}

body .section-ourteam .ourteam {
  padding: 2rem 3rem;
}

body .section-ourteam .ourteam .title {
  text-align: center;
  text-transform: uppercase;
  margin-bottom: 40px;
}

body .section-ourteam .ourteam .team-members {
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: (minmax(min-content, 1fr)) [var];
  grid-template-columns: repeat(
    var(--four-col-layout),
    minmax(-webkit-min-content, 1fr)
  );
  grid-template-columns: repeat(
    var(--four-col-layout),
    minmax(min-content, 1fr)
  );
  grid-column-gap: 5rem;
  grid-row-gap: 5rem;
  -webkit-box-pack: stretch;
  -ms-flex-pack: stretch;
  justify-content: stretch;
  margin-top: 10px;
}

body .section-ourteam .ourteam .team-members .team-member {
  cursor: pointer;
  height: 300px;
  position: relative;
  overflow: hidden;
}

body .section-ourteam .ourteam .team-members .team-member img {
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
  position: absolute;
}

body
  .section-ourteam
  .ourteam
  .team-members
  .team-member
  .team-memmber-info
  .member-name {
  padding: 1rem 0.8rem;
  background-color: var(--color-yellow);
  font-size: 1.5rem;
  position: absolute;
  padding-right: 40px;
  bottom: 0px;
  left: 0px;
  z-index: 4;
  -webkit-clip-path: polygon(0 0, 100% 0, 70% 100%, 0% 100%);
  clip-path: polygon(0 0, 100% 0, 70% 100%, 0% 100%);
  color: #000;
  font-weight: 600;
}

body
  .section-ourteam
  .ourteam
  .team-members
  .team-member
  .team-memmber-info
  .member-desg {
  font-style: italic;
  position: absolute;
  padding: 1rem 0.8rem;
  font-size: 1.5rem;
  background-color: var(--color-black-light-text);
  width: 100%;
  bottom: 0px;
  text-align: end;
  z-index: 3;
  right: 0px;
}

body .section-ourteam .ourteam .team-members .team-member:hover .member-desc {
  position: absolute;
  z-index: 2;
  left: 0%;
  top: 0px;
}

body .section-ourteam .ourteam .team-members .team-member .member-desc {
  width: 100%;
  height: 100%;
  position: absolute;
  z-index: 2;
  left: 100%;
  -webkit-backdrop-filter: blur(8px);
  backdrop-filter: blur(8px);
  background-color: rgba(20, 20, 20, 0.58);
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  padding: 3rem;
  font-size: 1.8rem;
  top: 0px;
  -webkit-transition: all 0.5s ease;
  transition: all 0.5s ease;
}

body .section-memberships {
  padding: clamp(4rem, 10vw, 8rem) 0;
}

body .section-memberships .memberships {
  padding: 3rem 3rem;
  position: relative;
}

body .section-memberships .memberships .title {
  text-align: center;
  text-transform: uppercase;
  margin-bottom: 40px;
}

body .section-memberships .memberships .classes {
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: (minmax(min-content, 1fr)) [var];
  grid-template-columns: repeat(
    var(--three-col-layout),
    minmax(-webkit-min-content, 1fr)
  );
  grid-template-columns: repeat(
    var(--three-col-layout),
    minmax(min-content, 1fr)
  );
  grid-column-gap: 10rem;
  grid-row-gap: 5rem;
  -ms-flex-pack: distribute;
  justify-content: space-around;
  margin-top: 20px;
  margin: 20px 70px;
}

@media only screen and (max-width: 50em) {
  body .section-memberships .memberships .classes {
    margin: 0px;
  }
}

body .section-memberships .memberships .classes .class {
  cursor: pointer;
  background-color: #414141;
  z-index: 10;
  -webkit-box-shadow: rgba(0, 0, 0, 0.16) 0px 10px 36px 0px,
    rgba(0, 0, 0, 0.06) 0px 0px 0px 1px;
  box-shadow: rgba(0, 0, 0, 0.16) 0px 10px 36px 0px,
    rgba(0, 0, 0, 0.06) 0px 0px 0px 1px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

body .section-memberships .memberships .classes .class .class-name {
  padding: 1.5rem;
  margin-top: 10px;
  text-transform: uppercase;
}

body .section-memberships .memberships .classes .class .class-price {
  font-size: 1.8rem;
  margin-bottom: 20px;
}

body .section-memberships .memberships .classes .class ul {
  padding: 2rem;
  list-style: none;
}

body .section-memberships .memberships .classes .class ul li {
  margin: 15px 0px;
}

body .section-memberships .memberships .classes .class a {
  width: 100%;
  padding: 15px;
  color: #000;
  font-weight: 600;
  text-align: center;
  font-size: 1.8rem;
  background-color: var(--color-yellow);
}

body .section-memberships .memberships .classes .class a:hover {
  background-color: var(--color-yellow-dark);
}

body .section-memberships .memberships .classes .class:hover {
  -webkit-transform: scale(1.05);
  transform: scale(1.05);
  -webkit-box-shadow: rgba(0, 0, 0, 0.29) 0px 10px 36px 0px,
    rgba(0, 0, 0, 0.218) 0px 0px 0px 1px;
  box-shadow: rgba(0, 0, 0, 0.29) 0px 10px 36px 0px,
    rgba(0, 0, 0, 0.218) 0px 0px 0px 1px;
}

body .section-reviews {
  padding: clamp(4rem, 10vw, 8rem) 0;
}

body .section-reviews .reviews {
  padding: 2rem 3rem;
  position: relative;
}

body .section-reviews .reviews .title {
  text-align: center;
  text-transform: uppercase;
  margin-bottom: 40px;
}

body .section-reviews .reviews .review {
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: (minmax(min-content, 1fr)) [var];
  grid-template-columns: repeat(
    var(--three-col-layout),
    minmax(-webkit-min-content, 1fr)
  );
  grid-template-columns: repeat(
    var(--three-col-layout),
    minmax(min-content, 1fr)
  );
  grid-column-gap: 10rem;
  grid-row-gap: 5rem;
  -ms-flex-pack: distribute;
  justify-content: space-around;
  margin: 20px 0px;
}

body .section-reviews .reviews .review .review-info {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

body .section-reviews .reviews .review .review-info .review-image {
  width: 145px;
  height: 145px;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  position: relative;
  border-radius: 100%;
  overflow: hidden;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  cursor: pointer;
}

body .section-reviews .reviews .review .review-info .review-image img {
  -webkit-transform: rotate(-90deg);
  transform: rotate(-90deg);
  border-radius: 100%;
  z-index: 15;
  border: 2px solid var(--color-black);
}

body .section-reviews .reviews .review .review-info .review-image:before {
  content: "";
  width: 100%;
  height: 50%;
  z-index: 11;
  position: absolute;
  background-color: #fae500;
  -webkit-transition: 0.3s;
  transition: 0.3s;
  bottom: 0px;
}

body .section-reviews .reviews .review .review-info .review-image:after {
  content: "";
  width: 100%;
  height: 100%;
  position: absolute;
  border-radius: 100%;
  background-image: -webkit-gradient(
    linear,
    left top,
    right top,
    from(#212121),
    color-stop(rgba(179, 143, 0, 0.174)),
    to(#fae500)
  );
  background-image: linear-gradient(
    90deg,
    #212121,
    rgba(179, 143, 0, 0.174),
    #fae500 100%
  );
}

body .section-reviews .reviews .review .review-info .review-image:hover:before {
  width: 100%;
  height: 100%;
}

body .section-reviews .reviews .review .review-info .review-details {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

body
  .section-reviews
  .reviews
  .review
  .review-info
  .review-details
  div:first-child {
  font-size: 1.8rem;
  padding: 1rem;
}

body
  .section-reviews
  .reviews
  .review
  .review-info
  .review-details
  div:last-child {
  text-align: justify;
  position: relative;
  font-style: italic;
}

body
  .section-reviews
  .reviews
  .review
  .review-info
  .review-details
  div:last-child:before {
  top: -20px;
  left: -25px;
  position: absolute;
  content: "\201F";
  font-size: 5rem;
}

body .section-contact {
  position: relative;
}

body .section-contact .contact {
  overflow: hidden;
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: (minmax(min-content, 1fr)) [var];
  grid-template-columns: repeat(
    var(--two-col-layout),
    minmax(-webkit-min-content, 1fr)
  );
  grid-template-columns: repeat(
    var(--two-col-layout),
    minmax(min-content, 1fr)
  );
  grid-column-gap: 1rem;
  grid-row-gap: 1rem;
  -ms-flex-pack: distribute;
  justify-content: space-around;
}

body .section-contact .contact .contactus {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: stretch;
  -ms-flex-pack: stretch;
  justify-content: stretch;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  padding: 2rem 1rem;
}

body .section-contact .contact .contactus form {
  width: 100%;
}

body .section-contact .contact .contactus form input::-webkit-outer-spin-button,
body
  .section-contact
  .contact
  .contactus
  form
  input::-webkit-inner-spin-button {
  -webkit-appearance: none;
  margin: 0;
}

body .section-contact .contact .contactus form input,
body .section-contact .contact .contactus form textarea {
  margin: 0;
  color: #fff;
  font-size: 1.8rem;
  padding: 10px 5px;
  width: 100%;
  background-color: transparent;
  border: 0px;
  outline: none;
  position: relative;
}

body .section-contact .contact .contactus form textarea {
  min-height: 50px;
}

body .section-contact .contact .contactus form .class-input {
  position: relative;
  margin: 20px 0px;
  overflow: hidden;
  border-bottom: 1px solid #6a6a6a;
  cursor: text;
}

body .section-contact .contact .contactus form .class-input:after {
  content: "";
  position: absolute;
  width: 100%;
  height: 0%;
  border-bottom: 2px solid rgb(7, 251, 247);
  left: 0px;
  bottom: 0px;
  -webkit-transform: translateX(-100%);
  transform: translateX(-100%);
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

body .section-contact .contact .contactus form .class-input:hover:after {
  -webkit-transform: translateX(0%);
  transform: translateX(0%);
}

body .section-contact .contact .contactus form button {
  padding: 10px 30px;
  font-size: 1.5rem;
}

body .section-contact .contact .contactus form button:hover {
  background-color: var(--color-yellow);
  color: #464646;
}

body .section-contact .contact .map {
  width: 100%;
  height: 450px;
}

body .section-contact .contact .map iframe {
  width: 100%;
  height: 100%;
}

body .section-footer {
  padding: clamp(4rem, 10vw, 8rem) 0;
  background-color: #161616;
}

body .section-footer .footer-box {
  margin: auto;
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: (minmax(min-content, 1fr)) [var];
  grid-template-columns: repeat(
    var(--three-col-layout),
    minmax(-webkit-min-content, 1fr)
  );
  grid-template-columns: repeat(
    var(--three-col-layout),
    minmax(min-content, 1fr)
  );
  grid-column-gap: 10rem;
  grid-row-gap: 5rem;
  -ms-flex-pack: distribute;
  justify-content: space-around;
  padding: 30px 30px;
}

body .section-footer .footer-box .contact-details .contact-company-address {
  font-size: 1.8rem;
  margin: 10px 0px;
}

body .section-footer .footer-box .contact-social-links {
  cursor: pointer;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  gap: 4rem;
}

body .section-footer .footer-box .footer-nav h3 {
  margin: 10px 0px;
}

body .section-footer .footer-box .footer-nav li {
  font-size: 1.7rem;
  list-style: none;
}

body .section-footer .footer-box .newsletter h3 {
  margin: 10px 0px;
}

body .section-footer .footer-box .newsletter input {
  padding: 8px 10px;
  width: 60%;
  background-color: #414141;
  margin-right: 10px;
  border: none;
  border-radius: 5px;
  color: #fff;
  font-size: 1.7rem;
  outline: none;
}

body .section-footer .footer-box .newsletter button {
  font-weight: 900;
  padding: 08px 20px;
}

body .section-footer .copyrights {
  cursor: pointer;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
}

body .section-footer .copyrights div {
  font-size: 1.8rem;
  margin: 20px;
}

body .offerModal {
  -webkit-animation: movemodel 0.5s forwards;
  animation: movemodel 0.5s forwards;
  -webkit-animation-delay: 1.5s;
  animation-delay: 1.5s;
  opacity: block;
  position: fixed;
  background-color: red;
  padding: 35px 35px;
  right: -80%;
  top: 50%;
  width: 420px;
  -webkit-transform: translate(50%, -50%);
  transform: translate(50%, -50%);
  z-index: 15;
  background: rgba(255, 252, 252, 0.14);
  border-radius: 16px;
  backdrop-filter: blur(15px);
  -webkit-backdrop-filter: blur(10px);
}

@media only screen and (max-width: 50em) {
  body .offerModal {
    display: none;
  }
}

body .offerModal .modal-content {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -ms-flex-pack: distribute;
  justify-content: space-around;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  align-items: center;
}

body .offerModal .modal-content h2 {
  font-size: 35px;
}

body .offerModal .modal-content p {
  font-size: 15px;
}

body .offerModal .modal-content h1 {
  color: #ff4646;
  font-weight: bolder;
}

body .offerModal .modal-content button {
  width: 180px;
  height: 40px;
  -webkit-clip-path: none;
  clip-path: none;
}

body .offerModal .modal-content .close-button {
  width: 150px;
  background-color: #414141;
  color: #f4ce14;
}

body .offerModal .modal-content .close-button:hover {
  background-color: #000;
}

body .offerModal .modal-content div {
  margin-top: 10px;
  gap: 15px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

[data-aos="image-rotateIn"] {
  -webkit-transform: rotate(360deg) scale(0.5);
  transform: rotate(360deg) scale(0.5);
  -webkit-transition-property: opacity, -webkit-transform;
  transition-property: opacity, -webkit-transform;
  transition-property: transform, opacity;
  transition-property: transform, opacity, -webkit-transform;
}

[data-aos="image-rotateIn"].aos-animate {
  -webkit-transform: rotate(90deg) scale(1);
  transform: rotate(90deg) scale(1);
}

@-webkit-keyframes onclick {
  0% {
    opacity: 0;
    -webkit-transform: scale(0);
    transform: scale(0);
  }
  100% {
    opacity: 1;
    -webkit-transform: scale(1);
    transform: scale(1);
  }
}

@keyframes onclick {
  0% {
    opacity: 0;
    -webkit-transform: scale(0);
    transform: scale(0);
  }
  100% {
    opacity: 1;
    -webkit-transform: scale(1);
    transform: scale(1);
  }
}

@-webkit-keyframes moveInLeft {
  0% {
    opacity: 0;
    -webkit-transform: translateX(-100px);
    transform: translateX(-100px);
  }
  100% {
    opacity: 1;
    -webkit-transform: translate(0);
    transform: translate(0);
  }
}

@keyframes moveInLeft {
  0% {
    opacity: 0;
    -webkit-transform: translateX(-100px);
    transform: translateX(-100px);
  }
  100% {
    opacity: 1;
    -webkit-transform: translate(0);
    transform: translate(0);
  }
}

@-webkit-keyframes moveInRight {
  0% {
    opacity: 0;
    -webkit-transform: translateX(100px);
    transform: translateX(100px);
  }
  100% {
    opacity: 1;
    -webkit-transform: translate(0);
    transform: translate(0);
  }
}

@keyframes moveInRight {
  0% {
    opacity: 0;
    -webkit-transform: translateX(100px);
    transform: translateX(100px);
  }
  100% {
    opacity: 1;
    -webkit-transform: translate(0);
    transform: translate(0);
  }
}

@-webkit-keyframes movemodel {
  0% {
    right: -80%;
  }
  100% {
    right: 20%;
  }
}

@keyframes movemodel {
  0% {
    right: -80%;
  }
  100% {
    right: 20%;
  }
}
/*# sourceMappingURL=main.css.map */
import aos from "https://esm.sh/aos";
var movementStrength = 25;

const hero = document.getElementById("section-hero");

var modal = document.getElementById("offerModal");

var closeButton = document.querySelector(".close-button");

closeButton.onclick = function () {
  modal.style.display = "none";
};

hero.addEventListener("mousemove", (e) => {
  const div = document.createElement("div");
  div.classList.add("hero-section-mouseClick");
  div.style.left = e.pageX + "px";
  div.style.top = e.pageY + "px";
  const box = document.getElementById("section-hero");
  box.appendChild(div);
  setTimeout(() => {
    box.removeChild(div);
    div.remove();
  }, 200);
}
);
