<!DOCTYPE html>
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
    <p>Hello! I'm Dustin 👋</p>
</header>

<!-- ABOUT ME -->
<section class="about">
    <h2>About Me</h2>
    <img src="blob:https://www.messenger.com/f9776ffc-a787-4b18-bc8b-24239bdae4f4" alt="My Photo">
    <p>
        I am a Grade 11 TVL-ICT student. I love coding and learning new technologies.
    </p>
</section>

<!-- HOBBIES -->
<section class="hobbies">
    <h2>My Hobbies</h2>

<div class="hobby">
        <img src="https://img.freepik.com/premium-photo/person-jogging-nature-early-morning-hours-fresh-air-outdoor-exercise-scenic-views-nature-physical-activity-mental-clarity-mood-boost-high-resolution-generative-ai_661108-4564.jpg" alt="Hobby 1">
        <p>jogging</p>
    </div>

<div class="hobby">
        <img src="https://thehake.com/wp-content/uploads/2026/03/airtable_69c3e479b8d01-1-760x567.webp" alt="Hobby 2">
        <p>Gaming</p>
    </div>
</section>

<!-- BUTTON (JavaScript) -->
<section class="interaction">
    <h2>Click Me!</h2>
    <button onclick="showMessage()">Click Here</button>
    <p id="message"></p>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Dustin | Personal Website</p>
</footer>

<!-- INTERNAL JAVASCRIPT -->
<script>
function showMessage() {
    document.getElementById("message").innerHTML = "Thanks for visiting my website!";
}
</script>

</body>
</html>

