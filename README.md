# Gym-Advisor
html code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Gym Advisor</title>
    <link rel="stylesheet" href="gym.css" />
    <!-- insert font awesome icon CDN link here -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css"
      integrity="sha512-5A8nwdMOWrSz20fDsjczgUidUBR8liPYU+WymTZP1lmY9G6Oc7HlZv156XqnsgNUzTyMefFTcsFH/tnJE/+xBg=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
  </head>
  <body>
    <!-----------------------navigation bar-------------------------->
    <div class="navbar">
      <a href="#" class="logo">F<b>R</b>.</a>
      <div class="toggle" onclick="navToggle();"></div>
      <ol>
        <li><a href="#home " onclick="navToggle();">home</a></li>
        <li><a href="#about" onclick="navToggle();">about</a></li>
        <li><a href="#workout" onclick="navToggle();">workout</a></li>
        <li><a href="#trainers" onclick="navToggle();">trainer</a></li>
        <li><a href="#diet" onclick="navToggle();">diet</a></li>
        <li><a href="#contact" onclick="navToggle();">contact</a></li>
      </ol>
    </div>

    <section id="home" class="home view">
      <div class="highlights">
        <h3>Feel the poweer with</h3>
        <h1><b>FIT</b>ROOM</h1>
        <p class="tagline">
          "Elevate Your Fitness Journey with Gym Advisor: Your Path to Strength,
          Health, and Transformation."
        </p>
        <button class="join">Join Now</button>
      </div>
      <div class="banner"></div>
    </section>

    <!------------------------------About section----------------------->
    <section id="about" class="about view">
      <div class="main">
        <h2><span>A</span>bout Us</h2>
        <h6>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat
          labore pariatur porro.
        </h6>
      </div>
      <div class="content">
        <div class="cols">
          <p>
            <b>W</b>elcome to our fitness haven -your ultimate destination for
            expert guidance on all things gym-related! Our site is a
            comprehensive resource designed to empower fitness enthusiasts of
            all levels with valuable advice and tips. Whether you're a seasoned
            gym-goer or just starting your fitness journey, we've got you
            covered.Discover a wealth of information curated by experienced
            fitness advisors who are passionate about helping you achieve your
            health and wellness goals. From workout routines and nutrition plans
            to recovery strategies and the latest fitness trends, our site is
            your go-to hub for reliable and practical advice.F
          </p>
          <a href="#">more</a>
        </div>
        <div class="cols">
          <div class="box">
            <img src="About.jpg" alt="" />
          </div>
        </div>
      </div>
    </section>

    <!------------------------------ Workout section ------------------------------>
    <section id="workout" class="workout view">
      <div class="main">
        <h2><span>W</span>orkout</h2>
        <h6>
          "Unleash Your Strength: Elevate Every Workout with Passion and
          Purpose."
        </h6>
      </div>

      <div class="content">
        <div class="frame">
          <div class="box">
            <img src="workout1.jpg" alt="" />
          </div>
          <div class="title">Cardio</div>
          <p>
            "Rev up your cardio routine with high-intensity intervals for
            maximum calorie burn and heart health. Keep it dynamic, stay
            consistent, and let your endurance soar.
          </p>
        </div>

        <div class="frame">
          <div class="box">
            <img src="workout2.jpg" alt="" />
          </div>
          <div class="title">Weight lifting</div>
          <p>
            "Elevate your gains by focusing on proper form and gradually
            increasing weights. Consistency is key; challenge yourself, but
            always prioritize technique."
          </p>
        </div>

        <div class="frame">
          <div class="box">
            <img src="workout3.jpg" alt="" />
          </div>
          <div class="title">Leg exercise</div>
          <p>
            "Activate those leg muscles with compound exercises like squats and
            lunges. Don't forget to incorporate targeted isolation movements for
            a well-rounded and effective leg day.
          </p>
        </div>

        <div class="frame">
          <div class="box">
            <img src="workout4.jpg" alt="" />
          </div>
          <div class="title">Muscles Building</div>
          <p>
            "Fuel your muscles with a balanced diet rich in protein, and
            optimize growth by incorporating compound exercises into your
            routine. Prioritize rest and recovery for optimal muscle building
            results."
          </p>
        </div>
        <div class="frame">
          <div class="box">
            <img src="workout5.jpg" alt="" />
          </div>
          <div class="title">Strength Building</div>
          <p>
            "Build strength efficiently with compound exercises like squats and
            deadlifts. Progress by gradually increasing weights, and ensure
            proper form for maximum effectiveness."
          </p>
        </div>
        <div class="frame">
          <div class="box">
            <img src="workout6.jpg" alt="" />
          </div>
          <div class="title">Abs workout</div>
          <p>
            "Sculpt strong abs with a mix of targeted exercises like planks and
            crunches. Consistency is crucial—incorporate core workouts into your
            routine for a toned, resilient midsection."
          </p>
        </div>
      </div>
    </section>

    <!------------------------------- Trainers section----------------------------->
    <section id="trainers" class="trainers view">
      <div class="main">
        <h2><span>B</span>est <span>T</span>rainers</h2>
        <h6>
          "Empowering Your Best: Where Fitness Meets Inspiration."
        </h6>
      </div>
      <div class="content">
        <div class="frame">
          <div class="box">
            <img src="trainer1.jpg" alt="" />
          </div>
          <div class="headline">
            <div class="title">Chris Powell</div>
            <div class="icons">
              <i class="fa fa-facebook"></i>
              <i class="fa fa-twitter"></i>
              <i class="fa fa-linkedin"></i>
            </div>
          </div>
          <p>
            Known for his appearances on the TV show "Extreme Weight Loss,"
            Chris Powell is a renowned fitness expert and transformation
            specialist.
          </p>
          <a href="#">Explore</a>
        </div>

        <div class="frame">
          <div class="box">
            <img src="trainer2.jpg" alt="" />
          </div>
          <div class="headline">
            <div class="title">Tony Horton</div>
            <div class="icons">
              <i class="fa fa-facebook"></i>
              <i class="fa fa-twitter"></i>
              <i class="fa fa-linkedin"></i>
            </div>
          </div>
          <p>
            The mastermind behind the P90X workout series, Tony Horton is a
            seasoned fitness trainer with a focus on intense and varied exercise
            routines
          </p>
          <a href="#">Explore</a>
        </div>

        <div class="frame">
          <div class="box">
            <img src="trainer3.jpg" alt="" />
          </div>
          <div class="headline">
            <div class="title">Kayla Itsines</div>
            <div class="icons">
              <i class="fa fa-facebook"></i>
              <i class="fa fa-twitter"></i>
              <i class="fa fa-linkedin"></i>
            </div>
          </div>
          <p>
            Creator of the Bikini Body Guide (BBG) program, Kayla Itsines has
            gained international recognition for her effective and accessible
            workout routines.
          </p>
          <a href="#">Explore</a>
        </div>

        <div class="frame">
          <div class="box">
            <img src="trainer4.jpg" alt="" />
          </div>
          <div class="headline">
            <div class="title">Jillian Michaels</div>
            <div class="icons">
              <i class="fa fa-facebook"></i>
              <i class="fa fa-twitter"></i>
              <i class="fa fa-linkedin"></i>
            </div>
          </div>
          <p>
            Famous for her role on "The Biggest Loser," Jillian Michaels is a
            fitness trainer, author, and life coach, providing motivational and
            effective workout programs.
          </p>
          <a href="#">Explore</a>
        </div>
      </div>
    </section>

    <!---------------------------------Diet Section---------------------------------------------->
    <section id="diet" class="diet view">
      <div class="main">
        <h2><span>S</span>pecial <span>D</span>iet</h2>
        <h6>
          
