<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oscar Cao | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header & Navigation -->
  <header class="site-header">
        <div class="container">
            <h1 class="logo">Oscar Cao</h1>
            <nav class="nav-links">
                <a href="#about">About</a>
                <a href="#projects">Projects</a>
                <a href="#modeling">3D & Modeling Parts</a>
                <a href="#gallery">Image Gallery</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h2>Systems & Industrial Engineering Portfolio</h2>
            <p>Showcasing engineering systems, CAD modeling, automated prototypes, and design work.</p>
            <a href="#projects" class="btn">Explore Work</a>
        </div>
    </section>

    <main class="container">

        <!-- Projects Section (Scalable Grid) -->
        <section id="projects" class="content-section">
            <h2>Projects</h2>
            <div class="card-grid">
                <!-- Project Card 1 -->
                <article class="card">
                    <img src="placeholder-project1.jpg" alt="Project preview" class="card-img">
                    <div class="card-body">
                        <h3>Autonomous Vehicle Subassembly</h3>
                        <p>High-precision structural components built using aluminum and automated prototyping.</p>
                        <a href="https://github.com/CondescendingCottageCow" target="_blank" class="card-link">View on GitHub →</a>
                    </div>
                </article>

                <!-- Project Card 2 -->
                <article class="card">
                    <img src="placeholder-project2.jpg" alt="Project preview" class="card-img">
                    <div class="card-body">
                        <h3>Discrete-Event Simulation</h3>
                        <p>Systems engineering value-stream simulation architecture tracking lifecycle assembly flows.</p>
                        <a href="https://github.com/CondescendingCottageCow" target="_blank" class="card-link">View on GitHub →</a>
                    </div>
                </article>
            </div>
        </section>

        <!-- Modeling Parts Section -->
        <section id="modeling" class="content-section">
            <h2>3D Models & Parts</h2>
            <p class="section-desc">Dimensioning drawings, SolidWorks subassemblies, and mechanical renders.</p>
            <div class="card-grid">
                <!-- Model Card 1 -->
                <article class="card">
                    <div class="model-placeholder">[ 3D Model Viewer / Render ]</div>
                    <div class="card-body">
                        <h3>Mechanical Subassembly Part A</h3>
                        <p>SolidWorks parametric drawing and tolerance analysis for custom brackets.</p>
                    </div>
                </article>

                <!-- Model Card 2 -->
                <article class="card">
                    <div class="model-placeholder">[ 3D Model Viewer / Render ]</div>
                    <div class="card-body">
                        <h3>Sensor Housing Bracket</h3>
                        <p>Optimized mounting component designed for ultrasonic distance sensor integration.</p>
                    </div>
                </article>
            </div>
        </section>

        <!-- Image Gallery Section -->
        <section id="gallery" class="content-section">
            <h2>Image Gallery</h2>
            <div class="gallery-grid">
                <img src="placeholder-gallery1.jpg" alt="Gallery item" class="gallery-img">
                <img src="placeholder-gallery2.jpg" alt="Gallery item" class="gallery-img">
                <img src="placeholder-gallery3.jpg" alt="Gallery item" class="gallery-img">
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer id="contact" class="site-footer">
        <div class="container">
            <h3>Get In Touch</h3>
            <p>Interested in collaborating or discussing engineering systems?</p>
            <div class="social-links">
                <a href="https://github.com/CondescendingCottageCow" target="_blank">GitHub</a>
            </div>
            <p class="copyright">© 2026 Oscar Cao. Built with GitHub Pages.</p>
        </div>
    </footer>

</body>
</html>
