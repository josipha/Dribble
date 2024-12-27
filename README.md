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
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmacy Company</title>
    <!-- Bootstrap CDN -->
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Pharmacy Co.</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#products">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact Us</a>
                    </li>
                </ul>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Login</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Register</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Carousel Section -->
    <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
        </button>
    </div>

    <!-- About Section -->
    <section id="about" class="py-4 text-center">
        <div class="container">
            <h2>About Us</h2>
            <p>We are a trusted pharmacy company offering quality medicines and healthcare products to our customers for over 25 years.</p>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-4 bg-light">
        <div class="container">
            <h2 class="text-center">Our Products</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="c:\Users\admin\Downloads\pd 1.jpeg" class="card-img-top" alt="Product 1">
                        <div class="card-body">
                            <h5 class="card-title">Medicine A</h5>
                            <p class="card-text">Quality healthcare product to treat common illnesses.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="c:\Users\admin\Downloads\pd 4.jpeg" class="card-img-top" alt="Product 2">
                        <div class="card-body">
                            <h5 class="card-title">Supplement B</h5>
                            <p class="card-text">Essential supplements for a healthy lifestyle.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="c:\Users\admin\Downloads\pd 3.webp" class="card-img-top" alt="Product 3">
                        <div class="card-body">
                            <h5 class="card-title">Medical Equipment</h5>
                            <p class="card-text">Reliable medical equipment for healthcare needs.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-4 text-center">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email:contact@pharmacyco.com | Phone: 9789265527</p>
            <button class="btn btn-success">Send a Message</button>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-primary text-white text-center py-3">
        <div class="container">
            <p>Designed and Developed by JOSIPHA</p>
        </div>
    </footer>

    <!-- Bootstrap Bundle JS -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>
</html>

## OUTPUT:
![alt text](<Screenshot 2024-12-17 130418 - Copy.png>)
![alt text](<Screenshot 2024-12-17 130503.png>)
![alt text](<Screenshot 2024-12-17 130518.png>)
![alt text](<Screenshot 2024-12-17 130534.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
