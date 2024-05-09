<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Single Page Website</title>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
<style>
    body {
        font-family: Arial, sans-serif;
    }
    .profile-image {
        width: 100px;
        height: 100px;
        border-radius: 50%;
        object-fit: cover;
    }
</style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Brand</a>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Login</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Profile Section -->
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-3">
                <img src="profile.jpg" alt="Profile Image" class="profile-image">
            </div>
            <div class="col-md-9">
                <h2>Description</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla volutpat blandit nunc, vitae feugiat justo condimentum eget.</p>
            </div>
        </div>
    </div>

    <!-- Image Section -->
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-9">
                <img src="image.jpg" alt="Image" class="img-fluid">
            </div>
            <div class="col-md-3">
                <h2>Image Description</h2>
            </div>
        </div>
    </div>

    <!-- Three Images Section -->
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-4 text-center">
                <img src="image1.jpg" alt="Image 1" class="img-fluid">
                <p>Image 1 Description</p>
            </div>
            <div class="col-md-4 text-center">
                <img src="image2.jpg" alt="Image 2" class="img-fluid">
                <p>Image 2 Description</p>
            </div>
            <div class="col-md-4 text-center">
                <img src="image3.jpg" alt="Image 3" class="img-fluid">
                <p>Image 3 Description</p>
            </div>
        </div>
    </div>

    <!-- Footer Section -->
    <footer class="footer mt-4">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <a href="#"><i class="fas fa-get-started"></i> Get Started</a>
                    <a href="#"><i class="fas fa-login"></i> Login Page</a>
                </div>
                <div class="col-md-6 text-right">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
</body>
</html>

