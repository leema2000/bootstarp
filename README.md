# bootstarp
A camera is a SAVE button for the mind's eye.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body { 
        scroll-behavior: smooth;
         }
        .navbar { 
        background-color: #000000;
         }
        .navbar-brand, .nav-link {
         color: white !important; 
         }
        .hero {
         background: #000000; color: white; padding: 100px 0; text-align: center; }
        .section {
         padding: 80px 0; }
        .footer {
         background: #343a40; color: white; padding: 20px 0; text-align: center; }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">My Portfolio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#resume">Resume</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="hero">
        <div class="container">
            <h1>Hi I'm lEE </h1>
            <p>I'm a passionate professional with expertise in web development.</p>
            <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="C:\Users\UK\Pictures\bs\bs-1.png" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>First slide represent our profilio</h5>
                      <p>Some representative placeholder content for the first slide.</p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="C:\Users\UK\Pictures\bs\bs-2.png" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>Second slide label</h5>
                      <p>Some representative placeholder content for the second slide.</p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="C:\Users\UK\Pictures\bs\bs-3.png" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>Third slide label</h5>
                      <p>Some representative placeholder content for the third slide.</p>
                    </div>
                  </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2 class="text-center">About Me</h2>
            <p class="text-center">I am a web developer with experience in Bootstrap, HTML, CSS, and JavaScript.</p>
        </div>
        <style>
            body {
                font-family: 'Arial', sans-serif;
            }
            .about-section {
                padding: 50px 0;
            }
            .profile-img {
                width: 100%;
                border-radius: 10px;
            }
            .info-list {
                list-style: none;
                padding: 0;
            }
            .info-list li {
                margin-bottom: 10px;
                font-size: 16px;
            }
            .info-list i {
                color: #ff4a57;
                margin-right: 10px;
            }
            .title {
                font-weight: bold;
                font-size: 24px;
                margin-bottom: 20px;
            }
        </style>
    </head>
    <body>
    
    <div class="container about-section">
        <div class="row">
            <!-- Image Section -->
            <div class="col-md-4 text-center">
                <img src="C:\Users\UK\Pictures\bs\bs-2.png" alt="Profile Image" class="profile-img">
            </div>
            
            <!-- Information Section -->
            <div class="col-md-8">
                <h2 class="title">UI/UX Designer & Web Developer.</h2>
                <p class="text-muted">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                </p>
                
                <div class="row">
                    <div class="col-md-6">
                        <ul class="info-list">
                            <li><i class="fas fa-calendar-alt"></i> <strong>Birthday:</strong> 1 May 1995</li>
                            <li><i class="fas fa-globe"></i> <strong>Website:</strong> www.example.com</li>
                            <li><i class="fas fa-phone"></i> <strong>Phone:</strong> +123 456 7890</li>
                            <li><i class="fas fa-map-marker-alt"></i> <strong>City:</strong> New York, USA</li>
                        </ul>
                    </div>
                    <div class="col-md-6">
                        <ul class="info-list">
                            <li><i class="fas fa-user"></i> <strong>Age:</strong> 30</li>
                            <li><i class="fas fa-graduation-cap"></i> <strong>Degree:</strong> Master</li>
                            <li><i class="fas fa-envelope"></i> <strong>Email:</strong> email@example.com</li>
                            <li><i class="fas fa-briefcase"></i> <strong>Freelance:</strong> Available</li>
                        </ul>
                    </div>
                </div>
    
                <p class="mt-3 text-muted">
                    Officiis eligendi itaque labore et dolorem mollitia officiis optio vero. Quisquam sunt adipisci omnis et ut.
                </p>
            </div>
        </div>
    </div>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="section bg-light">
        <style>
            body {
                font-family: 'Arial', sans-serif;
            }
            .section-title {
                font-weight: bold;
                font-size: 26px;
                margin-bottom: 20px;
                border-bottom: 3px solid #ff4a57;
                display: inline-block;
                padding-bottom: 5px;
            }
            .progress {
                height: 8px;
                background-color: #eee;
            }
            .progress-bar {
                background-color: #000000;
            }
            .resume-section {
                background: #f8f9fa;
                padding: 50px 0;
            }
            .resume-card {
                padding: 20px;
                background: white;
                border-radius: 10px;
                box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            }
            .experience-title {
                font-weight: bold;
                color: #000000;
            }
            .timeline-dot {
                height: 12px;
                width: 12px;
                background-color: #000000;
                border-radius: 50%;
                display: inline-block;
                margin-right: 10px;
            }
        </style>
    </head>
    <body>
    
    <div class="container my-5">
        <!-- Skills Section -->
        <h2 class="section-title">Skills</h2>
        <p class="text-muted">Necessitatibus eius consequatur ex aliquid fuga eum quidem sint consectetur velit.</p>
        
        <div class="row">
            <div class="col-md-6">
                <p><strong>HTML</strong></p>
                <div class="progress">
                    <div class="progress-bar" style="width:100%;"></div>
                </div>
    
                <p class="mt-3"><strong>CSS</strong></p>
                <div class="progress">
                    <div class="progress-bar" style="width:90%;"></div>
                </div>
    
                <p class="mt-3"><strong>JAVASCRIPT</strong></p>
                <div class="progress">
                    <div class="progress-bar" style="width:75%;"></div>
                </div>
            </div>
    
            <div class="col-md-6">
                <p><strong>PHP</strong></p>
                <div class="progress">
                    <div class="progress-bar" style="width:80%;"></div>
                </div>
    
                <p class="mt-3"><strong>WORDPRESS/CMS</strong></p>
                <div class="progress">
                    <div class="progress-bar" style="width:90%;"></div>
                </div>
    
                <p class="mt-3"><strong>PHOTOSHOP</strong></p>
                <div class="progress">
                    <div class="progress-bar" style="width:55%;"></div>
                </div>
            </div>
        </div>
    </div>
    
    <!-- Resume Section -->
    <div class="resume-section">
        <div class="container">
            <h2 class="section-title">Resume</h2>
            <p class="text-muted">Necessitatibus eius consequatur ex aliquid fuga eum quidem sint consectetur velit.</p>
    
            <div class="row">
                <!-- Summary and Education -->
                <div class="col-md-6">
                    <div class="resume-card">
                        <h4 class="experience-title">Summary</h4>
                        <p><strong>Brandon Johnson</strong></p>
                        <p class="text-muted">
                            Innovative and deadline-driven Graphic Designer with 3+ years of experience designing user-centered digital/print marketing materials.
                        </p>
                        <ul>
                            <li>Portland, Orlando, FL</li>
                            <li>(123) 456-7891</li>
                            <li>alice.barley@example.com</li>
                        </ul>
                    </div>
    
                    <div class="resume-card mt-4">
                        <h4 class="experience-title">Education</h4>
                        <p><strong>MASTER OF FINE ARTS & GRAPHIC DESIGN</strong></p>
                        <p class="text-muted">Rochester Institute of Technology, Rochester, NY (2015 - 2016)</p>
                        <p>
                            Qui deserunt voluptatem. Est aliquam illum tempore ex molestiae autem.
                        </p>
                    </div>
                </div>
    
                <!-- Experience -->
                <div class="col-md-6">
                    <div class="resume-card">
                        <h4 class="experience-title">Professional Experience</h4>
    
                        <p class="mt-3">
                            <span class="timeline-dot"></span> <strong>Senior Graphic Design Specialist</strong> (2019 - Present)
                        </p>
                        <p class="text-muted">Empsron, New York, NY</p>
                        <ul>
                            <li>Lead the design, development, and implementation of graphic materials.</li>
                            <li>Supervise the design team for quality control.</li>
                            <li>Manage budgets ranging from $7,000 - $25,000.</li>
                        </ul>
    
                        <p class="mt-3">
                            <span class="timeline-dot"></span> <strong>Graphic Design Specialist</strong> (2017 - 2018)
                        </p>
                        <p class="text-muted">Previous Company, NY</p>
                        <ul>
                            <li>Handled various graphic projects for clients.</li>
                            <li>Created print & digital media.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
        <div class="container">
            <h2 class="text-center">Resume</h2>
            <p class="text-center"><a href="resume.pdf" class="btn btn-dark">Download Resume</a></p>
        </div>
    </section>

    <!-- Services Section -->
    <style>
        .service-card {
            transition: all 0.3s ease;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
        }
        .service-card:hover {
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
        }
        .service-icon {
            font-size: 30px;
            color: #c2185b;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <div class="container my-5">
        <h2 class="text-dark text-center">Services</h2>
        <p class="text-center text-muted">Necessitatibus eius consequatur ex aliquid fuga eum quidem sint consectetur velit</p>
        <div class="row mt-4">
            <div class="col-md-3">
                <div class="service-card p-3 bg-white">
                    <div class="service-icon">&#128147;</div>
                    <h5>Lorem Ipsum</h5>
                    <p class="text-muted">Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="service-card p-3 bg-white">
                    <div class="service-icon">&#129513;</div>
                    <h5>Sed ut perspici</h5>
                    <p class="text-muted">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="service-card p-3 bg-white">
                    <div class="service-icon">&#128187;</div>
                    <h5>Magni Dolores</h5>
                    <p class="text-muted">Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="service-card p-3 bg-white">
                    <div class="service-icon">&#128250;</div>
                    <h5>Nemo Enim</h5>
                    <p class="text-muted">At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis</p>
                </div>
            </div>
        </div>
    </div>
   

    <!-- Skills Section -->


    <style>
        .portfolio-item img {
            width: 100%;
            border-radius: 10px;
            transition: transform 0.3s ease-in-out;
        }
        .portfolio-item img:hover {
            transform: scale(1.05);
        }
        .filter-buttons .btn {
            margin: 5px;
        }
    </style>
</head>
<body>
    <div class="container my-5">
        <h2 class="text-dark text-center">Portfolio</h2>
        <p class="text-center text-muted">Necessitatibus eius consequatur ex aliquid fuga eum quidem sint consectetur velit</p>
        
        <div class="text-center filter-buttons my-4">
            <button class="btn btn-danger">All</button>
            <button class="btn btn-light">App</button>
            <button class="btn btn-light">Card</button>
            <button class="btn btn-light">Web</button>
        </div>
        
        <div class="row g-3">
            <div class="col-md-4 portfolio-item"><img src="C:\Users\UK\Documents\bootstrap\bootstrap pro1\profolio\c1.png" alt="Item"></div>
            <div class="col-md-4 portfolio-item"><img src="C:\Users\UK\Documents\bootstrap\bootstrap pro1\profolio\c2.png" alt="Item"></div>
            <div class="col-md-4 portfolio-item"><img src="C:\Users\UK\Documents\bootstrap\bootstrap pro1\profolio\c3.png" alt="Item"></div>
            <div class="col-md-6 portfolio-item"><img src="C:\Users\UK\Documents\bootstrap\bootstrap pro1\profolio\c4.png" alt="Item"></div>
            <div class="col-md-6 portfolio-item"><img src="C:\Users\UK\Documents\bootstrap\bootstrap pro1\profolio\c5.png" alt="Item"></div>
            <div class="col-md-4 portfolio-item"><img src="C:\Users\UK\Documents\bootstrap\bootstrap pro1\profolio\c1.png" alt="Item"></div>
            <div class="col-md-4 portfolio-item"><img src="C:\Users\UK\Documents\bootstrap\bootstrap pro1\profolio\c2.png" alt="Item"></div>
            <div class="col-md-4 portfolio-item"><img src="C:\Users\UK\Documents\bootstrap\bootstrap pro1\profolio\c3.png" alt="Item"></div>
        </div>
    </div>
           
    <!-- Contact Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2 class="text-center">Contact Me</h2>
            <form>
                <div class="mb-3">
                    <label class="form-label">Name</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="mb-3">
                    <label class="form-label">Email</label>
                    <input type="email" class="form-control" required>
                </div>
                <div class="mb-3">
                    <label class="form-label">Message</label>
                    <textarea class="form-control" rows="4" required></textarea>
                </div>
                <button type="submit" class="btn btn-dark">Send Message</button>
            </form>
            <p class="text-center mt-3">Email: myemail@example.com | LinkedIn: <a href="#">My Profile</a></p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>© 2025 My Portfolio | All Rights Reserved</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
