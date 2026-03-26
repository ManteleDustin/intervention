
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Personal Website</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

<!-- HEADER -->
<header>
  <h1>Welcome to My Website</h1>
  <p id="greeting">Hello!</p>
</header>

<!-- ABOUT ME -->
<section class="about">
  <h2>About Me</h2>
  <img src="https://scontent.fmnl30-3.fna.fbcdn.net/v/t39.30808-1/600284105_1577787896586325_3445389563946953261_n.jpg?stp=dst-jpg_s200x200_tt6&_nc_cat=108&ccb=1-7&_nc_sid=e99d92&_nc_eui2=AeEm-Gh9vAJUQsucFa-Sez69ahQoojjYY_tqFCiiONhj-0HV3lPZiC9Yc95nPwK_2DLjELkut6OyPBA3FHqjuJNF&_nc_ohc=DqMrMPrTmSsQ7kNvwEO9GBh&_nc_oc=AdqwSIu-fkbS2bIqD9hY521JuDoHPeSb4uvkHCvjO_TnCxM7bQA8V8NZdn_-66fyoDk&_nc_zt=24&_nc_ht=scontent.fmnl30-3.fna&_nc_gid=2Ftvgw3tC_mx9trpYkOJ7Q&_nc_ss=7a32e&oh=00_Afx9FWwQ2eFcnLDSqYWmKo-aHUzk9EgzUzT6s8chAth1qg&oe=69CAA85F" alt="My Photo">
  <p>
    Hi! I'm Dustin. I am a Grade 11 TVL-ICT student. 
    I love reading, gaming, and learning new things in life.
  </p>
</section>

<!-- HOBBIES -->
<section class="hobbies">
  <h2>My Hobbies</h2>

  <div class="gallery">
    <div>
      <img src="https://thehake.com/wp-content/uploads/2026/03/airtable_69c3e479b8d01-1-760x567.webp">
      <p>Gaming</p>
    </div>

<div>
      <img src="https://img.freepik.com/premium-photo/person-jogging-nature-early-morning-hours-fresh-air-outdoor-exercise-scenic-views-nature-physical-activity-mental-clarity-mood-boost-high-resolution-generative-ai_661108-4564.jpg">
      <p>Jogging</p>
    </div>

<div>
      <img src="https://img.freepik.com/premium-photo/christian-gospel-hands-reading-bible-living-room-worship-god-faith-praise-jesus-christ-home-spiritual-holy-book-person-studying-scripture-story-sofa-learning-religion_590464-378549.jpg?w=2000">
      <p>Reading</p>
    </div>
  </div>
</section>

<!-- BUTTON -->
<section class="interact">
  <h2>Click Me!</h2>
  <button onclick="showMessage()">Click Here</button>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 Dustin | Personal Website</p>
</footer>

<!-- INTERNAL JAVASCRIPT -->
<script>
  function showMessage() {
    alert("Thanks for visiting my website!");
  }

  // Greeting based on time
  const greeting = document.getElementById("greeting");
  const hour = new Date().getHours();

  if (hour < 12) {
    greeting.innerText = "Good Morning!";
  } else if (hour < 18) {
    greeting.innerText = "Good Afternoon!";
  } else {
    greeting.innerText = "Good Evening!";
  }
</script>

</body>
</html>
