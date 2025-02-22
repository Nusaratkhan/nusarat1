<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Travel Website</title>
   <style>
    *{
    margin:0;
    padding: 0;
    width: 100%;
    scroll-behavior: smooth;
}
header{
    display: flex;
    padding: 10px;
    background-color: #4826070c;
    box-shadow: 0 0 10px rgba(131, 10, 10, 0.354);
    align-items: center;
}
.logo img{
    max-width: 20%;
}
.nav-menu ul{
    display:flex;

}
.nav-menu li{
    list-style: none;
    margin-right: 5px;
    padding: 5px;
}
.nav-menu a{
    text-decoration: none;
    font-family:inherit;
    font-size: 1.6rem;
    color:#121111;
    transition: all ease 0.3s;
 }
.nav-menu a:hover{
    color:rgb(153, 28, 49);
}
.nav-menu li:last-child{    
    margin-right:0;
}
.one{
    position:relative;
    height: 600px;
    overflow: hidden;
}
.main-image img{
    position: absolute ;
    top:0;
    left:0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index:-1;
 }
.content{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    color:white;
    text-align:center;
}
.content h1{
    font-size: 4rem;
}
.content p{
    font-size: 1.8rem;
    margin-bottom: 10px;
}
.button{
    display: inline-block;
    text-decoration: none;
    color: #fff;
    background-color: rgba(183, 75, 7, 0.865);
    padding: 12px 30px;
    border-radius: 50px;
    font-size: 1.6rem;
    width: 10%;
    transition: all ease 0.3s;

}
.button:hover{
    color:rgb(34, 32, 30);
}
.destinations{
    font-size: 2.4rem;
    margin: 40px 80px;
    text-align: center;
}
.destinations h2{
    margin-bottom: 40px;
}
.destination-grid{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 40px;
}
.destination-item img{
    width: 100%;
    height: 400px;
    object-fit: cover;
}
.destination-item{
    text-align: left;
}
.destination-item h3{
    font-size: 2rem;
}
.destination-item p{
    font-size: 1.4rem;
    line-height: 1;
}
.about{
    text-align: center;
    padding: 100px;
}
.about h3{
    font-size: 3rem;
}
.about p{
    font-size: 1.4rem;
    line-height: 1;
    margin-bottom: 40px;
}
.team-members{
    display: flex;
    justify-content:center;
}
.team-member img{
    width: 300px;
    height: 300px;
    margin: 20px;
    object-fit: cover;

}
.team-member h4{
    font-size: 2rem;

}
.contact{
    padding: 80px;
    text-align: center;
    background-color: #F7F7F7;
}
.contact h3{
    font-size: 3rem;
}
    .form{
    width: 100%;
}
.our{
    padding-top: 10px;
    background-color: rgba(240, 248, 255, 0.283);
}
input,textarea{
    width: 70%;
    padding: 10px;
    margin: 20px 0;
    border: none;
    box-shadow: 0 0 5px rgba(0,0,0, 0.1);
    border-radius: 5px;
    font-size: 1.4rem;
}
textarea{
    height: 200px;
}
.form button{
    display: inline-block;
    text-decoration: none;
    color: #fff;
    background-color: #ff7f50;
    padding: 12px 30px;
    border-radius: 50px;
    font-size: 1.6rem;
    border: none;
    transition: all ease 0.3s;
}
.form button:hover{
    background-color: #333;
}

