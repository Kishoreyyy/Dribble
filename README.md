# Project Responsive Web Design using Bootstrap
## Date: 10/11/2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## Website URL:
https://codepen.io/Kishore-A-the-lessful/pen/jOgRbVb

## PROGRAM :
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bootstrap Webpage</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">My Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#services">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Home Section -->
  <section id="home" class="py-5 text-center bg-light">
    <div class="container">
      <h1>Welcome to My Website</h1>
      <p class="lead">A modern and responsive Bootstrap website.</p>
      <a href="#about" class="btn btn-primary">Learn More</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-5">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <h2>About Us</h2>
          <p>We provide top-notch services to meet your needs. Our team is dedicated to delivering exceptional results.</p>
        </div>
        <div class="col-md-6">
          <img src="https://via.placeholder.com/500x300" alt="About Us" class="img-fluid rounded">
        </div>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center">Our Services</h2>
      <div class="row text-center mt-4">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Service One</h5>
              <p class="card-text">High-quality service to fulfill your needs.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Service Two</h5>
              <p class="card-text">We go above and beyond for customer satisfaction.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Service Three</h5>
              <p class="card-text">Tailored solutions for every project.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-5">
    <div class="container">
      <h2 class="text-center">Contact Us</h2>
      <form class="mt-4">
        <div class="mb-3">
          <label for="name" class="form-label">Name</label>
          <input type="text" class="form-control" id="name" placeholder="Enter your name">
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" placeholder="Enter your email">
        </div>
        <div class="mb-3">
          <label for="message" class="form-label">Message</label>
          <textarea class="form-control" id="message" rows="4" placeholder="Enter your message"></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-primary text-white text-center py-3">
    <p class="mb-0">&copy; 2024 My Website. All Rights Reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```


## OUTPUT:
![alt text](<Screenshot 2024-11-16 014006.png>)
![alt text](<Screenshot 2024-11-16 014052.png>)
![alt text](<Screenshot 2024-11-16 014059.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
