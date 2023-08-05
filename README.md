<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple One-Page Website</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    body {
      padding-top: 70px; /* Adjust as needed to accommodate the header height */
      padding-bottom: 70px; /* Adjust as needed to accommodate the footer height */
    }

    .header {
      background-color: #f8f9fa;
      height: 70px;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      z-index: 999;
    }

    .footer {
      background-color: #f8f9fa;
      height: 70px;
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
    }
  </style>
</head>

<body>
  <!-- Header -->
  <div class="header">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">Simple Website</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>

  <!-- Main Content -->
  <div class="container mt-5">
    <h1>Welcome to Our Simple One-Page Website!</h1>
    <p>This is the main content section of the website.</p>
    <p>You can add your content here.</p>
    <p>Feel free to modify the design as per your requirements.</p>

    <!-- About Section -->
    <div id="about" class="mt-5">
      <h2>About Us</h2>
      <p>This section is dedicated to providing information about the website or your organization.</p>
      <p>You can add more details here as needed.</p>
    </div>

    <!-- Contact Section -->
    <div id="contact" class="mt-5">
      <h2>Contact Us</h2>
      <p>If you have any questions or inquiries, feel free to get in touch with us.</p>
      <p>Email: contact@example.com</p>
      <p>Phone: +1 (123) 456-7890</p>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
    <div class="container">
      <p class="text-center mt-3">Copyright © 2023 Simple Website. All rights reserved.</p>
    </div>
  </div>

  <!-- Bootstrap JS and jQuery -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
