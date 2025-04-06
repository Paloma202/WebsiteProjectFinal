<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400..900&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
  <title>Final Project</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: work sans;
    }

    body {
      background-color: #0e0e0e;
      color: #f5f5f5;
      line-height: 1.6;
    }

    header {
      text-align: center;
      background: url("pic/prosres3.jpeg") no-repeat center center;
      background-size: cover;
      padding: 80px 20px;
      position: relative;

    }

    header::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.6);
      z-index: 1;
    }

    header h1 {
      font-size: 50px;
      color: #ffff;
      letter-spacing: 3px;
      position: relative;
      z-index: 2;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
      font-family: cinzel;
    }

    header h3 {
      font-weight: 300;
      font-size: 14px;
      color: #ccc;
      font-family: 'Work Sans';
      position: relative;
      z-index: 2;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      max-width: 1200px;
      margin: auto;
      padding: 60px 20px;
      gap: 30px;
    }

    section {
      flex: 1;
      min-width: 300px;
      padding: 30px;
      background: #1a1a1a;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.5);
    }

    

    h2 {
      color: #d3af37;
      margin-bottom: 20px;
      font-size: 20px;
      font-family: cinzel;
      text-align: center;
    }



    p{
      margin-bottom: 16px;
      color: #ccc;
      font-size: 14px;
      text-align: center;
      font-weight: 300;
    }

    .vmcv{
      text-align: left;
    }


    span{
      font-weight: 500;
    }

    h4{
      text-align: center;
      color: #ccc;
      font-weight: 500;
    }

    .intro-img{
      width: 100%;
      height: auto;
      border-radius: 10px;
      margin: 15px 0;
    }

    .facility-img {
      width: 100%;
      height: auto;
      border-radius: 10px;
      margin: 15px 0;
    }


    .form-group {
      margin-bottom: 20px;
    }

    label {
      display: block;
      margin-bottom: 8px;
      font-weight: 500;
      color: #ccc;
    }

    input[type="text"], input[type="email"] {
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 6px;
      background: #2a2a2a;
      color: #fff;
    }

    input[type="text"]::placeholder,
    input[type="email"]::placeholder {
      color: #aaa;
    }

    button {
      padding: 12px 24px;
      background-color: #d4af37;
      border: none;
      color: #000;
      font-weight: bold;
      cursor: pointer;
      border-radius: 6px;
      transition: background-color 0.3s, transform 0.3s;
    }

    button:hover {
      background-color: #e5c06f;
      transform: scale(1.05);
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
        padding: 30px 15px;
      }
    }

    .newsletter{
      padding: 20px;
      max-height: 450px;
    }

    .last-img{
    width: 200px;
    display: block;
    margin: 0 auto;
    margin-top:120px;
    }

  </style>
</head>
<body>
  <header>
    <h1>The Proscenium Residences</h1>
    <h3> 6409 Rockwell Dr, Makati City, Metro Manila, Philippines</h3>
  </header>
  <div class="container">
    <section>
      <h2>About Proscenium</h2>
      <p>Welcome to The Proscenium Residences—where elegance meets comfort in the heart of Makati City. </p>
      <img src="pic/prosres.jpeg" alt="prosres" class="intro-img">

      <p>Proscenium stands out with its exceptional design and world-class amenities. Designed by renowned architect Carlos Ott, the development features five distinct residential towers, each reflecting unique cultural influences. With a prime location offering direct access to high-end retail, dining, and entertainment at Power Plant Mall, residents enjoy the perfect balance of luxury and convenience.<br></p>


      <img src="pic/nice.png" alt="nice" class="intro-img">
      <img src="pic/interior.jpg" alt="int" class="intro-img">
      <img src="pic/interior2.jpg" alt="int" class="intro-img">
<p class=vmcv>
      <span>Proscenium at Rockwell<br><br></span>
      
      <span>Vision:</span> To create admired communities beyond ordinary.<br>
      <span>Mission:</span> To deliver delightful, memorable experiences every day.<br>

      <span>Core Values:</span>

      Innovation, Integrity, Teamwork, Fairness, Excellence</p>

    </section>

    <section>
      <h2>Facilities & Offerings</h2>
      
        <h4>Gym and Wellness Center</h4>
        <img src="pic/gym.webp" alt="Gym" class="facility-img">
        <p> Each tower features a private, fully equipped gym, along with wellness amenities like pools, a tennis court, and jogging paths. These facilities promote a healthy, active lifestyle in a luxurious setting.</p>

        <h4>Infinity Pool and Poolside Lounge</h4>
        <img src="pic/pool.jpg" alt="Pool" class="facility-img">
        <p>The pool area features uniquely shaped swimming pools, including a serene floating river. Surrounded by immaculately landscaped tropical foliage, the poolside is adorned with cabanas, pavilions, and lounges, providing ideal spaces for relaxation and socializing while enjoying stunning views of the Makati skyline.</p>

        <h4>Private Theater Room</h4>
        <img src="pic/theater.webp" alt="Theater Room" class="facility-img">
        <p>Residents can enjoy a state-of-the-art performing arts theater, an intimate venue with under 800 seats, offering excellent acoustics and unobstructed views for world-class cultural performances. Additionally, elegant function rooms are available, providing versatile spaces suitable for hosting events, gatherings, and special occasions.</p>

        <h4>Function Rooms</h4>
        <img src="pic/funcroom.jpg" alt="funcroom" class="facility-img">
        <p> Elegant function rooms are available, providing versatile spaces suitable for hosting events, gatherings, and special occasions.</p>

    </section>

    <section class="newsletter">
      <h2>Newsletter Registration</h2>
      <p>Stay up to date with the latest news, exclusive offers, and community events. Subscribe to our newsletter and experience the lifestyle that awaits.<br></p>
      <form>
        <div class="form-group">
          <label for="name">Name</label>
          <input type="text" id="name" name="name" placeholder="Your name" required />
        </div>
        <div class="form-group">
          <label for="email">Email</label>
          <input type="email" id="email" name="email" placeholder="Your email" required />
        </div>
        <button type="submit">Subscribe</button>
      </form>
   
     <img src="pic/logo.png" alt="logo" class="last-img">
     
    </section>
  </div>
</body>
</html>
