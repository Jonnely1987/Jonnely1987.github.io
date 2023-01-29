<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
  <style>
  
    .carousel-item {
        height: 40rem;
        background: #777;
        color:white;
        position: relative;
      }
      .carousel-item img{
        align-items: center;
        position: relative;
        background-position: center;
        background-size: cover;
      }
      .carousel-indicators{
        position: absolute;
        bottom: 0;
        left: 0;
        right:0;
      }
      h1{
        font-size: large;
        font: weight 10px;
        color: black;
        text-shadow: #777;
        justify-content: left;
      }
      p{
        font-size: large;
        font-weight: 3px;
        color: black;
        text-shadow: #777;
      }
      .blog-post{
        margin-bottom: 10rem;
      }
      .blog-post-title {
        font-size: 2.5rem;
      }
      .blog-post-meta {
         margin-bottom: 1.25rem;
         color: #727272;
      }

  </style>


</head>
<body>
  <header id="top">
    <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand" href="#"></a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="تبديل التنقل">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav me-auto mb-2 mb-md-0">
            <li class="nav-item">
              <a class="nav-link active" href="#aboutus">About Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#menu">Menu</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="#location">Contact</a>
            </li>
          </ul>
          <button class="btn btn-outline-danger">Order Now</button>
  </header>

    <div id="carouselExampleCaptions" class="carousel slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 3"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" aria-label="Slide 4"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item">
          <img src="https://images.unsplash.com/photo-1497888329096-51c27beff665?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=871&q=100" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h1>About us</h1>
            <p>Some representative placeholder content for the first slide.</p>
            <button class="btn btn-outline-success"a href="#aboutus">More</button>
          </div>
        </div>
        <div class="carousel-item">
          <img src="https://images.unsplash.com/photo-1496412705862-e0088f16f791?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=100" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h1>Our Food</h1>
            <p>Some representative placeholder content for the second slide.</p>
            <button class="btn btn-outline-success"a href="#menu">Order Now</button>
          </div>
        </div>
        <div class="carousel-item">
          <img src="https://images.unsplash.com/photo-1470337458703-46ad1756a187?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=869&q=100" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block" style="display: flex;">
            <h1>We are Located At</h1>
            <p>Some representative placeholder content for the third slide.</p>
            <button class="btn btn-outline-success"a href="#location">Location</button>
          </div>
        </div>
        <div class="carousel-item active">
          <img src="Final_background2.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block" style="display: flex;">
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </br>
  </br>
    <article class="blog-post" id="aboutus">
      <h2 class="blog-post-title mb-1">Our Food</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut alias expedita, 
        commodi neque repudiandae vero eum explicabo numquam vitae! Corrupti dolor labore modi vel voluptatem. 
        Modi, repellat nobis. Libero, commodi. This blog post shows a few different types of content that’s supported 
        and styled with Bootstrap. Basic typography, lists, tables, images, code, and more are all supported as expected.</p>
      <p>This is some additional paragraph placeholder content. It has been written to fill the available space and show how a longer 
        snippet of text affects the surrounding content. We'll repeat it often to keep the demonstration flowing, so be on the lookout for this e
        xact same string of text.</p>
      <p>This is some additional paragraph placeholder content. It has been written to fill the available space and show how a 
        longer snippet of text affects the surrounding content. We'll repeat it often to keep the demonstration flowing, so be on the lookout 
        for this exact same string of text.</p>
      <h2>About Us</h2>
      <p>This is some additional paragraph placeholder content. It's a slightly shorter version of the other highly repetitive body text used throughout. This is an example unordered list:</p>
    </article>
    <article class="blog-post" id="location">
      <h2 class="blog-post-title mb-1">We are Located At</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut alias expedita, 
        commodi neque repudiandae vero eum explicabo numquam vitae! Corrupti dolor labore modi vel voluptatem. 
        Modi, repellat nobis. Libero, commodi. This blog post shows a few different types of content that’s supported 
        and styled with Bootstrap. Basic typography, lists, tables, images, code, and more are all supported as expected.</p>
      <p>This is some additional paragraph placeholder content. It has been written to fill the available space and show how a longer 
        snippet of text affects the surrounding content. We'll repeat it often to keep the demonstration flowing, so be on the lookout for this e
        xact same string of text.</p>
      <p?>This is some additional paragraph placeholder content. It has been written to fill the available space and show how a 
        longer snippet of text affects the surrounding content. We'll repeat it often to keep the demonstration flowing, so be on the lookout 
        for this exact same string of text.</p>
    </article>

    <main>
      <section class="py-5 text-center container" id="menu" style="background-image: url(https://images.unsplash.com/photo-1515003197210-e0cd71810b5f?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=100);background-size: cover;">
        <div class="row py-lg-5">
          <div class="col-lg-6 col-md-8 mx-auto">
            <h1 class="fw-light">Menu</h1>
            <p class="lead text-muted">Here is our Menu</p>
            <p>
              <a href="#appetizers" class="btn btn-success my-2">Appetizers</a>
              <a href="#maincourse" class="btn btn-success my-2">Main Course</a>
            </p>
          </div>
        </div>
      </section>
      
      <br></br>
      <p id="appetizers">Appetizers</p>
  <div class="container">
    <div class="row gy-3">
      <div class="col-md-3">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1554502078-ef0fc409efce?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=784&q=100" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Tempura</h5>
              <p class="card-text">Freshly made garnish with veggies with secret sauce</p>
              <p>Php 150.00 / serving</p>
              <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1542528180-a1208c5169a5?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=877&q=100" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Fruit & Vegetable Salad</h5>
              <p class="card-text">A colorful plate of mix veggies and fruits vinegret sauce.</p>
              <p> Php 100.00 / serving</p>
              <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1464093515883-ec948246accb?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=859&q=100" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Resotto</h5>
              <p class="card-text">Hot resotto with lobster tail toppings</p>
              <p>Php. 250.00 / serving</p>
              <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1577906096429-f73c2c312435?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=100" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Tuna Sashimi</h5>
              <p class="card-text">Fresh tuna sashimi</p>
              <p>Php. 200.00 / serving</p>
              <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
    </div>
  </div>
  <br></br>
  <p id="maincourse">Main Course</p>
  <div class="container" >
    <div class="row gy-3">
      <div class="col-md-3">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1625862692743-3f57873bb37c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=100" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">>Pan Fried Salmon</h5>
            <p class="card-text">Crispy skin Salmon with sauted cherry tomatoes and sweet potato puree</p>
            <p>Php. 250.00 / serving</p>
            <a href="#" class="btn btn-primary">Add to Cart</a>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1644704265419-96ddaf628e71?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=100" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Steak</h5>
            <p class="card-text">Rib eye steak pan seard and grill to get smoky flavor, can request at your temperatur preferences</p>
            <p>Php. 350.00 / per serving</p>
            <a href="#" class="btn btn-primary">Add to Cart</a>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1626645738196-c2a7c87a8f58?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=100" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Fried Chicken</h5>
            <p class="card-text">Kanto style fried chicken with secret recipe gravy</p>
            <p>Php. 350.00 / serving</p>
            <a href="#" class="btn btn-primary">Add to Cart</a>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1633337474564-1d9478ca4e2e?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=871&q=100" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Pasta</h5>
            <p class="card-text">Freshly made pasta with squash puree and topping's with bacon and cheese</p>
            <p>Php. 250.00 / serving</p>
            <a href="#" class="btn btn-primary">Add to Cart</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</body>
<footer>
  <div class="card">
    <div class="card-header">
      Featured
    </div>
    <div class="card-body">
      <h5 class="card-title">Special title treatment</h5>
      <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
      <a href="#top" class="btn btn-primary">Go back to Top</a>
    </div>
  </div>
</footer>

</html>
