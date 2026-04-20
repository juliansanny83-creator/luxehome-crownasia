# Luxe Home by CrownAsia - Landing Page

A premium, responsive landing page for CrownAsia's luxury property portfolio.

## 🏆 Features

- ✨ Elegant, responsive design matching CrownAsia's premium branding
- 📱 Mobile-first approach with smooth animations
- 🎨 Gold & cream color scheme reflecting luxury real estate
- 📧 Contact form with validation
- 🏠 Featured property showcase (Lladro Grande)
- 🗺️ Multiple property developments
- ⚡ Fast loading with optimized assets
- ♿ Accessible and SEO-friendly

## 🚀 Deployment on GitHub Pages

### Method 1: Quick Deploy

1. Create a new repository on GitHub named `luxehome-crownasia`
2. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/luxehome-crownasia.git
   cd luxehome-crownasia
   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Luxe Home by CrownAsia - You don't just buy a house; you crown your success. 30 years of exquisite living for seasoned Filipino homebuyers.">
    <meta name="keywords" content="CrownAsia, Lladro Grande, luxury homes Philippines, premium real estate">
    <title>Luxe Home by CrownAsia | Crown Your Success</title>
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400;500;600;700&family=Montserrat:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- CSS -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="nav-brand">
                <div class="crown-icon">👑</div>
                <div class="brand-text">
                    <span class="brand-main">CROWNASIA</span>
                    <span class="brand-sub">a Vista Land Company</span>
                </div>
            </div>
            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#properties">Properties</a>
                <a href="#about">About</a>
                <a href="#contact" class="btn-contact">Contact Us</a>
            </div>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <div class="crown-divider">
                <span class="line"></span>
                <i class="fas fa-crown"></i>
                <span class="line"></span>
            </div>
            <h1 class="hero-title">
                You Don't Just Buy a House;<br>
                <span class="gradient-text">You Crown Your Success</span>
            </h1>
            <p class="hero-subtitle">
                For thirty years, CrownAsia has been the symbol of exquisite living<br>
                for seasoned Filipino homebuyers
            </p>
            <div class="hero-buttons">
                <a href="#properties" class="btn btn-primary">
                    <i class="fas fa-home"></i> View Properties
                </a>
                <a href="#contact" class="btn btn-secondary">
                    <i class="fas fa-phone"></i> Schedule Viewing
                </a>
            </div>
        </div>
        <div class="scroll-indicator">
            <span>Scroll to Explore</span>
            <i class="fas fa-chevron-down"></i>
        </div>
    </section>

    <!-- Tagline Section -->
    <section class="tagline-section">
        <div class="container">
            <div class="tagline-content">
                <div class="crown-icon-large">👑</div>
                <h2 class="tagline-text">Home is the Crowning Glory</h2>
                <div class="anniversary-badge">
                    <span class="anniversary-years">30</span>
                    <span class="anniversary-text">Years of<br>Excellence</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Property - Lladro Grande -->
    <section id="properties" class="featured-property">
        <div class="container">
            <div class="section-header">
                <span class="section-label">FEATURED DEVELOPMENT</span>
                <h2 class="section-title">Lladro Grande</h2>
                <p class="section-subtitle">A Grand Expression of Elegance</p>
            </div>

            <div class="property-showcase">
                <div class="property-image">
                    <img src="images/lladro-grande-hero.jpg" alt="Lladro Grande" onerror="this.src='https://via.placeholder.com/800x600/D4AF37/FFFFFF?text=Lladro+Grande'">
                    <div class="property-badge">Premium Collection</div>
                </div>
                <div class="property-details">
                    <h3>Where Space is Meaningfully Experienced</h3>
                    <p class="property-description">
                        Lladro Grande refines the Crown Asia home with a more expansive approach to space planning. 
                        Generous living spaces, well-proportioned rooms, and fluid transitions create a residence 
                        suited for individuals and investors who value comfort and clarity of design.
                    </p>
                    
                    <div class="property-features">
                        <div class="feature-item">
                            <i class="fas fa-ruler-combined"></i>
                            <div>
                                <strong>Floor Area</strong>
                                <span>211 sqm</span>
                            </div>
                        </div>
                        <div class="feature-item">
                            <i class="fas fa-bed"></i>
                            <div>
                                <strong>Bedrooms</strong>
                                <span>3 Bedrooms</span>
                            </div>
                        </div>
                        <div class="feature-item">
                            <i class="fas fa-bath"></i>
                            <div>
                                <strong>Bathrooms</strong>
                                <span>2 T&B + Powder Room</span>
                            </div>
                        </div>
                        <div class="feature-item">
                            <i class="fas fa-car"></i>
                            <div>
                                <strong>Parking</strong>
                                <span>2-Car Garage</span>
                            </div>
                        </div>
                    </div>

                    <div class="property-highlights">
                        <h4>Property Highlights</h4>
                        <ul>
                            <li><i class="fas fa-check-circle"></i> Maid's Quarters</li>
                            <li><i class="fas fa-check-circle"></i> Office/Den & Family Area</li>
                            <li><i class="fas fa-check-circle"></i> Service Room</li>
                            <li><i class="fas fa-check-circle"></i> Lanai & Balcony</li>
                            <li><i class="fas fa-check-circle"></i> Mediterranean Architecture</li>
                        </ul>
                    </div>

                    <a href="#contact" class="btn btn-primary btn-large">
                        <i class="fas fa-calendar-check"></i> Schedule a Viewing
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Other Developments -->
    <section class="other-properties">
        <div class="container">
            <div class="section-header">
                <span class="section-label">CROWN OF COMMUNITIES</span>
                <h2 class="section-title">Our Premium Developments</h2>
            </div>

            <div class="properties-grid">
                <!-- Chateau Nissa -->
                <div class="property-card">
                    <div class="property-card-image">
                        <img src="images/chateau-nissa.jpg" alt="Chateau Nissa" onerror="this.src='https://via.placeholder.com/400x300/C19A6B/FFFFFF?text=Chateau+Nissa'">
                        <div class="property-card-overlay">
                            <h3>Chateau Nissa</h3>
                            <p>Plaridel, Bulacan</p>
                            <span class="property-theme">Riviera-Inspired Refinement</span>
                        </div>
                    </div>
                </div>

                <!-- Belterre -->
                <div class="property-card">
                    <div class="property-card-image">
                        <img src="images/belterre.jpg" alt="Belterre" onerror="this.src='https://via.placeholder.com/400x300/8B7355/FFFFFF?text=Belterre'">
                        <div class="property-card-overlay">
                            <h3>Belterre</h3>
                            <p>Santa Maria, Bulacan</p>
                            <span class="property-theme">Beauty in Balanced Living</span>
                        </div>
                    </div>
                </div>

                <!-- Granvida -->
                <div class="property-card">
                    <div class="property-card-image">
                        <img src="images/granvida.jpg" alt="Granvida" onerror="this.src='https://via.placeholder.com/400x300/A0826D/FFFFFF?text=Granvida'">
                        <div class="property-card-overlay">
                            <h3>Granvida</h3>
                            <p>Baliwag, Bulacan</p>
                            <span class="property-theme">Living Grand</span>
                        </div>
                    </div>
                </div>

                <!-- Sonvielle -->
                <div class="property-card">
                    <div class="property-card-image">
                        <img src="images/sonvielle.jpg" alt="Sonvielle" onerror="this.src='https://via.placeholder.com/400x300/D4A574/FFFFFF?text=Sonvielle'">
                        <div class="property-card-overlay">
                            <h3>Sonvielle</h3>
                            <p>Urdaneta, Pangasinan</p>
                            <span class="property-theme">Distinction in Every Detail</span>
                        </div>
                    </div>
                </div>

                <!-- Meraveia -->
                <div class="property-card">
                    <div class="property-card-image">
                        <img src="images/meraveia.jpg" alt="Meraveia" onerror="this.src='https://via.placeholder.com/400x300/B8956A/FFFFFF?text=Meraveia'">
                        <div class="property-card-overlay">
                            <h3>Meraveia</h3>
                            <p>Tarlac</p>
                            <span class="property-theme">Where Achievements Find Home</span>
                        </div>
                    </div>
                </div>

                <!-- Aymara -->
                <div class="property-card">
                    <div class="property-card-image">
                        <img src="images/aymara.jpg" alt="Aymara" onerror="this.src='https://via.placeholder.com/400x300/9C7C5C/FFFFFF?text=Aymara'">
                        <div class="property-card-overlay">
                            <h3>Aymara</h3>
                            <p>Balanga, Bataan</p>
                            <span class="property-theme">Beauty in Every Detail</span>
                        </div>
                    </div>
                </div>

                <!-- Luzerra -->
                <div class="property-card">
                    <div class="property-card-image">
                        <img src="images/luzerra.jpg" alt="Luzerra" onerror="this.src='https://via.placeholder.com/400x300/C4A777/FFFFFF?text=Luzerra'">
                        <div class="property-card-overlay">
                            <h3>Luzerra</h3>
                            <p>Subic, Zambales</p>
                            <span class="property-theme">Privilege & Permanence</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about-section">
        <div class="container">
            <div class="about-content">
                <div class="about-text">
                    <span class="section-label">ABOUT CROWNASIA</span>
                    <h2 class="section-title">Bringing the Beauty of the World to Your Doorstep</h2>
                    <p>
                        Crown Asia is the foremost builder of themed residential developments, 
                        distinguished by global influences and set in the most strategic locations 
                        across the archipelago.
                    </p>
                    <p>
                        Built for the self-made, Crown Asia speaks to those who move with mastery, 
                        break through with boldness, and choose with clarity. Residences are not 
                        merely rewards, but reflections of their discipline, direction, and pursuit 
                        of distinction.
                    </p>
                    <div class="about-stats">
                        <div class="stat-item">
                            <span class="stat-number">30+</span>
                            <span class="stat-label">Years of Excellence</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-number">50+</span>
                            <span class="stat-label">Premium Developments</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-number">100K+</span>
                            <span class="stat-label">Happy Homeowners</span>
                        </div>
                    </div>
                </div>
                <div class="about-image">
                    <img src="images/crownasia-about.jpg" alt="CrownAsia" onerror="this.src='https://via.placeholder.com/600x700/D4AF37/FFFFFF?text=CrownAsia'">
                    <div class="about-badge">
                        <i class="fas fa-crown"></i>
                        <span>A Crown Asia home is a trophy of triumph</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <div class="container">
            <div class="section-header">
                <span class="section-label">GET IN TOUCH</span>
                <h2 class="section-title">Ready to Crown Your Success?</h2>
                <p class="section-subtitle">Let us help you find your dream home</p>
            </div>

            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-card">
                        <i class="fas fa-phone-alt"></i>
                        <h3>Call Us</h3>
                        <a href="tel:09701254402">0970-125-4402</a>
                        <a href="tel:09755693080">0975-569-3080</a>
                    </div>

                    <div class="contact-card">
                        <i class="fas fa-envelope"></i>
                        <h3>Email Us</h3>
                        <a href="mailto:luxehomebycrownasia@gmail.com">luxehomebycrownasia@gmail.com</a>
                    </div>

                    <div class="contact-card">
                        <i class="fab fa-instagram"></i>
                        <h3>Follow Us</h3>
                        <a href="https://instagram.com/luxehomebycrownasia" target="_blank">@luxehomebycrownasia</a>
                    </div>

                    <div class="contact-card">
                        <i class="fas fa-clock"></i>
                        <h3>Business Hours</h3>
                        <p>Monday - Saturday<br>9:00 AM - 6:00 PM</p>
                    </div>
                </div>

                <div class="contact-form">
                    <form id="inquiryForm">
                        <div class="form-row">
                            <div class="form-group">
                                <input type="text" id="firstName" name="firstName" required>
                                <label for="firstName">First Name *</label>
                            </div>
                            <div class="form-group">
                                <input type="text" id="lastName" name="lastName" required>
                                <label for="lastName">Last Name *</label>
                            </div>
                        </div>

                        <div class="form-row">
                            <div class="form-group">
                                <input type="email" id="email" name="email" required>
                                <label for="email">Email *</label>
                            </div>
                            <div class="form-group">
                                <input type="tel" id="phone" name="phone" required>
                                <label for="phone">Phone Number *</label>
                            </div>
                        </div>

                        <div class="form-group">
                            <select id="property" name="property" required>
                                <option value="">Select Property of Interest</option>
                                <option value="lladro-grande">Lladro Grande</option>
                                <option value="chateau-nissa">Chateau Nissa</option>
                                <option value="belterre">Belterre</option>
                                <option value="granvida">Granvida</option>
                                <option value="sonvielle">Sonvielle</option>
                                <option value="meraveia">Meraveia</option>
                                <option value="aymara">Aymara</option>
                                <option value="luzerra">Luzerra</option>
                            </select>
                            <label for="property">Property Interest *</label>
                        </div>

                        <div class="form-group">
                            <textarea id="message" name="message" rows="5" required></textarea>
                            <label for="message">Message *</label>
                        </div>

                        <button type="submit" class="btn btn-primary btn-large btn-block">
                            <i class="fas fa-paper-plane"></i> Send Inquiry
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-col">
                    <div class="footer-brand">
                        <div class="crown-icon">👑</div>
                        <div class="brand-text">
                            <span class="brand-main">CROWNASIA</span>
                            <span class="brand-sub">a Vista Land Company</span>
                        </div>
                    </div>
                    <p class="footer-tagline">Home is the Crowning Glory</p>
                    <div class="social-links">
                        <a href="https://instagram.com/luxehomebycrownasia" target="_blank" aria-label="Instagram">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="https://facebook.com/luxehomebycrownasia" target="_blank" aria-label="Facebook">
                            <i class="fab fa-facebook"></i>
                        </a>
                        <a href="mailto:luxehomebycrownasia@gmail.com" aria-label="Email">
                            <i class="fas fa-envelope"></i>
                        </a>
                    </div>
                </div>

                <div class="footer-col">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#properties">Properties</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>

                <div class="footer-col">
                    <h4>Featured Properties</h4>
                    <ul>
                        <li><a href="#properties">Lladro Grande</a></li>
                        <li><a href="#properties">Chateau Nissa</a></li>
                        <li><a href="#properties">Belterre</a></li>
                        <li><a href="#properties">Granvida</a></li>
                    </ul>
                </div>

                <div class="footer-col">
                    <h4>Contact Information</h4>
                    <ul class="contact-list">
                        <li>
                            <i class="fas fa-phone"></i>
                            <a href="tel:09701254402">0970-125-4402</a>
                        </li>
                        <li>
                            <i class="fas fa-phone"></i>
                            <a href="tel:09755693080">0975-569-3080</a>
                        </li>
                        <li>
                            <i class="fas fa-envelope"></i>
                            <a href="mailto:luxehomebycrownasia@gmail.com">luxehomebycrownasia@gmail.com</a>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="footer-bottom">
                <p>&copy; 2024 Luxe Home by CrownAsia. All rights reserved.</p>
                <p class="footer-disclaimer">CrownAsia is a subsidiary of Vista Land & Lifescapes, Inc.</p>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button class="back-to-top" id="backToTop">
        <i class="fas fa-chevron-up"></i>
    </button>

    <!-- JavaScript -->
    <script src="js/main.js"></script>
</body>
</html>
