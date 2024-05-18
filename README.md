<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Neighborhood Car Wash</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="bg-dark text-white text-center py-4">
        <h1>Neighborhood Car Wash</h1>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <a class="navbar-brand" href="#">Home</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <section id="home" class="container text-center my-5">
        <div class="jumbotron">
            <h2>Welcome to Neighborhood Car Wash</h2>
            <p>We provide the best car washing services in the neighborhood.</p>
        </div>
    </section>

    <section id="services" class="container my-5">
        <h2 class="text-center">Our Services</h2>
        <div class="row">
            <div class="col-md-3 text-center">
                <i class="fas fa-car fa-3x mb-3"></i>
                <h4>Exterior Wash</h4>
                <p>Comprehensive exterior wash to make your car shine.</p>
            </div>
            <div class="col-md-3 text-center">
                <i class="fas fa-spray-can fa-3x mb-3"></i>
                <h4>Interior Cleaning</h4>
                <p>Thorough cleaning of the car's interior for a fresh feel.</p>
            </div>
            <div class="col-md-3 text-center">
                <i class="fas fa-hand-sparkles fa-3x mb-3"></i>
                <h4>Full Service</h4>
                <p>A complete car wash service inside and out.</p>
            </div>
            <div class="col-md-3 text-center">
                <i class="fas fa-broom fa-3x mb-3"></i>
                <h4>Waxing</h4>
                <p>Professional waxing to protect and shine your car.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="container my-5">
        <h2 class="text-center">Contact Us</h2>
        <form>
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" class="form-control" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" class="form-control" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="message">Message:</label>
                <textarea class="form-control" id="message" name="message" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </section>

    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2024 Neighborhood Car Wash. All rights reserved.</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
    <script src="script.js"></script>
</body>
</html>