"Elevate Your Plate: Crafting Health, One Meal at a Time."S
        </h6>
      </div>

      <div class="content">
        <div class="row">
          <div class="cols a">
            <div class="heading">Boiled Chicken</div>
            <p>
              oiled chicken is a nutritious and lean protein source that
              supports muscle growth and repair. Being low in calories and high
              in essential nutrients, it promotes a healthy diet. The cooking
              method retains more vitamins and minerals compared to other
              methods, and its versatility makes it a versatile ingredient for
              various dishes. Additionally, boiling helps maintain the meat's
              moisture content, contributing to better digestibility and
              hydration.It's important to note that the overall health benefits
              of boiled chicken are also influenced by factors such as the
              cooking method, portion size, and the overall balance of your
              diet. It's advisable to pair boiled chicken with a variety of
              vegetables, whole grains, and other nutrient-rich foods to create
              a well-rounded and nutritious meal.
            </p>
          </div>
          <div class="cols b">
            <div class="boxes">
              <img src="diet1.jpg" alt="" />
            </div>
          </div>
        </div>

        <div class="row">
          <div class="cols a">
            <div class="heading">Bread Salad</div>
            <p>
              Bread salad, often made with a mix of fresh vegetables, herbs, and
              cubes of toasted or stale bread, offers a delightful combination
              of flavors and textures. This dish provides a balance of
              carbohydrates from the bread, essential vitamins and minerals from
              the vegetables, and healthy fats from dressings or added
              ingredients. Additionally, it's a versatile and customizable
              option that can be a tasty way to incorporate a variety of
              nutrient-rich foods into your diet.
            </p>
          </div>
          <div class="cols b">
            <div class="boxes">
              <img src="diet2.jpg" alt="" />
            </div>
          </div>
        </div>

        <div class="row">
          <div class="cols a">
            <div class="heading">Dry Fruits</div>
            <p>
              Dried fruits, such as raisins, apricots, and dates, offer
              concentrated doses of essential nutrients like vitamins, minerals,
              and fiber. They provide a natural sweetness and are convenient for
              on-the-go snacking. Additionally, dried fruits can contribute to
              overall well-being by supporting digestion, providing energy, and
              supplying antioxidants that help combat oxidative stress in the
              body. However, it's important to consume them in moderation due to
              their concentrated sugar content.
            </p>
          </div>
          <div class="cols b">
            <div class="boxes">
              <img src="diet3.jpg" alt="" />
            </div>
          </div>
        </div>

        <div class="row">
          <div class="cols a">
            <div class="heading">Heathy Fruits</div>
            <p>
              Healthy fruits, such as berries, apples, and citrus fruits, come
              with a host of benefits for overall well-being. Berries, like
              blueberries and strawberries, are rich in antioxidants that help
              combat oxidative stress, supporting heart health and reducing
              inflammation. Apples are a good source of fiber, promoting
              digestive health and aiding in weight management. Citrus fruits,
              such as oranges and grapefruits, are high in vitamin C,
              contributing to a strong immune system and healthy skin. Bananas
              offer a quick energy boost due to their natural sugars and are a
              good source of potassium, which supports heart and muscle
              function. Kiwi is packed with vitamin K, vitamin C, and dietary
              fiber, promoting healthy digestion and skin. Avocado, though
              technically a berry, is often categorized as a healthy fruit and
              is high in monounsaturated fats, contributing to heart health and
              satiety.
            </p>
          </div>
          <div class="cols b">
            <div class="boxes">
              <img src="diet4.jpg" alt="" />
            </div>
          </div>
        </div>

        <div class="row">
          <div class="cols a">
            <div class="heading">Fresh Juice</div>
            <p>
              Fruit juice, when consumed in moderation and as part of a balanced
              diet, offers several benefits. It provides a convenient and tasty
              way to increase your intake of essential vitamins and minerals,
              such as vitamin C and potassium. Fruit juices can contribute to
              hydration, especially if water content is high, aiding in
              maintaining overall fluid balance. Additionally, the natural
              sugars found in fruit juices can provide a quick energy source,
              making them a suitable option for a pre-workout boost. Some fruit
              juices, especially those without added sugars, may contain
              antioxidants that help combat oxidative stress and inflammation in
              the body.
            </p>
          </div>
          <div class="cols b">
            <div class="boxes">
              <img src="diet5.jpg" alt="" />
            </div>
          </div>
        </div>

        <div class="row">
          <div class="cols a">
            <div class="heading">Some Proteins</div>
            <p>
              Proteins play a vital role in maintaining and building tissues,
              supporting muscle growth, facilitating enzyme function for
              essential processes, contributing to a healthy immune system,
              regulating hormones, aiding in the transportation of substances
              like oxygen, helping maintain fluid balance and pH levels, acting
              as an energy source when needed, and promoting satiety for weight
              management.
            </p>
          </div>
          <div class="cols b">
            <div class="boxes">
              <img src="diet6.jpg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-----------------------------Contact Section--------------------------------->
    <section id="contact" class="contact view">
      <div class="main">
        <h2><span>C</span>ontact <span>U</span>s</h2>
        <h6>
          "Connecting with You, Anytime, Anywhere – Reach Out and Let's Talk!"
        </h6>
      </div>

      <div class="content">
        <form>
          <input type="text" placeholder="user" />
          <input type="text" placeholder="Email" />
          <textarea rows="5" placeholder="what's on your mind"></textarea>
          <br />
          <input type="submit" value="Send" class="btn" />
        </form>
        <div class="bgimg"></div>
      </div>
    </section>

    <!-----------------------------Copyright----------------------------------------------------------->
    <section class="copyright">
      &copy; copyright <a href="#">WebkitCoding</a> 2023 | All Rights Reserved
    </section>

    <!-------------------------------Javascript code here----------------------------------------------->
    <script src="gym.js"></script>
  </body>
