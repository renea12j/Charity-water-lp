<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Charity: Water | Rebuild the World</title>
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
<style>
  body {
    font-family: 'Open Sans', sans-serif;
    margin: 0;
    color: #003366;
    background: #ffffff;
  }
  header {
    background-color: #003366;
    color: white;
    padding: 50px 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
  }
  header .logo {
    font-size: 20px;
    font-weight: bold;
    display: flex;
    align-items: center;
  }
  header .logo img {
    height: 30px;
    margin-right: 10px;
  }
  header .contact {
    background: #FFC907;
    color: #000;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
  }
  .hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 60px 5%;
    flex-wrap: wrap;
  }
  .hero-text {
    flex: 1 1 45%;
  }
  .hero-text h1 {
    font-size: 48px;
    margin: 0;
    color: #003366;
  }
  .hero-text h2 {
    font-size: 28px;
    margin: 10px 0 20px;
    color: #003366;
  }
  .hero-text p {
    font-size: 16px;
    margin-bottom: 20px;
    color: #333;
  }
  .subscribe {
    display: flex;
    max-width: 450px;
  }
  .subscribe input {
    flex: 1;
    padding: 15px;
    border: 2px solid #003366;
    border-radius: 5px 0 0 5px;
    font-size: 14px;
  }
  .subscribe button {
    background: #FFC907;
    color: #000;
    border: none;
    padding: 15px 25px;
    font-weight: bold;
    border-radius: 0 5px 5px 0;
    cursor: pointer;
  }
  .hero-image {
    flex: 1 1 45%;
    text-align: center;
    margin-top: 30px;
  }
  .hero-image img {
    max-width: 100%;
    border-radius: 15px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.2);
  }
  .impact-boxes {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 40px 5%;
    flex-wrap: wrap;
  }
  .impact-box {
    background: #f9f9f9;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    max-width: 250px;
    text-align: center;
    font-size: 14px;
    color: #003366;
  }
  @media (max-width: 768px) {
    .hero {
      flex-direction: column;
    }
    .hero-text, .hero-image {
      flex: 1 1 100%;
    }
    .hero-text h1 {
      font-size: 36px;
    }
    .hero-text h2 {
      font-size: 22px;
    }
  }
</style>
</head>
<body>
<header>
  <div class="logo">
    <img src="https://www.charitywater.org/favicon-32x32.png" alt="Logo"> Charity:Water
  </div>
  <a class="contact" href="#">Contact Us</a>
</header>

<section class="hero">
  <div class="hero-text">
    <h1>Rebuild The World.</h1>
    <h2>One Clean Drop At A Time</h2>
    <p>100% of your donation funds clean water systems led by local communities—with full transparency and measurable results.</p>
    <div class="subscribe">
      <input type="text" placeholder="I want to give where it works. Don’t you?">
      <button>Subscribe</button>
    </div>
  </div>
  <div class="hero-image">
    <img src="https://via.placeholder.com/350x600" alt="Phone Mockup with clean water images">
  </div>
</section>

<section class="impact-boxes">
  <div class="impact-box">
    <strong>YOUR IMPACT</strong><br>
    ✔ Project in Uganda funded by college campaign<br>
    ✔ New GPS-tracked site launched in Nepal<br>
    ✔ 5 families gained access to clean water today
  </div>
  <div class="impact-box">
    <strong>TRACK YOUR DONATIONS</strong><br>
    <img src="https://img.icons8.com/color/96/000000/order-delivered.png" alt="Track Icon" width="40">
  </div>
</section>
</body>
</html>
# Charity-water-lp
