<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital Portfolio - Butterfly Collection</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f7fa;
      color: #333;
      line-height: 1.6;
    }

    /* Navigation */
    nav {
      background: #333;
      padding: 15px 20px;
      display: flex;
      justify-content: center;
      gap: 30px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 1rem;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ff9a9e;
    }

    header {
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
    }

    /* About Me */
    .about {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 20px;
      padding: 50px 20px;
      background: white;
      margin: 30px auto;
      border-radius: 15px;
      max-width: 1000px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .about img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid #ff9a9e;
    }

    .about-text {
      max-width: 650px;
    }

    .about-text h2 {
      margin-bottom: 12px;
      font-size: 2rem;
      color: #444;
    }

    .about-text p {
      margin-bottom: 15px;
      color: #555;
    }

    .contact {
      margin-top: 10px;
    }

    .contact p {
      margin: 5px 0;
      font-size: 1rem;
    }

    /* Projects / Gallery */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }

    .card {
      background: white;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .card h3 {
      font-size: 1.4rem;
      padding: 12px;
      color: #444;
    }

    .card p {
      padding: 0 12px 15px;
      font-size: 1rem;
      color: #555;
    }

    /* Skills Section */
    .skills {
      padding: 50px 20px;
      text-align: center;
      background: white;
      margin: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .skills h2 {
      margin-bottom: 20px;
      font-size: 2rem;
      color: #444;
    }

    .skills ul {
      list-style: none;
    }

    .skills ul li {
      font-size: 1.1rem;
      margin: 10px 0;
      color: #555;
    }

    /* Hire Me Section */
    .hire {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(135deg, #fad0c4, #ffdde1);
      margin: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .hire h2 {
      font-size: 2.2rem;
      margin-bottom: 15px;
      color: #333;
    }

    .hire p {
      font-size: 1.1rem;
      margin-bottom: 20px;
      color: #444;
    }

    /* Contact Form */
    .hire form {
      max-width: 500px;
      margin: 0 auto;
      text-align: left;
    }

    .hire label {
      display: block;
      margin: 10px 0 5px;
      font-weight: bold;
      color: #333;
    }

    .hire input, 
    .hire textarea {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 8px;
      margin-bottom: 15px;
      font-size: 1rem;
    }

    .hire button {
      display: block;
      width: 100%;
      padding: 12px;
      font-size: 1rem;
      font-weight: bold;
      background: #ff9a9e;
      color: white;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .hire button:hover {
      background: #ff6a6a;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 25px;
      background: #333;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#hire">Hire Me</a>
  </nav>

  <!-- Header -->
  <header id="home">
    <h1>Hii I'm S. Harshavardhan</h1>
    <p>Butterfly Collection Showcase</p>
  </header>

  <!-- About Me Section -->
  <section class="about" id="about">
    <img src="https://via.placeholder.com/160" alt="Profile Picture">
    <div class="about-text">
      <h2>About Me</h2>
      <p>Hello! I am a nature enthusiast and butterfly lover. Through this portfolio, I want to share the vibrant world of butterflies and their fascinating details.</p>
      <div class="contact">
        <p><strong>Email:</strong> kptrharshareddy@gmail.com</p>
        <p><strong>Phone:</strong> +91 98765 43210</p>
        <p><strong>Location:</strong> India</p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="gallery" id="projects">
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Morpho_menelaus_MHNT_dos.jpg" alt="Blue Morpho">
      <h3>Blue Morpho</h3>
      <p>Known for its brilliant blue wings, the Blue Morpho is native to South American rainforests.</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Monarch_Butterfly_Danaus_plexippus.jpg" alt="Monarch">
      <h3>Monarch</h3>
      <p>The Monarch butterfly is famous for its long migration across North America.</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Papilio_demoleus_1.jpg" alt="Lime Swallowtail">
      <h3>Lime Swallowtail</h3>
      <p>Found in Asia and Australia, it has striking black, white, and yellow wing patterns.</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/c/c2/Tailed_Jay_Ganeshgudi_Jan2016_IMG_7247_03.jpg" alt="Tailed Jay">
      <h3>Tailed Jay</h3>
      <p>A fast-flying butterfly with bright green spots, commonly found in tropical regions.</p>
    </div>
  </section>

  <!-- Skills Section -->
  <section class="skills" id="skills">
    <h2>My Skills</h2>
    <ul>
      <li>HTML, CSS, JavaScript</li>
      <li>Web Design & UI/UX</li>
      <li>Photography & Editing</li>
      <li>Nature Conservation Awareness</li>
    </ul>
  </section>

  <!-- Hire Me Section -->
  <section class="hire" id="hire">
    <h2>Hire Me</h2>
    <p>If you like my work and would like to collaborate, please fill out the form below:</p>

    <form action="mailto:kptrharshareddy@gmail.com" method="post" enctype="text/plain">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required>

      <label for="message">Message</label>
      <textarea id="message" name="message" rows="5" placeholder="Write your message..." required></textarea>

      <button type="submit">Submit</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Digital Portfolio | Created by S. Harshavardhan</p>
  </footer>

</body>
</html>