</html>



css code
/*-----------------------insert Google font--------------------------*/
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');
*{
    margin:0%;
    padding: 0%;
    font-family: 'Poppins',sans-serif;
    box-sizing: border-box;
    outline: none;
    color: #fff;
    scroll-behavior: smooth;
}

:root{
    --prime:#00ff34;
}
body{
    background-color: #131b2b;
}

/*-----------------------Style navbar--------------------------*/
.navbar{
    width: 100%;
    display: flex;
    position: fixed;
    padding: 30px 120px;
    background-color: transparent;
    justify-content: space-between;
    z-index: 1111;
    transition: 0.5s ease;
}
.navbar.sticky{
    padding: 6px 60px;
    background: #0c1518;
    box-shadow: 0 0 15px rgba(0,0,0,0.5);
}
.navbar.sticky .logo{
    font-size: 2em;
    color: var(--prime);
}
.navbar.sticky .logo B{
    color: #fff;
}
.logo{
    font-size: 2.8em;
    font-weight: 800;
    letter-spacing: 2px;
    text-transform: uppercase;
    text-decoration: none;
}
.logo B{
    color: var(--prime);
}
ol{
    display: flex;
    margin: auto 0;
}
ol li{
    list-style: none;
    margin-right: 20px;
}
ol li a{
    font-size: 20px;
    font-weight: 500;
    text-decoration: none;
    text-transform: capitalize;
}
ol li:hover a{
    color: var(--prime);
}





