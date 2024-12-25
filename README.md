# Project Responsive Web Design using Bootstrap
## Date:25.12.2024

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore the books </title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light">

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-success">
        <div class="container">
            <a class="navbar-brand" href="#">The Paper Garden</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Gallery</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                    </li>
                </ul>
                <ul class="navbar-nav mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Log In</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link btn btn-light text-dark px-3" href="#">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header -->
    <div class="bg-success text-white text-center py-4">
        <h1>The Paper Garden</h1>
        <p class="mb-0">"A name that speaks to the creative energy of books and stories!"</p>
    </div>

    <!-- Categories -->
    <div class="container my-5">
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card h-100">
                        <div class="ratio ratio-4x3">
                        <img src="1.jpg" class="card-img-top img-fluid" alt="The Twins Hit Hollywood">
                        <div class="card-body">
                            <h5 class="card-title">The Twins Hit Hollywood</h5>
                            <p class="card-text">This article includes a list of references, related reading, 
                                or external links, but its sources remain unclear because it lacks inline citations</p>
                        </div>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card h-100">
                        <div class="ratio ratio-4x3">
                        <img src="2.jpg" class="card-img-top img-fluid" alt="Percy Jackson and the Titan's Curse">
                        <div class="card-body">
                            <h5 class="card-title">Percy Jackson and the Titan's Curse</h5>
                            <p class="card-text">The Titan's Curse is an American fantasy-adventure novel.</p>
                        </div>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card h-100">
                        <div class="ratio ratio-4x3">
                        <img src="3.jpg" class="card-img-top img-fluid" alt="Zoology">
                        <div class="card-body">
                            <h5 class="card-title">Zoology</h5>
                            <p class="card-text">Are We Smart Enough to Know How Smart Animals Are? </p>
                        </div>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card h-100">
                        <div class="ratio ratio-4x3">
                        <img src="4.jpg" class="card-img-top img-fluid" alt="The black obelisk.">
                        <div class="card-body">
                            <h5 class="card-title">The black obelisk.</h5>
                            <p class="card-text">Ludwig, the protagonist in his mid twenties just like most of his friends.</p>
                        </div>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card h-100">
                        <div class="ratio ratio-4x3">
                        <img src="5.jpg" class="card-img-top img-fluid" alt="The Psychology of Money">
                        <div class="card-body">
                            <h5 class="card-title">The Psychology of Money</h5>
                            <p class="card-text">Timeless lessons on wealth, greed, and happiness.</p>
                        </div>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card h-100">
                        <div class="ratio ratio-4x3">
                        <img src="6.jpg" class="card-img-top img-fluid" alt="The secret">
                        <div class="card-body">
                            <h5 class="card-title">The secret</h5>
                            <p class="card-text"> In every aspect of life, money, health, and happiness will follow.</p>
                        </div>
                        </div>
                    </div>
                </a>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="text-center py-3 bg-light">
        <p>&copy; 2024 The Paper Garden. All Rights Reserved.</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:

![alt text](<Screenshot 2024-12-25 140819.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
