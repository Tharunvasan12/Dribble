# Project Responsive Web Design using Bootstrap
## Date:28-12-2024

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
<html>
<head>
    <title>DRIBBLE</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        
        .container {
            max-width: 1200px;
        }

        
        .card-img-top {
            height: 200px;
            object-fit: cover;
        }
    </style>
</head>
<body>


<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand" href="#">DRIBBLE</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Shots</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Designers</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Teams</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<section class="container my-4">
    <div class="d-flex justify-content-between align-items-center mb-4">
        <h2>Shots</h2>
        <div>
            <button class="btn btn-primary btn-sm">Learn More</button>
            <button class="btn btn-secondary btn-sm">Sign Up</button>
        </div>
    </div>
    <div class="row g-4">
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="breaking bad.jpeg" class="card-img-top img-fluid" alt="breaking bad">
                <div class="card-body">
                    <h5 class="card-title">breaking bad</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="stranger things.jpeg" class="card-img-top img-fluid" alt="stranger things">
                <div class="card-body">
                    <h5 class="card-title">stranger things</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="berlin.jpeg" class="card-img-top img-fluid" alt="berlin">
                <div class="card-body">
                    <h5 class="card-title">berlin</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="better call saul.jpeg" class="card-img-top img-fluid" alt="better call saul">
                <div class="card-body">
                    <h5 class="card-title">better call saul</h5>
                </div>
            </div>
        </div>
    </div>
    <div class="row g-4 mt-3">
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="money heist.jpeg" class="card-img-top img-fluid" alt="money heist">
                <div class="card-body">
                    <h5 class="card-title">money heist</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="squid game.jpeg" class="card-img-top img-fluid" alt="squid game">
                <div class="card-body">
                    <h5 class="card-title">squid game</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="one piece.jpeg" class="card-img-top img-fluid" alt="one piece">
                <div class="card-body">
                    <h5 class="card-title">one piece</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="the witcher.jpeg" class="card-img-top img-fluid" alt="the witcher">
                <div class="card-body">
                    <h5 class="card-title">the witcher</h5>
                </div>
            </div>
        </div>

        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="cobra kai.jpg" class="card-img-top img-fluid" alt="cobra kai">
                <div class="card-body">
                    <h5 class="card-title">cobra kai</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="peaky blinders.jpg" class="card-img-top img-fluid" alt="peaky blinders">
                <div class="card-body">
                    <h5 class="card-title">peaky blinders</h5>
                </div>
            </div>
        </div>
    </div>
</section>

<footer class="bg-dark text-white text-center py-3">
    <p>&copy; THARUNISH VASAN.T(24001333)</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
</body>
</html>

```

## OUTPUT:
![Screenshot 2024-12-28 142326](https://github.com/user-attachments/assets/b02c99b0-3270-4352-bf15-923d2bf9809a)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
