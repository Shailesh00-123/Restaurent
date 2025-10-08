<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AAPKA APNA RESTURENT</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; }
    h1, h2 { color: #b22222; }
    .section { margin-bottom: 30px; }
    marquee { font-weight: bold; color: green; margin-top: 20px; }
  </style>
</head>
<body>

  <h1>Welcome to Our Resturent </h1>

  <!-- Link to Menu Page -->
  <div class="section">
    <h2>Our Menu</h2>
    <p><a href="resturent menu.html" target="_blank">Click here to view our Menu</a></p>
  </div>

  <!-- Reservation Form -->
  <div class="section">
    <h2>Reservation Form</h2>
    <form>
      <label>Name: </label>
      <input type="text" required><br><br>
      <label>Email: </label>
      <input type="email" required><br><br>
      <label>Phone: </label>
      <input type="tel" required><br><br>
      <label>Date: </label>
      <input type="date" required><br><br>
      <label>Time: </label>
      <input type="time" required><br><br>
      <button type="submit">Reserve</button>
    </form>
  </div>

  <!-- Location with Google Map -->
  <div class="section">
    <h2>Our Location</h2>
    <iframe 
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.019454787038!2d-122.41941568468117!3d37.77492977975924!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80858064dcb0a7d5%3A0x74a27f1a1f8d8e0!2sCafe!5e0!3m2!1sen!2sin!4v1631712074005!5m2!1sen!2sin" 
      width="600" 
      height="350" 
      style="border:0;" 
      allowfullscreen="" 
      loading="lazy">
    </iframe>
  </div>

  <!-- Customer Reviews -->
  <div class="section">
    <h2>Customer Reviews</h2>
    <p><strong>Ghafoor Bhai:</strong> "Ek dam rapchik returent hai bhidu !!"</p>
    <p><strong>Munna Bhai MBBS:</strong> "Aeee bhidu kya resturent hai ree "</p>
  </div>

  <!-- Marquee -->
  <marquee>&copy; Thank you for visiting!</marquee>

</body>
</html>