/* --------------common size for all section--------- */
.view{
    width: 100%;
    min-height: 80vh;
    position: relative;
}

.home{
    display: flex;
    min-height: 120vh;
    align-items: center;
    justify-content: center;
    clip-path: polygon(0 0 , 100% 0,100% 100%,80% 95%,0 100%);
}

.banner{
    height: 100%;
    width: 100%;
    position: absolute;
    background: url(banner.jpg);
    background-position: center;
    filter: brightness(40%);
}

.highlights{
    width: 70%;
    position: relative;
    display: inline-block;
    z-index: 11;
}
.highlights h3{
    display: inline;
    font-size: 2vw;
    padding: 5px 20px;
    font-weight: lighter;
    text-transform: capitalize;
    border-left: 6px solid var(--prime);
}
.highlights h1{
    font-size: 9vw;
    text-align: center;
    font-weight: normal;
}
.highlights b{
    color: var(--prime);
    font-weight: 800;
    font-family: sans-serif;
}
.highlights .tagline{
    color: #d7d7d7;
    font-size: 1.2vw;
    text-align: center;
    font-weight: normal;
}
.highlights .join{
    position: absolute;
    left: 50%;
    transform: translate(-50%);
    font-weight: 800;
    padding: 5px 20px;
    font-size: 1.5vw;
    margin-top: 1.2em;
    color: var(--prime);
    border: 2px solid var(--prime);
    border-radius: 50px;
    background: transparent;
    text-transform: uppercase;
    transform: 0.3s ease;
}
.highlights .join:hover{
    color: #fff;
    cursor: pointer;
    letter-spacing: 1.5px;
    background: var(--prime);
}


/* ---------------common style for all section------------------ */
.main{
    width: 100%;
    text-align: center;
    padding-bottom: 20px;
}

.main h2{
    font-size: 2.5vw;
    position: relative;
    text-align: center;
    padding-top: 100px;
    display: inline-block;
}
span{
    color: var(--prime);
}

.main h2:before{
    position: absolute;
    content: '';
    background: var(--prime);
    height: 3px;
    width: 30%;
    right: -15px;
    bottom: 0;
    border-radius: 50px;
}

.main h6{
    margin-top: 10px;
    font-size: 13px;
    font-family: sans-sarif;
    font-weight: lighter;
}

.content{
    position: relative;
    display: flex;
    width: 100%;
    padding: 0 30px;
    justify-content: center;
}

/* ---------------Style about section------------------ */
.about .content .cols{
    position: relative;
    width: 100%;
    height: 100%;
    padding: 20px 70px;
}
.about .content .cols p b{
   font-size: 20px;
   margin-right: 2px;
}

.about .content .cols a{
    position: relative;
    top: 20px;
    color: #fff;
    background: var(--prime);
    padding: 5px 20px;
    border-radius: 5px;
    text-decoration: none;
    text-transform: capitalize;
}
.about .content .cols a:hover{
    color: #000;
    background: #fff;
}
.about .content .cols .box{
    position: relative;
    height: 550px;
    box-shadow: 0 10px 10px rgba(0,0,0,0.5);
}
.about .content .cols .box img{
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
}




/* -------------------------Style workout section-------------------------------------------- */
.workout .content{
    flex-wrap: wrap;
}
.workout .main h6{
    font-size:1.5rem;
}

.workout .content .frame{
    position: relative;
    width: 350px;
    padding: 20px;
    margin: 10px;
    background: #222;
    box-shadow: 0 10px 15px rgba(0,0,0,0.5);
}
.workout .content .frame .box{
    position: relative;
    height: 200px;
    width: 100%;
    overflow: hidden;
}
.workout .content .frame .box img{
    position: absolute;
    height: 100%;
    width: 100%;
    object-fit: cover;
    filter: brightness(80%);
    transition: 0.2s ease-in;
}
.workout .content .frame .box:hover img{
    filter: brightness(100%);
    transform: scale(1.08);
}
.workout .content .frame .title{
    color: var(--prime);
    padding: 5px 0;
}
.workout .content .frame p{
    font-size: 0.8em;
}




/* -----------------------------Style Trainer Section--------------------------------- */
.trainers .content{
    flex-wrap: wrap;
}
.trainer .main h6{
    font-size: 1.5rem;
}

