# Project Responsive Web Design using Bootstrap
## Date:

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

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background: url('https://images.unsplash.com/photo-1522202176988-66273c2fd55f') no-repeat center center/cover;
      color: white;
      height: 80vh;
      display: flex;
      align-items: center;
      text-align: center;
    }
    .overlay {
      background: rgba(0,0,0,0.5);
      width: 100%;
      height: 100%;
      padding: 100px 0;
    }
    .card img { 
      height: 200px;
      object-fit: cover;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm fixed-top">
    <div class="container">
      <a class="navbar-brand fw-bold text-danger" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Explore</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Login</a></li>
          <li class="nav-item"><a class="btn btn-danger text-white ms-2" href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero mt-5">
    <div class="overlay">
      <div class="container">
        <h1 class="display-4 fw-bold">Discover the World’s Top Designers</h1>
        <p class="lead mb-4">Dribbble is the leading platform for showcasing creative work.</p>
        <div class="input-group mb-3 w-50 mx-auto">
          <input type="text" class="form-control" placeholder="Search for designers or projects...">
          <button class="btn btn-danger">Search</button>
        </div>
      </div>
    </div>
  </section>

  <!-- Design Cards -->
  <section class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-4">Explore Popular Shots</h2>
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card shadow-sm">
            <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f" class="card-img-top" alt="">
            <div class="card-body">
              <h5 class="card-title">Creative Dashboard UI</h5>
              <p class="card-text text-muted">by Jane Doe</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card shadow-sm">
            <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085" class="card-img-top" alt="">
            <div class="card-body">
              <h5 class="card-title">Modern App Interface</h5>
              <p class="card-text text-muted">by John Smith</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card shadow-sm">
            <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085" class="card-img-top" alt="">
            <div class="card-body">
              <h5 class="card-title">E-commerce UI Kit</h5>
              <p class="card-text text-muted">by Emily Johnson</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4">
    <p class="mb-0">&copy; 2025 Dribbble Clone | Designed by Jeno</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```




## OUTPUT:
<img width="1280" height="677" alt="image" src="https://github.com/user-attachments/assets/9c816f2d-f9f8-4624-99a8-6ea587d79af0" />



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
