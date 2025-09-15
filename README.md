<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free YouTube SEO Tools | Boost Your Channel</title>
    <meta name="description" content="Free YouTube SEO tools and resources to help you grow your channel. Keyword research, optimization tips, and analytics - completely free!">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #ff0000;
            --primary-dark: #cc0000;
            --primary-light: #ff4d4d;
            --secondary: #282828;
            --accent: #0077B5;
            --dark: #121212;
            --light: #f8f9fa;
            --gray: #6c757d;
            --success: #28a745;
            --gradient: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        
        body {
            background-color: var(--dark);
            color: var(--light);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header Styles */
        header {
            background: rgba(18, 18, 18, 0.95);
            backdrop-filter: blur(10px);
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 20px rgba(255, 0, 0, 0.1);
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .logo i {
            font-size: 2rem;
            color: var(--primary);
        }
        
        .logo h1 {
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(45deg, var(--primary), var(--primary-light));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 30px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
            position: relative;
        }
        
        nav a:after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--primary);
            transition: width 0.3s;
        }
        
        nav a:hover {
            color: var(--primary-light);
        }
        
        nav a:hover:after {
            width: 100%;
        }
        
        .cta-button {
            background: var(--gradient);
            color: white;
            border: none;
            padding: 10px 25px;
            border-radius: 50px;
            font-weight: 600;
            cursor: pointer;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: 0 4px 15px rgba(255, 0, 0, 0.2);
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(255, 0, 0, 0.3);
        }
        
        /* Hero Section */
        .hero {
            padding: 8rem 0 4rem;
            text-align: center;
            background: linear-gradient(rgba(18, 18, 18, 0.9), rgba(18, 18, 18, 0.9)), url('https://images.unsplash.com/photo-1611162617213-7d7a39e9b1d7?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            position: relative;
            overflow: hidden;
        }
        
        .hero:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: var(--gradient);
            opacity: 0.1;
            z-index: -1;
        }
        
        .hero h2 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            background: linear-gradient(45deg, var(--primary), #ff6b6b);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 800;
        }
        
        .hero p {
            font-size: 1.2rem;
            color: #ccc;
            max-width: 700px;
            margin: 0 auto 2rem;
        }
        
        .hero-badges {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 20px 0;
        }
        
        .badge {
            background: rgba(255, 255, 255, 0.1);
            padding: 8px 15px;
            border-radius: 50px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 5px;
        }
        
        .badge i {
            color: var(--primary);
        }
        
        /* Tools Section */
        .tools {
            padding: 5rem 0;
            background: var(--secondary);
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            color: white;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            position: relative;
            display: inline-block;
        }
        
        .section-title h2:after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--primary);
            border-radius: 2px;
        }
        
        .tools-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .tool-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .tool-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(255, 0, 0, 0.1);
            border-color: rgba(255, 0, 0, 0.3);
        }
        
        .tool-icon {
            font-size: 3rem;
            color: var(--primary);
            margin-bottom: 20px;
        }
        
        .tool-card h3 {
            margin-bottom: 15px;
            color: white;
        }
        
        .tool-card p {
            color: #ccc;
            margin-bottom: 20px;
        }
        
        .tool-button {
            background: transparent;
            color: var(--primary);
            border: 2px solid var(--primary);
            padding: 8px 20px;
            border-radius: 50px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .tool-button:hover {
            background: var(--primary);
            color: white;
        }
        
        /* Free Resources */
        .resources {
            padding: 5rem 0;
            background: var(--dark);
        }
        
        .resources-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .resource-card {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        
        .resource-card:hover {
            transform: translateY(-5px);
        }
        
        .resource-image {
            height: 200px;
            background-size: cover;
            background-position: center;
        }
        
        .resource-content {
            padding: 20px;
        }
        
        .resource-content h3 {
            margin-bottom: 10px;
            color: white;
        }
        
        .resource-content p {
            color: #ccc;
            margin-bottom: 15px;
            font-size: 0.9rem;
        }
        
        .resource-link {
            color: var(--primary);
            text-decoration: none;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 5px;
        }
        
        /* How It Works */
        .process {
            padding: 5rem 0;
            background: var(--secondary);
        }
        
        .steps {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        
        .step {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            max-width: 250px;
        }
        
        .step-number {
            width: 50px;
            height: 50px;
            background: var(--primary);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            font-weight: bold;
            margin-bottom: 15px;
        }
        
        .step h3 {
            margin-bottom: 10px;
            color: white;
        }
        
        .step p {
            color: #ccc;
            font-size: 0.9rem;
        }
        
        /* FAQ Section */
        .faq {
            padding: 5rem 0;
            background: var(--dark);
        }
        
        .faq-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
            gap: 20px;
            margin-top: 3rem;
        }
        
        .faq-item {
            background: rgba(255, 255, 255, 0.05);
            padding: 20px;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .faq-item:hover {
            background: rgba(255, 255, 255, 0.1);
        }
        
        .faq-question {
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: white;
            font-weight: 600;
        }
        
        .faq-answer {
            color: #ccc;
            margin-top: 15px;
            display: none;
        }
        
        .faq-item.active .faq-answer {
            display: block;
        }
        
        /* Footer */
        footer {
            background: var(--secondary);
            color: white;
            padding: 4rem 0 2rem;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 3rem;
        }
        
        .footer-section h3 {
            margin-bottom: 20px;
            font-size: 1.3rem;
            position: relative;
            display: inline-block;
        }
        
        .footer-section h3:after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 40px;
            height: 3px;
            background: var(--primary);
        }
        
        .footer-section p, .footer-section a {
            color: #ccc;
            margin-bottom: 10px;
            display: block;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-section a:hover {
            color: var(--primary);
        }
        
        .social-icons {
            display: flex;
            gap: 15px;
            margin-top: 15px;
        }
        
        .social-icons a {
            width: 40px;
            height: 40px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s;
        }
        
        .social-icons a:hover {
            background: var(--primary);
            transform: translateY(-3px);
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #aaa;
            font-size: 0.9rem;
        }
        
        /* Responsive Design */
        @media (max-width: 992px) {
            .steps {
                flex-direction: column;
                align-items: center;
            }
            
            .faq-grid {
                grid-template-columns: 1fr;
            }
        }
        
        @media (max-width: 768px) {
            nav ul {
                display: none;
            }
            
            .hero h2 {
                font-size: 2.5rem;
            }
            
            .hero-badges {
                flex-direction: column;
                align-items: center;
            }
        }
        
        /* Animations */
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <i class="fab fa-youtube"></i>
                    <h1>Free YouTube SEO</h1>
                </div>
                <nav>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Tools</a></li>
                        <li><a href="#">Resources</a></li>
                        <li><a href="#">Guide</a></li>
                        <li><a href="#">Community</a></li>
                    </ul>
                </nav>
                <button class="cta-button">Get Started</button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h2>Free YouTube SEO Tools & Resources</h2>
            <p>Grow your YouTube channel with our completely free SEO tools, keyword research, and optimization guides. No trials, no payments, no hidden fees.</p>
            
            <div class="hero-badges">
                <div class="badge"><i class="fas fa-check"></i> 100% Free Forever</div>
                <div class="badge"><i class="fas fa-check"></i> No Credit Card Required</div>
                <div class="badge"><i class="fas fa-check"></i> No Trial Limitations</div>
            </div>
            
            <button class="cta-button pulse">Access Free Tools</button>
        </div>
    </section>

    <!-- Tools Section -->
    <section class="tools">
        <div class="container">
            <div class="section-title">
                <h2>Free SEO Tools</h2>
                <p>Everything you need to optimize your YouTube channel</p>
            </div>
            
            <div class="tools-grid">
                <div class="tool-card">
                    <div class="tool-icon">
                        <i class="fas fa-key"></i>
                    </div>
                    <h3>Keyword Research</h3>
                    <p>Find the best keywords for your YouTube videos to rank higher in search results.</p>
                    <button class="tool-button">Use Tool</button>
                </div>
                
                <div class="tool-card">
                    <div class="tool-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>Rank Tracker</h3>
                    <p>Monitor your video rankings for specific keywords and track your progress over time.</p>
                    <button class="tool-button">Use Tool</button>
                </div>
                
                <div class="tool-card">
                    <div class="tool-icon">
                        <i class="fas fa-tags"></i>
                    </div>
                    <h3>Tag Generator</h3>
                    <p>Generate relevant tags for your videos to improve discoverability and suggestions.</p>
                    <button class="tool-button">Use Tool</button>
                </div>
                
                <div class="tool-card">
                    <div class="tool-icon">
                        <i class="fas fa-heading"></i>
                    </div>
                    <h3>Title Optimizer</h3>
                    <p>Create compelling titles that attract clicks while incorporating important keywords.</p>
                    <button class="tool-button">Use Tool</button>
                </div>
                
                <div class="tool-card">
                    <div class="tool-icon">
                        <i class="fas fa-eye"></i>
                    </div>
                    <h3>Thumbnail Analyzer</h3>
                    <p>Test and optimize your thumbnails for maximum click-through rate.</p>
                    <button class="tool-button">Use Tool</button>
                </div>
                
                <div class="tool-card">
                    <div class="tool-icon">
                        <i class="fas fa-analytics"></i>
                    </div>
                    <h3>Competitor Analysis</h3>
                    <p>Analyze what's working for competitors in your niche and adapt their strategies.</p>
                    <button class="tool-button">Use Tool</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Free Resources -->
    <section class="resources">
        <div class="container">
            <div class="section-title">
                <h2>Free Learning Resources</h2>
                <p>Educational content to help you master YouTube SEO</p>
            </div>
            
            <div class="resources-grid">
                <div class="resource-card">
                    <div class="resource-image" style="background-image: url('https://images.unsplash.com/photo-1552664730-d307ca884978?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80');"></div>
                    <div class="resource-content">
                        <h3>YouTube SEO Guide</h3>
                        <p>Complete step-by-step guide to optimizing your videos for maximum visibility.</p>
                        <a href="#" class="resource-link">Read Guide <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
                
                <div class="resource-card">
                    <div class="resource-image" style="background-image: url('https://images.unsplash.com/photo-1593642632823-8f785ba67e45?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80');"></div>
                    <div class="resource-content">
                        <h3>Algorithm Updates</h3>
                        <p>Stay updated with the latest changes to YouTube's algorithm and how to adapt.</p>
                        <a href="#" class="resource-link">Learn More <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
                
                <div class="resource-card">
                    <div class="resource-image" style="background-image: url('https://images.unsplash.com/photo-1542744173-8e7e53415bb0?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80');"></div>
                    <div class="resource-content">
                        <h3>Case Studies</h3>
                        <p>Real examples of channels that grew using our free SEO strategies.</p>
                        <a href="#" class="resource-link">View Cases <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section class="process">
        <div class="container">
            <div class="section-title">
                <h2>How It Works</h2>
                <p>Start growing your channel in just a few simple steps</p>
            </div>
            
            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Create Account</h3>
                    <p>Sign up for free with your email - no credit card required.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Use Our Tools</h3>
                    <p>Access all our SEO tools and resources completely free.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Implement Strategies</h3>
                    <p>Apply our recommendations to your YouTube channel.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">4</div>
                    <h3>Grow Your Channel</h3>
                    <p>Watch your views, subscribers, and engagement increase.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="faq">
        <div class="container">
            <div class="section-title">
                <h2>Frequently Asked Questions</h2>
                <p>Everything you need to know about our free YouTube SEO tools</p>
            </div>
            
            <div class="faq-grid">
                <div class="faq-item">
                    <div class="faq-question">
                        Is it really completely free? <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        Yes! All our tools and resources are 100% free with no hidden costs, no trials, and no premium upgrades. We believe in providing value to the creator community.
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">
                        How do you offer this for free? <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        We're supported by optional donations from grateful users and through partnerships with creator-focused companies. Our mission is to help creators succeed.
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">
                        Do I need to create an account? <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        Some tools work without an account, but creating a free account gives you access to additional features like saving your work and tracking progress over time.
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">
                        Are there any limitations? <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        Our free version has generous usage limits that should be more than enough for most creators. If you have exceptional needs, we offer custom solutions.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Free YouTube SEO</h3>
                    <p>Providing completely free SEO tools and resources to help content creators grow their channels and reach wider audiences.</p>
                    <div class="social-icons">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                
                <div class="footer-section">
                    <h3>Quick Links</h3>
                    <a href="#">Home</a>
                    <a href="#">Tools</a>
                    <a href="#">Resources</a>
                    <a href="#">Guide</a>
                    <a href="#">Community</a>
                </div>
                
                <div class="footer-section">
                    <h3>Free Tools</h3>
                    <a href="#">Keyword Research</a>
                    <a href="#">Rank Tracker</a>
                    <a href="#">Tag Generator</a>
                    <a href="#">Title Optimizer</a>
                    <a href="#">Thumbnail Analyzer</a>
                </div>
                
                <div class="footer-section">
                    <h3>Contact Us</h3>
                    <a href="mailto:support@freeyoutubesEO.com">support@freeyoutubesEO.com</a>
                    <p>123 Creator Road, YouTube City, YT 12345</p>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 Free YouTube SEO. All rights reserved. | <a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a></p>
            </div>
        </div>
    </footer>

    <script>
        // FAQ toggle functionality
        document.querySelectorAll('.faq-item').forEach(item => {
            item.addEventListener('click', () => {
                item.classList.toggle('active');
            });
        });

        // Tool buttons functionality
        document.querySelectorAll('.tool-button').forEach(button => {
            button.addEventListener('click', () => {
                alert('All our tools are completely free to use! In a real implementation, this would open the specific tool.');
            });
        });

        // Smooth scrolling for navigation
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                if(targetId !== '#') {
                    document.querySelector(targetId).scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