.trainers .content .frame{
    position: relative;
    width: 350px;
    padding: 20px;
    margin: 10px;
    background: #222;
    box-shadow: 0 10px 15px rgba(0,0,0,0.5);
}
.trainers .content .frame .box{
    position: relative;
    height: 200px;
    width: 100%;
    overflow: hidden;
}
.trainers .content .frame .box img{
    position: absolute;
    height: 100%;
    width: 100%;
    object-fit: cover;
    filter: grayscale(1);
    transition: 0.2s ease-in;
}
.trainers .content .frame .box:hover img{
    filter: grayscale(0);
    transform: scale(1.08);
}
.trainers.content .frame .title{
    color: var(--prime);
    padding: 5px 0;
}
.trainers .content .frame p{
    font-size: 0.8em;
}

.trainers .content .frame .headline{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 8px 0;
}

.trainers .content .frame .headline i{
    height: 22px;
    width: 22px;
    border: 1.5px solid #fff;
    border-radius: 50%;
    text-align: center;
    font-size: 12px;
    margin-right: 5px;
    cursor: pointer;
    line-height: 22px;
}
.trainers .content .frame .headline i:hover{
    border: 1.5px solid var(--prime);
    background: var(--prime);
}

.trainers .content .frame .headline .title{
    color: var(--prime);
    font-size: 1.2em;
}
.trainers .content .frame  p{
    font-size: 0.8em;
    position: relative;
    bottom: 5px;
}
.trainers .content .frame a{
    top: 10px;
    color: var(--prime);
    background: transparent;
    padding: 5px 20px;
    border: 1.5px solid var(--prime);
    border-radius: 5px;
    text-decoration: none;
    position: relative;
    text-transform: capitalize;
    transition: 0.2s ease;
}
.trainers .content .frame a:hover{
    color: #fff;
    background: var(--prime);
}

/* ---------------------------style diet section-------------------------------------------- */
.diet .content{
    flex-direction: column;
}
.diet .main h6{
    font-size: 1.5rem;
}
.diet .content .row{
   display: flex;
   position: relative;
   width: 100%;
   padding: 20px 0;
   justify-content: center;
}
.diet .content .row:nth-child(odd) .a{
    order: 2;
}
.diet .content .row .cols{
    position: relative;
    width: 600px;
    padding: 20px 50px;
}
.diet .content .row .cols .heading{
    font-size: 2em;
    color: #ff8502;
    text-transform: capitalize;
}
.diet .content .row:nth-child(odd)  .cols .heading{
    color: #02a3ff;
}
.diet .content .row .cols .boxes{
    position: relative;
    width: 100%;
    height: 350px;
    padding: 20px;
    border-radius: 8px;
    background: #fff;
    box-shadow: 0 10px 15px rgba(0,0,0,0.5);
}
.diet .content .row .cols .boxes img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}


/* ----------------------------------style contact section------------------------------ */
.contact .content{
    min-height: 100vh;
}
.contact .main h6{
    font-size: 1.5rem;
}
.contact .content form{
    margin: auto 0;
    width: 400px;
    height: 500px;
    padding: 20px;
    background: #fff;
    box-shadow: 0 10px 15px rgba(0,0,0,0.5)s;
    z-index: 1;
}
.contact .content form input{
    color: #222;
    width: 100%;
    height: 50px;
    padding: 0 10px;
    font-size: 18px;
    border: 1px solid #878787;
    border-radius: 4px;
    margin: 15px 0;
    background: transparent;
}
.contact .content form textarea{
    width: 100%;
    padding: 10px;
    color: #222;
    font-size: 18px;
    border: 1px solid #878787;
    border-radius: 4px;
    margin: 15px 0;
    background: transparent;
}
.contact .content form input:focus,
.contact .content form textarea:focus{
    border: 2px solid var(--prime);
    transition: 0.1s ease;
}
.contact .content form .btn{
    letter-spacing: 1px;
    width: 100px;
    display: inline-block;
    color: var(--prime);
    border-color: var(--prime);
    cursor: pointer;
    transition: 0.2s ease;
}
.contact .content form .btn:hover{
      background: var(--prime);
      color: #fff;
}
.contact .content .bgimg{
    position: absolute;
    height: 100%;
    width: 100%;
    background: url(bgimg.jpg);
    background-size: cover;
    background-position: center;
    filter: brightness(20%);
}

/* -------------------------------------------Style copyright area------------------------------------------------ */
.copyright{
    text-transform: capitalize;
    height: 40px;
    width: 100%;
    line-height: 40px;
    background: #222;
    text-align: center;
    font-size: 18px;
}
.copyright a{
    color: var(--prime);
    text-decoration: none;
    margin: 0 2px;
    font-weight: lighter;
}





