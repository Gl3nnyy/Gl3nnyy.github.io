<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Delights</title>
    <!-- Add the Bootstrap CSS stylesheet link here -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  </head>
  <body>
    <header>
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Food Delights</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#menu">Menu</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact Us</a>
            </li>
          </ul>
        </div>
      </nav>
    </header>
    <body>
    <main>
      <section id="hero" class="jumbotron text-center">
        <h1 class="display-4">Welcome to Food Delights!</h1>
        <p class="lead">Looking for delicious food options? You've come to the right place! At Food Delights, we offer a wide range of meals that are both tasty and satisfying.</p>
        <hr class="my-4">
      </section>
      <section id="menu" class="container">
        <h2 class="text-center">Our Menu</h2>
        <p class="text-center">Check out our menu to see what we have to offer. From breakfast to dinner, we've got you covered! Our dishes are made with fresh, locally sourced ingredients and are always prepared with care.</p>
        <div class="row">
          <!-- Add your menu items here using Bootstrap cards -->
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="adobo.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Chicken Adobo</h5>
                <p class="card-text">Chicken Adobo is a traditional Filipino dish that is popular for its unique blend of salty, sweet, and sour flavors. 
                    The dish is made with chicken that is marinated in a mixture of vinegar, soy sauce, garlic, peppercorns, and bay leaves, and then simmered in the same marinade until the chicken is tender and flavorful. 
                    The dish is usually served with steamed rice and can be garnished with sliced green onions or chopped cilantro.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="karekare.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Kare-Kare</h5>
                <p class="card-text">Kare-kare is a traditional Filipino dish that is popular for its rich and savory peanut sauce. The dish is made with oxtail, beef tripe, and various vegetables such as eggplant, string beans, and bok choy, all of which are stewed in a peanut sauce made with ground roasted peanuts, rice flour, and annatto seeds.
                     The sauce is typically thick and creamy, and the flavors are further enhanced by the addition of shrimp paste or bagoong.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="sisig.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Sisig</h5>
                <p class="card-text">Sisig is a popular Filipino dish that originated in the Pampanga province. It is typically made with parts of the pig's head, such as the cheeks, ears, and snout, that are boiled, grilled, or fried, and then chopped into small pieces. The meat is then mixed with onions, garlic, chili peppers, and calamansi juice, which gives it a tangy and slightly sour flavor. 
                    Sisig is often served on a sizzling plate and topped with a raw egg that is mixed into the hot meat just before eating, creating a rich and creamy texture.
                </p>
              </div>
            </div>
          </div>
    </section>
    <hr>
    <section id="contact" class="container">
        <h2 class="text-center">Contact Us</h2>
        <br>
        <h3 class="text-center">09123456789</h3>
        <br>
        <h3 class="text-center">1234-421-234</h3>
        <br>
    </section>
    </body>
    </html>