footer{
    background-color: #333;
    color: #fff;
    display: flex;
    justify-content: space-between;
    padding: 20px;
    align-items: center;
}
.social-icons a{
    color: #fff;
    margin-right: 20px;
}
footer p{
    font-size: 1.4rem;
}
   </style>
  </head>
  <body>
    <header>
      <header>
        <div class="logo">
          <a href="#"><img src="travellogo.png" alt="logo" /></a>
        </div>
        <nav class="nav-menu">
          <ul>
            <li><a href="#Home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#destinations">Destinations</a></li>
            <li><a href="#hotels">Hotels</a></li>
            <li><a href="#foods">Food</a></li>
            <li><a href="#activites">Activities</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </nav>
      </header>
    </header>
    <main>
      <section class="one">
        <div class="main-image">
          <img src="background img.png" alt="main-image" />
        </div>
        <div class="content">
          <h1>Welcome to Our Travel Website</h1>
          <p>Discover amazing destinations and book your next trip with us.</p>
          <a href="#" class="button">Book Now</a>
        </div>
      </section>
      <!-- Destinations -->
      <section id="destinations" class="destinations">
        <h2>Popular Destinations</h2>
        <div class="destination-grid">
          <div class="destination-item">
            <img src="new york.png" alt="" />
            <h3>New York City</h3>
            <p>
              Visit the city that never sleeps and discover its iconic
              landmarks, world-class museums, and diverse neighborhoods.
            </p>
          </div>
          <div class="destination-item">
            <img src="ladakh.png" alt="ladakh" />
            <h3>Leh-Ladakh</h3>
            <p>
              Leh-Ladakh is a breathtaking region in northern India known
             for its dramatic landscapes, Buddhist monasteries, and adventure activities.
            </p>
          </div>
          <div class="destination-item">
            <img src="tokyo.png" alt="" />
            <h3>Tokyo</h3>
            <p>
              Explore the vibrant city of Tokyo and immerse yourself in its
              unique blend of ancient traditions and modern technology.
            </p>
          </div>
        </div>
      </section>
      <section id="hotels" class="destinations">
        <h2>Featured Hotels</h2>
        <div class="destination-grid">
          <div class="destination-item">
            <img src="hotel1.png" alt="" />
            <h3>The Ritz Carlton</h3>
            <p>
              Experience luxury accommodations and impeccable service at The
              Ritz Carlton, located in the heart of the city.
            </p>
          </div>
          <div class="destination-item">
            <img src="hotel2.png" alt="" />
            <h3>The Four Seasons</h3>
            <p>
              Relax in style at The Four Seasons, featuring breathtaking views,
              an award-winning spa, and gourmet dining options.
            </p>
          </div>
          <div class="destination-item">
            <img src="hotel3.png" alt="" />
            <h3>The Waldorf Astoria</h3>
            <p>
              Indulge in luxury at The Waldorf Astoria, a historic landmark
              hotel renowned for its elegance and sophistication.
            </p>
          </div>
        </div>
      </section>
        <section id="foods" class="destinations">
          <h2>Food Tours</h2>
          <div class="destination-grid">
          <div class="destination-item">
          <img src="briyani.png" alt="" />
          <h3> Biryani (India)</h3>
          <p>
              A fragrant rice dish cooked with spices, saffron, and marinated meat (or vegetables), 
              often served with raita (yogurt sauce).
          </p>
        </div>
        <div class="destination-item">
          <img src="pizza.png" alt="" />
          <h3>Pizza Napoletana(Italy)</h3>
          <p>A classic Italian pizza characterized by its soft, chewy crust and simple toppings of 
            San Marzano tomatoes,fresh mozzarella, basil, and olive oil.</p>
        </div>
        <div class="destination-item">
          <img src="baklava2.png" alt="" />
          <h3>Baklava (Turkey)</h3>
          <p>
            A rich, sweet pastry made of layers of filo dough filled with chopped nuts and sweetened 
            with honey or syrup, often flavored with cinnamon or rosewater.
          </p>
        </div>
        </div>
        </section>
      <section id="activites" class="destinations">
        <h2>Featured Activities</h2>
        <div class="destination-grid">
          <div class="destination-item">
            <img src="paraglding.png" alt="snorke" />
            <h3>Paragliding in Manali</h3>
            <p>
              Manali, a picturesque hill station in Himachal Pradesh, India, is renowned for its stunning 
              landscapes, adventure sports, and pleasant climate. One of the most exhilarating activities that attract adventure enthusiasts to this region is paragliding. 
            </p>
          </div>
          <div class="destination-item">
            <img src="hiking.png" alt="hiking" />
            <h3>Hiking the Grand Canyon</h3>
            <p>
              Explore the breathtaking beauty of the Grand Canyon on a
              guided hiking tour.
            </p>
          </div>
          <div class="destination-item">
            <img src="whale.png" alt="whale" />
            <h3>Whale Watching in Alaska</h3>
            <p>
              Experience the thrill of seeing majestic whales up close on a 
              scenic boat tour in Alaska.
            </p>
        </div>
      </section>
      <section id="about" class="about">
        <h3>About Us</h3>
        <p>
          Our company is dedicated to providing the best travel experiences to
          our customers. We specialize in creating custom<br> itineraries that cater
          to each individual's interests and preferences.Our mission is to empower 
          travelers by providing the best travel deals and personalized experiences.
        </p>
        <div class="team-members">
          <div class="team-member">
            <img src="nuss.png" alt=""/>
            <h4>Nusarat khan</h4>
            <p>Founder & CEO</p>
          </div>
          <div class="team-member">
            <img src="mahira.png" alt=""/>
            <h4>Mahira khan</h4>
            <p>Head of Operations</p>
          </div>
          <div class="team-member">
            <img src="riya.png" alt="" />
            <h4>Riya khan</h4>
            <p>Marketing Director</p>
          </div>
        </div>
      </section>
</body>
</html>
      <section id="contact" class="contact">
        <h3>Contact Us</h3>
        <div class="contact-info">
          <p>
            If you have any questions or would like to book a trip, please fill
            out the form below or contact us using the information provided.
          </p>
      <address class="address">
            <p>1234 Main St, Melbourne<br>
            USA </p>
            <p>Email:<a href="mailto:info@travelcompany.com">
              info@travelcompany.com</a></p>
            <p>Phone:<a href="tel:555-123-4567">555-123-4567</a></p>
      </address>
        </div>
        <form action="#" class="form">
          <div class="form-group">
            <input type="name" name="name" id="name" placeholder="Enter Your Name" />
          </div>
          <div class="form-group">
            <input type="email" name="email" id="email" placeholder="Enter Your Email"/>
          </div>
          <div class="form-group">
            <textarea name="textarea" id="textarea" cols="30" rows="10" placeholder="Message" ></textarea>
          </div>
          <button type="submit">Send Message</button>
        </form>
      </section>
      <footer>
        <div class="social-icons">
          <a href="https://www.facebook.com/" target="_blank">Facebook</a>
          <a href="https://www.twitter.com/" target="_blank">Twitter</a>
          <a href="https://www.instagram.com/" target="_blank">Instagram</a>
        </div>
        <p>&copy; 2023 Your Travel Website. All Rights Reserved.</p>
      </footer>
    </main>
  </body>
</html>