/* ---------------------------------------make responsive ------------------------------------------*/
@media screen and (max-width:900px){
    .navbar{
        padding: 0 60px;
    }
    .navbar ol{
        display: none;
    }
    .navbar ol.active{
        top: 60px;
        left: 0;
        width: 100%;
        display: flex;
        position: fixed;
        background: #222;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        height: calc(100%);
    }
    .navbar ol.active li{
        margin: 8px;
    }
    .navbar ol.active li a{
        font-size: 25px;
    }
    .navbar .toggle{
        height: 25px;
        width: 25px;
        margin: auto 0;
        cursor: pointer;
        background: url(menubar.jpg);
        background-size: 25px;
        background-position: center;
        filter: invert(1);
        background-repeat: no-repeat;
    }

    .navbar .toggle.active{
        background: url(close.png);
        background-size: 40px;
        background-position: center;
        cursor: pointer;
        filter: invert(1);
    }
  
    .highlights h3{
        font-size: 3vw;
        padding: 5px 10px;
        border-left: 3px solid var(--prime);
    }
    .highlights h1{
        font-size: 16vw;
    }
    .highlights .join{
        font-size: 1.8vw;
        border: 1px solid var(--prime);
    }
    .main h2{
        font-size: 1.5rem;
    }
    .main h6{
        font-size: 10px;
    }
    .about .content{
        flex-direction: column;
    }
    .workout .content .frame{
        width: 350px;
        padding: 15px 15px 40px 15px;
        margin: 10px 5px;
    }
    .workout .content .frame .box{
        height: 200px;
    }
    .trainers .content .frame a{
     border: 1.5px solid var(--prime);
     padding: 3px 15px;
    }
    .diet .content .row{
        flex-direction: column;
    }
    .diet .content .row .cols{
        width: 100%;
    }
    .diet .content .row:nth-child(odd) .a{
        order: 0;
    }

    .diet .content .row .cols .heading{
        font-size: 1.5em;
    }
    .diet .content .row .cols p{
        font-size: 13px;
    }
    .diet .content .row .cols .boxes{
        width: 90%;
        margin: auto;
    }
}



javascript code
/*-----------------------insert Google font--------------------------*/
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');
*{
    margin:0%;
    padding: 0%;
    font-family: 'Poppins',sans-serif;
    box-sizing: border-box;
    outline: none;
    color: #fff;
    scroll-behavior: smooth;
}

:root{
    --prime:#00ff34;
}
body{
    background-color: #131b2b;
}

/*-----------------------Style navbar--------------------------*/
.navbar{
    width: 100%;
    display: flex;
    position: fixed;
    padding: 30px 120px;
    background-color: transparent;
    justify-content: space-between;
    z-index: 1111;
    transition: 0.5s ease;
}
.navbar.sticky{
    padding: 6px 60px;
    background: #0c1518;
    box-shadow: 0 0 15px rgba(0,0,0,0.5);
}
.navbar.sticky .logo{
    font-size: 2em;
    color: var(--prime);
}
.navbar.sticky .logo B{
    color: #fff;
}
.logo{
    font-size: 2.8em;
    font-weight: 800;
    letter-spacing: 2px;
    text-transform: uppercase;
    text-decoration: none;
}
.logo B{
    color: var(--prime);
}
ol{
    display: flex;
    margin: auto 0;
}
ol li{
    list-style: none;
    margin-right: 20px;
}
ol li a{
    font-size: 20px;
    font-weight: 500;
    text-decoration: none;
    text-transform: capitalize;
}
ol li:hover a{
    color: var(--prime);
}





/* --------------common size for all section--------- */
.view{
    width: 100%;
    min-height: 80vh;
    position: relative;
}

.home{
    display: flex;
    min-height: 120vh;
    align-items: center;
    justify-content: center;
    clip-path: polygon(0 0 , 100% 0,100% 100%,80% 95%,0 100%);
}

.banner{
    height: 100%;
    width: 100%;
    position: absolute;
    background: url(banner.jpg);
    background-position: center;
    filter: brightness(40%);
}

.highlights{
    width: 70%;
    position: relative;
    display: inline-block;
    z-index: 11;
}
.highlights h3{
    display: inline;
    font-size: 2vw;
    padding: 5px 20px;
    font-weight: lighter;
    text-transform: capitalize;
    border-left: 6px solid var(--prime);
}
.highlights h1{
    font-size: 9vw;
    text-align: center;
    font-weight: normal;
}
.highlights b{
    color: var(--prime);
    font-weight: 800;
    font-family: sans-serif;
}
.highlights .tagline{
    color: #d7d7d7;
    font-size: 1.2vw;
    text-align: center;
    font-weight: normal;
}
.highlights .join{
    position: absolute;
    left: 50%;
    transform: translate(-50%);
    font-weight: 800;
    padding: 5px 20px;
    font-size: 1.5vw;
    margin-top: 1.2em;
    color: var(--prime);
    border: 2px solid var(--prime);
    border-radius: 50px;
    background: transparent;
    text-transform: uppercase;
    transform: 0.3s ease;
}
.highlights .join:hover{
    color: #fff;
    cursor: pointer;
    letter-spacing: 1.5px;
    background: var(--prime);
}


