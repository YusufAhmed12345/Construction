<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BuildPro Construction</title>
  <!-- Bootstrap CSS -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1590650046871-92c88703d1b5?auto=format&fit=crop&w=1500&q=80') center/cover no-repeat;
      height: 400px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      text-shadow: 2px 2px 6px black;
    }

    .hero h1 {
      font-size: 3rem;
    }

    footer {
      background-color: #343a40;
      color: white;
      padding: 1rem 0;
      text-align: center;
    }

    .navbar-brand {
      font-weight: bold;
    }

    html {
      scroll-behavior: smooth;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container">
      <a class="navbar-brand" href="#">BuildPro</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
        data-bs-target="#navbarNav" aria-controls="navbarNav"
        aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="hero">
    <h1>Building Dreams, One Brick at a Time</h1>
  </div>

  <!-- Services Section -->
  <section id="services" class="py-5 bg-light">
    <div class="container">
      <h2 class="mb-4 text-center">Our Services</h2>
      <div class="row text-center">
        <div class="col-md-3 mb-4">
          <h5>🏠 Residential</h5>
          <p>Custom homes and renovations.</p>
        </div>
        <div class="col-md-3 mb-4">
          <h5>🏢 Commercial</h5>
          <p>Offices, retail, and industrial builds.</p>
        </div>
        <div class="col-md-3 mb-4">
          <h5>🔧 Remodeling</h5>
          <p>Modernize kitchens, baths, and more.</p>
        </div>
        <div class="col-md-3 mb-4">
          <h5>📋 Project Management</h5>
          <p>Planning, scheduling, and budgeting.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-5">
    <div class="container">
      <h2 class="mb-4 text-center">About Us</h2>
      <p>
        BuildPro Construction has over 20 years of experience delivering high-quality residential and commercial projects.
        We value craftsmanship, transparency, and timely delivery. Our expert team ensures every structure stands the test
        of time and exceeds client expectations.
      </p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-5 bg-light">
    <div class="container">
      <h2 class="mb-4 text-center">Contact Us</h2>
      <div class="row">
        <div class="col-md-6">
          <p><strong>Email:</strong> joslowcostcon@gmail.com</p>
          <p><strong>Phone:</strong> +251 920 818 488</p>
          <p><strong>Address:</strong> Adiss Ababa, Ethiopia</p>
        </div>
        <div class="col-md-6">
          <form>
            <div class="mb-3">
              <label for="name" class="form-label">Name:</label>
              <input type="text" class="form-control" id="name" required />
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email:</label>
              <input type="email" class="form-control" id="email" required />
            </div>
            <div class="mb-3">
              <label for="message" class="form-label">Message:</label>
              <textarea class="form-control" id="message" rows="4" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send Message</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 BuildPro Construction. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js">
  </script>

  <!-- Optional JavaScript: Smooth scroll for internal links -->
  <script>
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener("click", function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute("href")).scrollIntoView({
          behavior: "smooth"
        });
      });
    });
  </script>

</body>
</html>
