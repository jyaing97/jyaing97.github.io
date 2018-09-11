<!DOCTYPE html>
<html>
<head>
	<h1>Three Bites</h1>
	<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
 <div class="topnav">
  <a class="active" href="#home">Home</a>
  <a href="#news">About</a>
  <a href="#contact">Recipes</a>
  <a href="#about">Favorite Places</a>
  <a href="#about">Reviews</a>
</div>
</head>

<!-- Container for the image gallery -->
<div class="container">

  <!-- Full-width images with number text -->
  <div class="mySlides">
	
/* When the screen is less than 600 pixels wide, hide all links, except for the first one ("Home"). Show the link that contains should open and close the topnav (.icon) */
@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

/* The "responsive" class is added to the topnav with JavaScript when the user clicks on the icon. This class makes the topnav look good on small screens (display the links vertically instead of horizontally) */
@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive a.icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
}
    <div class="numbertext">1 / 6</div>
      <img src="https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&ved=2ahUKEwiExuDckLLdAhVlTt8KHVE3AU4QjRx6BAgBEAU&url=https%3A%2F%2Fwww.cnn.com%2Fspecials%2Fhealth%2Ffood-diet&psig=AOvVaw1A5oxRj51unjZYNdALDZ2Z&ust=1536727105887859" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
      <img src="https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&ved=2ahUKEwjYkuzykLLdAhVxg-AKHbmJCzcQjRx6BAgBEAU&url=https%3A%2F%2Fwww.angelfoodmn.com%2F&psig=AOvVaw1A5oxRj51unjZYNdALDZ2Z&ust=1536727105887859" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 6</div>
      <img src="https://www.telegraph.co.uk/content/dam/business/2018/01/17/pizza_trans_NvBQzQNjv4BqZgEkZX3M936N5BQK4Va8RWtT0gK_6EfZT336f62EI5U.jpg?imwidth=450" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 6</div>
      <img src="https://creators-images.vice.com/content-images/contentimage/no-slug/7ea491fd45c85b888913626e791c8e3f.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 6</div>
      <img src="https://www.tangophotographie.com/wp-content/uploads/2016/11/food-photographer-menu-board-tango-photography.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">6 / 6</div>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQw3QTWQ_meBWulLoQOE5o0yti-AhLfxwYR7LO_fS4wf9GyDqAi" style="width:100%">
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <!-- Image text -->
  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <!-- Thumbnail images -->
  <div class="row">
    <div class="column">
      <img class="demo cursor" src="https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&ved=2ahUKEwiExuDckLLdAhVlTt8KHVE3AU4QjRx6BAgBEAU&url=https%3A%2F%2Fwww.cnn.com%2Fspecials%2Fhealth%2Ffood-diet&psig=AOvVaw1A5oxRj51unjZYNdALDZ2Z&ust=1536727105887859" style="width:100%" onclick="currentSlide(1)" alt="Yum Dawg">
    </div>
    <div class="column"> 
      <img class="demo cursor" src="https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&ved=2ahUKEwjYkuzykLLdAhVxg-AKHbmJCzcQjRx6BAgBEAU&url=https%3A%2F%2Fwww.angelfoodmn.com%2F&psig=AOvVaw1A5oxRj51unjZYNdALDZ2Z&ust=1536727105887859" style="width:100%" onclick="currentSlide(2)" alt="Heaven Holes">
    </div>
    <div class="column">
      <img class="demo cursor" src="https://www.telegraph.co.uk/content/dam/business/2018/01/17/pizza_trans_NvBQzQNjv4BqZgEkZX3M936N5BQK4Va8RWtT0gK_6EfZT336f62EI5U.jpg?imwidth=450" style="width:100%" onclick="currentSlide(3)" alt="Zza's">
    </div>
    <div class="column">
      <img class="demo cursor" src="https://creators-images.vice.com/content-images/contentimage/no-slug/7ea491fd45c85b888913626e791c8e3f.jpg" style="width:100%" onclick="currentSlide(4)" alt="Food is an Art Form">
    </div>
    <div class="column">
      <img class="demo cursor" src="https://www.tangophotographie.com/wp-content/uploads/2016/11/food-photographer-menu-board-tango-photography.jpg" style="width:100%" onclick="currentSlide(5)" alt="Bring on the Sugar">
    </div> 
    <div class="column">
      <img class="demo cursor" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQw3QTWQ_meBWulLoQOE5o0yti-AhLfxwYR7LO_fS4wf9GyDqAi" style="width:100%" onclick="currentSlide(6)" alt="More Layers Please">
    </div>
  </div>
</div>
</body>
</html>
