# Robert-RoMaRo-phone-repair-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Robert RoMaRo Phone Repair</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f8f9fa;
      color: #333;
    }
    header {
      background: #d40000;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    header h1 {
      margin-bottom: 5px;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .services ul {
      list-style: none;
      padding: 0;
    }
    .services li {
      background: #fff;
      padding: 15px;
      margin: 15px 0;
      border-left: 5px solid #d40000;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    .contact {
      background: #f1f1f1;
      border-radius: 10px;
      padding: 30px;
    }
    .contact p, .contact form {
      margin: 15px 0;
    }
    .contact input, .contact textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1em;
    }
    .contact button {
      background: #d40000;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1em;
    }
    .contact button:hover {
      background: #b00000;
    }
    footer {
      background: #d40000;
      color: white;
      text-align: center;
      padding: 20px;
    }
    h2 {
      margin-top: 0;
    }
    .icon {
      margin-right: 10px;
      color: #d40000;
    }
  </style>
</head>
<body>

  <header>
    <h1>Robert RoMaRo Phone Repair Service</h1>
    <p>We fix it right the first time</p>
  </header>

  <section class="services">
    <h2><i class="fas fa-tools icon"></i>Our Services</h2>
    <ul>
      <li>Screen Repair</li>
      <li>Phone Unlocking</li>
      <li>Software Flashing</li>
      <li>Phone Fixing (Charging, Speaker, Camera, etc.)</li>
    </ul>
  </section>

  <section class="gallery">
    <img src="https://via.placeholder.com/400x400?text=Fixed+Phone+1" alt="Phone 1">
    <img src="https://via.placeholder.com/400x400?text=Fixed+Phone+2" alt="Phone 2">
    <img src="https://via.placeholder.com/400x400?text=Fixed+Phone+3" alt="Phone 3">
    <img src="https://via.placeholder.com/400x400?text=Fixed+Phone+4" alt="Phone 4">
  </section>

  <section class="contact">
    <h2><i class="fas fa-phone icon"></i>Contact Us</h2>
    <p><strong>Phone:</strong> 09119013932</p>
    <p><strong>WhatsApp:</strong> 09036960290</p>
    <p><strong>Location:</strong> Ado Maraba, New Karu, Along Keffi-Abuja Expressway</p>

    <h3>Send us a message</h3>
    <form action="https://formspree.io/f/xayrzwoj" method="POST">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Robert RoMaRo Phone Repair. All rights reserved.
  </footer>

</body>
</html>