/* ---------------common style for all section------------------ */
.main{
    width: 100%;
    text-align: center;
    padding-bottom: 20px;
}

.main h2{
    font-size: 2.5vw;
    position: relative;
    text-align: center;
    padding-top: 100px;
    display: inline-block;
}
span{
    color: var(--prime);
}

.main h2:before{
    position: absolute;
    content: '';
    background: var(--prime);
    height: 3px;
    width: 30%;
    right: -15px;
    bottom: 0;
    border-radius: 50px;
}

.main h6{
    margin-top: 10px;
    font-size: 13px;
    font-family: sans-sarif;
    font-weight: lighter;
}

.content{
    position: relative;
    display: flex;
    width: 100%;
    padding: 0 30px;
    justify-content: center;
}

/* ---------------Style about section------------------ */
.about .content .cols{
    position: relative;
    width: 100%;
    height: 100%;
    padding: 20px 70px;
}
.about .content .cols p b{
   font-size: 20px;
   margin-right: 2px;
}

.about .content .cols a{
    position: relative;
    top: 20px;
    color: #fff;
    background: var(--prime);
    padding: 5px 20px;
    border-radius: 5px;
    text-decoration: none;
    text-transform: capitalize;
}
.about .content .cols a:hover{
    color: #000;
    background: #fff;
}
.about .content .cols .box{
    position: relative;
    height: 550px;
    box-shadow: 0 10px 10px rgba(0,0,0,0.5);
}
.about .content .cols .box img{
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
}




/* -------------------------Style workout section-------------------------------------------- */
.workout .content{
    flex-wrap: wrap;
}
.workout .main h6{
    font-size:1.5rem;
}

.workout .content .frame{
    position: relative;
    width: 350px;
    padding: 20px;
    margin: 10px;
    background: #222;
    box-shadow: 0 10px 15px rgba(0,0,0,0.5);
}
.workout .content .frame .box{
    position: relative;
    height: 200px;
    width: 100%;
    overflow: hidden;
}
.workout .content .frame .box img{
    position: absolute;
    height: 100%;
    width: 100%;
    object-fit: cover;
    filter: brightness(80%);
    transition: 0.2s ease-in;
}
.workout .content .frame .box:hover img{
    filter: brightness(100%);
    transform: scale(1.08);
}
.workout .content .frame .title{
    color: var(--prime);
    padding: 5px 0;
}
.workout .content .frame p{
    font-size: 0.8em;
}




/* -----------------------------Style Trainer Section--------------------------------- */
.trainers .content{
    flex-wrap: wrap;
}
.trainer .main h6{
    font-size: 1.5rem;
}

.trainers .content .frame{
    position: relative;
    width: 350px;
    padding: 20px;
    margin: 10px;
    background: #222;
    box-shadow: 0 10px 15px rgba(0,0,0,0.5);
}
.trainers .content .frame .box{
    position: relative;
    height: 200px;
    width: 100%;
    overflow: hidden;
}
.trainers .content .frame .box img{
    position: absolute;
    height: 100%;
    width: 100%;
    object-fit: cover;
    filter: grayscale(1);
    transition: 0.2s ease-in;
}
.trainers .content .frame .box:hover img{
    filter: grayscale(0);
    transform: scale(1.08);
}
.trainers.content .frame .title{
    color: var(--prime);
    padding: 5px 0;
}
.trainers .content .frame p{
    font-size: 0.8em;
}

.trainers .content .frame .headline{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 8px 0;
}

.trainers .content .frame .headline i{
    height: 22px;
    width: 22px;
    border: 1.5px solid #fff;
    border-radius: 50%;
    text-align: center;
    font-size: 12px;
    margin-right: 5px;
    cursor: pointer;
    line-height: 22px;
}
.trainers .content .frame .headline i:hover{
    border: 1.5px solid var(--prime);
    background: var(--prime);
}

.trainers .content .frame .headline .title{
    color: var(--prime);
    font-size: 1.2em;
}
.trainers .content .frame  p{
    font-size: 0.8em;
    position: relative;
    bottom: 5px;
}
.trainers .content .frame a{
    top: 10px;
    color: var(--prime);
    background: transparent;
    padding: 5px 20px;
    border: 1.5px solid var(--prime);
    border-radius: 5px;
    text-decoration: none;
    position: relative;
    text-transform: capitalize;
    transition: 0.2s ease;
}
.trainers .content .frame a:hover{
    color: #fff;
    background: var(--prime);
}

