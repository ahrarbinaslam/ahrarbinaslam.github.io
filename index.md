---
layout: default
title: Home
---
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

<style>
    /* Apply Times New Roman font */
    body {
        font-family: 'Times New Roman', serif;
        background-color: #f4f4f4; /* Light background for contrast */
    }

    /* Header Styling */
    .header-title {
        font-size: 2.5rem;
        font-weight: bold;
        color: #002244;
        margin-bottom: 1rem;
        text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2); /* Subtle text shadow */
    }

    /* Profile Image Styling */
    .logo-img {
        max-width: 200px;
        border-radius: 50%;
        margin: 0 auto;
        border: 5px solid #ddd;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    /* Section Titles */
    .section-title {
        font-size: 1.75rem;
        color: #002244;
        border-bottom: 3px solid #007bff; /* Blue underline for section titles */
        padding-bottom: 0.5rem;
        margin-bottom: 1rem;
        font-weight: 600;
    }

    /* Content Styling */
    .content-section {
        margin-bottom: 2rem;
        padding: 1.5rem;
        border-radius: 10px; /* More rounded corners */
        background-color: #ffffff; /* White background for sections */
        transition: background-color 0.3s;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
    }

    .content-section:hover {
        background-color: #f8f9fa; /* Slightly darker on hover */
    }

    /* Contact Icons */
    .contact-icons {
        margin-top: 20px;
        display: flex;
        justify-content: center;
        gap: 20px;
    }

    .contact-icons a {
        font-size: 1.5rem; /* Adjust icon size */
        color: #004b8d; /* Default icon color */
        text-decoration: none;
        transition: color 0.3s ease, transform 0.3s ease;
    }

    .contact-icons a:hover {
        color: #007bff; /* Highlight color on hover */
        transform: scale(1.2); /* Slight zoom effect */
    }

    /* Responsive Layout */
    @media (max-width: 768px) {
        .content-section {
            padding: 1rem;
        }

        .contact-icons {
            gap: 15px; /* Adjust gap for smaller screens */
        }
    }

    /* Additional Styling */
    h2 {
        margin-top: 1.5rem; /* Space above section headers */
    }

    p.lead {
        font-size: 1.1rem; /* Slightly larger lead paragraph */
        line-height: 1.6; /* Increased line height for readability */
    }
</style>

<!-- Header Title -->
<div class="container text-center my-4">
    <h1 class="header-title">Ahrar Bin Aslam</h1>
    <!-- Profile Picture -->
    <img src="/assets/img/profile-pic.png" alt="Ahrar Bin Aslam" class="logo-img mb-3">
    <!-- Contact Icons Below Picture -->
    <div class="contact-icons">
        <a href="mailto:ahas00001@stud.uni-saarland.de" title="Email"><i class="fas fa-envelope"></i></a>
        <a href="https://linkedin.com/in/ahrarbinaslam23" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
        <a href="https://scholar.google.com/citations?user=TjNDuj0AAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="https://medium.com/@ahrarbaslam23" target="_blank" title="Medium"><i class="fab fa-medium"></i></a>
        <a href="https://github.com/ahrarbinaslam" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
    </div>
</div>

<!-- Introduction -->
<div class="container content-section">
    <p class="lead">I am Ahrar Bin Aslam, a master's student of Cybersecurity at <strong><a href="https://www.uni-saarland.de/en/home.html" target="_blank">Universität des Saarlandes</a></strong>. I hold a Bachelor’s degree in Telecommunications Engineering from <strong><a href="https://www.muet.edu.pk/" target="_blank">Mehran University of Engineering and Technology</a></strong>, where I secured first position in my batch. My academic journey has developed a keen interest in cybersecurity, artificial intelligence, and machine learning, fields in which I am committed to advancing my knowledge and expertise. Apart from my academic and professional endeavors, I enjoy coding, watching football, and playing computer games. Feel free to explore my projects, publications, and teaching materials to get a deeper insight into my work. I am always open to new opportunities and connections, so don't hesitate to reach out.</p>
</div>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.0.11/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
