# 1-task
  1. Header
Contains a logo, navigation menu (Home, About, Services, Contact), and a menu toggle icon (☰) for mobile view.

🔷 2. Hero Section
Displays a headline, a tagline, and a call-to-action button ("Get Started") to grab user attention.

🔷 3. Footer
Includes a short message: “Follow us on” and links to social media platforms (Facebook, Twitter, Instagram).

✅ Key Features:
Responsive-ready (with CSS support assumed via style.css).

Clean and semantic HTML5 layout.

Designed for future enhancements (like mobile menu toggle via JavaScript or CSS).
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Website</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header -->
  <header class="header">
    <div class="logo">MyLogo</div>
    <nav class="navbar">
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <div class="menu-toggle">&#9776;</div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>Welcome to Our Website</h1>
      <p>Your success is our commitment.</p>
      <a href="#" class="btn">Get Started</a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>Follow us on</p>
    <div class="social-links">
      <a href="#">Facebook</a>
      <a href="#">Twitter</a>
      <a href="#">Instagram</a>
    </div>
  </footer>

</body>
</html>