/* ---------------------------style diet section-------------------------------------------- */
.diet .content{
    flex-direction: column;
}
.diet .main h6{
    font-size: 1.5rem;
}
.diet .content .row{
   display: flex;
   position: relative;
   width: 100%;
   padding: 20px 0;
   justify-content: center;
}
.diet .content .row:nth-child(odd) .a{
    order: 2;
}
.diet .content .row .cols{
    position: relative;
    width: 600px;
    padding: 20px 50px;
}
.diet .content .row .cols .heading{
    font-size: 2em;
    color: #ff8502;
    text-transform: capitalize;
}
.diet .content .row:nth-child(odd)  .cols .heading{
    color: #02a3ff;
}
.diet .content .row .cols .boxes{
    position: relative;
    width: 100%;
    height: 350px;
    padding: 20px;
    border-radius: 8px;
    background: #fff;
    box-shadow: 0 10px 15px rgba(0,0,0,0.5);
}
.diet .content .row .cols .boxes img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}


/* ----------------------------------style contact section------------------------------ */
.contact .content{
    min-height: 100vh;
}
.contact .main h6{
    font-size: 1.5rem;
}
.contact .content form{
    margin: auto 0;
    width: 400px;
    height: 500px;
    padding: 20px;
    background: #fff;
    box-shadow: 0 10px 15px rgba(0,0,0,0.5)s;
    z-index: 1;
}
.contact .content form input{
    color: #222;
    width: 100%;
    height: 50px;
    padding: 0 10px;
    font-size: 18px;
    border: 1px solid #878787;
    border-radius: 4px;
    margin: 15px 0;
    background: transparent;
}
.contact .content form textarea{
    width: 100%;
    padding: 10px;
    color: #222;
    font-size: 18px;
    border: 1px solid #878787;
    border-radius: 4px;
    margin: 15px 0;
    background: transparent;
}
.contact .content form input:focus,
.contact .content form textarea:focus{
    border: 2px solid var(--prime);
    transition: 0.1s ease;
}
.contact .content form .btn{
    letter-spacing: 1px;
    width: 100px;
    display: inline-block;
    color: var(--prime);
    border-color: var(--prime);
    cursor: pointer;
    transition: 0.2s ease;
}
.contact .content form .btn:hover{
      background: var(--prime);
      color: #fff;
}
.contact .content .bgimg{
    position: absolute;
    height: 100%;
    width: 100%;
    background: url(bgimg.jpg);
    background-size: cover;
    background-position: center;
    filter: brightness(20%);
}

/* -------------------------------------------Style copyright area------------------------------------------------ */
.copyright{
    text-transform: capitalize;
    height: 40px;
    width: 100%;
    line-height: 40px;
    background: #222;
    text-align: center;
    font-size: 18px;
}
.copyright a{
    color: var(--prime);
    text-decoration: none;
    margin: 0 2px;
    font-weight: lighter;
}





/* ---------------------------------------make responsive ------------------------------------------*/
@media screen and (max-width:900px){
    .navbar{
        padding: 0 60px;
    }
    .navbar ol{
        display: none;
    }
    .navbar ol.active{
        top: 60px;
        left: 0;
        width: 100%;
        display: flex;
        position: fixed;
        background: #222;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        height: calc(100%);
    }
    .navbar ol.active li{
        margin: 8px;
    }
    .navbar ol.active li a{
        font-size: 25px;
    }
    .navbar .toggle{
        height: 25px;
        width: 25px;
        margin: auto 0;
        cursor: pointer;
        background: url(menubar.jpg);
        background-size: 25px;
        background-position: center;
        filter: invert(1);
        background-repeat: no-repeat;
    }

    .navbar .toggle.active{
        background: url(close.png);
        background-size: 40px;
        background-position: center;
        cursor: pointer;
        filter: invert(1);
    }
  
    .highlights h3{
        font-size: 3vw;
        padding: 5px 10px;
        border-left: 3px solid var(--prime);
    }
    .highlights h1{
        font-size: 16vw;
    }
    .highlights .join{
        font-size: 1.8vw;
        border: 1px solid var(--prime);
    }
    .main h2{
        font-size: 1.5rem;
    }
    .main h6{
        font-size: 10px;
    }
    .about .content{
        flex-direction: column;
    }
    .workout .content .frame{
        width: 350px;
        padding: 15px 15px 40px 15px;
        margin: 10px 5px;
    }
    .workout .content .frame .box{
        height: 200px;
    }
    .trainers .content .frame a{
     border: 1.5px solid var(--prime);
     padding: 3px 15px;
    }
    .diet .content .row{
        flex-direction: column;
    }
    .diet .content .row .cols{
        width: 100%;
    }
    .diet .content .row:nth-child(odd) .a{
        order: 0;
    }

    .diet .content .row .cols .heading{
        font-size: 1.5em;
    }
    .diet .content .row .cols p{
        font-size: 13px;
    }
    .diet .content .row .cols .boxes{
        width: 90%;
        margin: auto;
    }
}
