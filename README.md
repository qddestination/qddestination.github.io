<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Travel Agency</title>
  <style>
    /* Add your custom CSS styles here */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }

    nav ul {
      list-style-type: none;
      padding: 0;
    }

    nav li {
      display: inline;
      margin: 10px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
    }

    #hero {
      background-image: url('your-image.jpg');
      background-size: cover;
      background-position: center;
      color: #fff;
      text-align: center;
      padding: 100px 0;
    }

    #hero h1 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    #hero p {
      font-size: 18px;
      margin-bottom: 30px;
    }

    #hero a {
      background-color: #f44336;
      color: #fff;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-size: 16px;
    }

    #about {
      padding: 50px;
      background-color: #f9f9f9;
    }

    #about h2 {
      font-size: 30px;
      margin-bottom: 20px;
    }

    #destinations {
      padding: 50px;
    }

    #destinations h2 {
      font-size: 30px;
      margin-bottom: 20px;
    }

    #destinations ul {
      list-style-type: none;
      padding: 0;
    }

    #destinations li {
      font-size: 18px;
      margin-bottom: 10px;
    }

    #packages {
      padding: 50px;
      background-color: #f9f9f9;
    }

    #packages h2 {
      font-size: 30px;
      margin-bottom: 20px;
    }

    #packages ul {
      list-style-type: none;
      padding: 0;
    }

    #packages li {
      font-size: 18px;
      margin-bottom: 10px;
    }

    #contact {
      padding: 50px;
    }

    #contact h2 {
      font-size: 30px;
      margin-bottom: 20px;
    }

    #contact p {
      font-size: 18px;
      margin-bottom: 30px;
    }

    form input,
    form textarea,
    form button {
      display: block;
      width: 100%;
      margin-bottom: 20px;
      padding: 10px;
      font-size: 16px;
    }

    form button {
      background-color: #f44336;
      color: #fff;
      border: none;
      cursor: pointer;
      border-radius: 5px;
      padding: 10px 20px;
      font-size: 16px;
    }

    footer {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#destinations">Destinations</a></li>
        <li><a href="#packages">Packages</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="hero">
      <h1>Welcome to My Travel Agency</h1>
      <p>Discover the world with us!</p>
      <a href="#contact">Contact Us</a>
    </section>

    <section id="about">
      <h2>About Us</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse ut lectus in lorem tincidunt placerat. Etiam dapibus rutrum ligula, a volutpat neque fermentum id.</p>
    </section>

    <section id="destinations">
      <h2>Popular Destinations</h2>
      <ul>
        <li>Destination 1</li>
        <li>Destination 2</li>
        <li>Destination 3</li>
        <li>Destination 4</li>
      </ul>
    </section>

    <section id="packages">
      <h2>Tour Packages</h2>
      <ul>
        <li>Package 1</li>
        <li>Package 2</li>
        <li>Package 3</li>
        <li>Package 4</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>For inquiries and bookings, please fill out the form below:</p>
      <form>
        <input type="text" placeholder="Name" required>
        <input type="email" placeholder="Email" required>
        <textarea placeholder="Message" required></textarea>
        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 My Travel Agency. All rights reserved.</p>
  </footer>
</body>
</html>
