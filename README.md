<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GK Choppa | Prince Geoffrey Kimera - Official Biography</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --gold: #D4AF37;
            --dark-gold: #B8941F;
            --black: #0a0a0a;
            --dark-gray: #1a1a1a;
            --light-gray: #f5f5f5;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: var(--light-gray);
        }

        /* Header */
        .hero {
            background: linear-gradient(135deg, var(--black) 0%, var(--dark-gray) 100%);
            color: var(--white);
            padding: 80px 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="50" cy="50" r="40" fill="none" stroke="%23D4AF37" stroke-width="0.5" opacity="0.1"/></svg>');
            background-size: 100px;
            opacity: 0.3;
        }

        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
        }

        .crown-icon {
            font-size: 3rem;
            color: var(--gold);
            margin-bottom: 20px;
        }

        h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            font-weight: 700;
            letter-spacing: 2px;
        }

        .subtitle {
            color: var(--gold);
            font-size: 1.3rem;
            margin-bottom: 20px;
            font-weight: 300;
        }

        .titles {
            font-size: 1.1rem;
            opacity: 0.9;
            margin-bottom: 30px;
        }

        .motto {
            font-style: italic;
            font-size: 1.2rem;
            border-left: 3px solid var(--gold);
            padding-left: 20px;
            margin-top: 30px;
            color: var(--gold);
        }

        /* Navigation */
        nav {
            background: var(--white);
            padding: 15px;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 30px;
        }

        nav a {
            text-decoration: none;
            color: var(--black);
            font-weight: 600;
            transition: color 0.3s;
            text-transform: uppercase;
            font-size: 0.9rem;
            letter-spacing: 1px;
        }

        nav a:hover {
            color: var(--gold);
        }

        /* Container */
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Sections */
        section {
            background: var(--white);
            margin-bottom: 30px;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
        }

        h2 {
            color: var(--black);
            font-size: 2rem;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 3px solid var(--gold);
            display: inline-block;
        }

        h3 {
            color: var(--dark-gold);
            font-size: 1.3rem;
            margin: 25px 0 15px 0;
        }

        /* Stats Grid */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }

        .stat-card {
            background: var(--black);
            color: var(--white);
            padding: 25px;
            border-radius: 8px;
            text-align: center;
            border: 2px solid var(--gold);
        }

        .stat-label {
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            opacity: 0.8;
            margin-bottom: 5px;
        }

        .stat-value {
            font-size: 1.3rem;
            font-weight: bold;
            color: var(--gold);
        }

        /* Business Cards */
        .business-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }

        .business-card {
            background: linear-gradient(135deg, var(--dark-gray) 0%, var(--black) 100%);
            color: var(--white);
            padding: 30px;
            border-radius: 10px;
            border-left: 5px solid var(--gold);
        }

        .business-card h3 {
            color: var(--gold);
            margin-top: 0;
        }

        /* Family Tree */
        .family-section {
            background: var(--light-gray);
            padding: 20px;
            border-radius: 8px;
            margin: 15px 0;
        }

        .family-title {
            color: var(--dark-gold);
            font-weight: bold;
            margin-bottom: 10px;
        }

        .family-list {
            list-style: none;
            padding-left: 0;
        }

        .family-list li {
            padding: 8px 0;
            border-bottom: 1px solid #ddd;
            position: relative;
            padding-left: 20px;
        }

        .family-list li:before {
            content: "♦";
            color: var(--gold);
            position: absolute;
            left: 0;
        }

        .heritage-note {
            background: var(--gold);
            color: var(--black);
            padding: 15px;
            border-radius: 5px;
            margin-top: 20px;
            font-weight: 600;
        }

        /* Focus Areas */
        .focus-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .focus-item {
            background: var(--black);
            color: var(--white);
            padding: 20px;
            border-radius: 5px;
            text-align: center;
            font-weight: 600;
            border: 2px solid transparent;
            transition: all 0.3s;
        }

        .focus-item:hover {
            border-color: var(--gold);
            transform: translateY(-2px);
        }

        /* Footer */
        footer {
            background: var(--black);
            color: var(--white);
            text-align: center;
            padding: 40px 20px;
            border-top: 5px solid var(--gold);
        }

        .footer-text {
            opacity: 0.8;
            margin-bottom: 10px;
        }

        .locations {
            color: var(--gold);
            font-weight: 600;
        }

        /* Responsive */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            section {
                padding: 25px;
            }
            
            nav ul {
                gap: 15px;
            }
        }

        /* Print Styles */
        @media print {
            nav { display: none; }
            .hero { background: var(--black) !important; -webkit-print-color-adjust: exact; }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <header class="hero">
        <div class="hero-content">
            <div class="crown-icon">👑</div>
            <h1>GK CHOPPA</h1>
            <p class="subtitle">Prince Geoffrey Kimera</p>
            <p class="titles">Founder & CEO | Investor | Philanthropist</p>
            <div class="motto">"Happiness, Wealth, and Power."</div>
        </div>
    </header>

    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#overview">Overview</a></li>
            <li><a href="#philanthropy">Philanthropy</a></li>
            <li><a href="#business">Business</a></li>
            <li><a href="#heritage">Heritage</a></li>
            <li><a href="#philosophy">Philosophy</a></li>
        </ul>
    </nav>

    <div class="container">

        <!-- Overview Section -->
        <section id="overview">
            <h2>Overview</h2>
            <p>GK Choppa is a Ugandan entrepreneur, technologist, and philanthropist whose work blends business leadership, innovation, and community upliftment. With formal training in computer science, he applies technology-driven thinking across real estate, construction, and digital innovation, while maintaining a strong commitment to direct community support, including food and financial donations.</p>
            
            <div class="stats-grid">
                <div class="stat-card">
                    <div class="stat-label">Full Name</div>
                    <div class="stat-value">Prince Geoffrey Kimera</div>
                </div>
                <div class="stat-card">
                    <div class="stat-label">Date of Birth</div>
                    <div class="stat-value">02 August 1999</div>
                </div>
                <div class="stat-card">
                    <div class="stat-label">Nationality</div>
                    <div class="stat-value">Ugandan</div>
                </div>
                <div class="stat-card">
                    <div class="stat-label">Education</div>
                    <div class="stat-value">Computer Science</div>
                </div>
                <div class="stat-card">
                    <div class="stat-label">Est. Net Worth</div>
                    <div class="stat-value">USD 100 Million</div>
                </div>
            </div>
        </section>

        <!-- Philanthropy Section -->
        <section id="philanthropy">
            <h2>Philanthropy & Community Upliftment</h2>
            <p>GK Choppa is widely recognized for hands-on philanthropy, personally supporting communities through:</p>
            <ul style="margin: 20px 0; padding-left: 20px;">
                <li>Food donations to underserved households</li>
                <li>Financial assistance to individuals and families in need</li>
                <li>Empowerment-focused support, prioritizing dignity, opportunity, and long-term impact</li>
            </ul>
            <div class="heritage-note">
                His approach emphasizes uplifting individuals and communities, not charity alone.
            </div>
        </section>

        <!-- Business Section -->
        <section id="business">
            <h2>Business & Impact Platforms</h2>
            <div class="business-grid">
                <div class="business-card">
                    <h3>GK Choppa Property Investments</h3>
                    <p>A real estate and construction enterprise focused on acquisition, development, selling, and construction of residential and commercial properties, while creating employment and supporting local economies.</p>
                </div>
                <div class="business-card">
                    <h3>GK Choppa Foundation</h3>
                    <p>The philanthropic arm dedicated to community upliftment, food security initiatives, financial relief, and empowerment programs.</p>
                </div>
                <div class="business-card">
                    <h3>28th Gold</h3>
                    <p>A technology and innovation hub specializing in app development, digital platforms, and modern tech solutions.</p>
                </div>
            </div>
        </section>

        <!-- Heritage Section -->
        <section id="heritage">
            <h2>Royal Heritage & Family Lineage</h2>
            <p>GK Choppa traces his heritage to the <strong>Buganda Royal Family (Balangira Clan)</strong>, a lineage historically associated with leadership, service, and governance within the Buganda Kingdom.</p>
            
            <div class="family-section">
                <div class="family-title">Parents</div>
                <ul class="family-list">
                    <li><strong>Mother:</strong> Sarah Muwanguzi Kikulwe</li>
                    <li><strong>Father:</strong> Prince Geoffrey Kikulwe</li>
                </ul>
            </div>

            <div class="family-section">
                <div class="family-title">Grandparents & Ancestral Line</div>
                <ul class="family-list">
                    <li><strong>Namagembe Alexier</strong></li>
                    <li><strong>Joswa Misango (Yoswa Misango):</strong> Treasurer of King Daudi Chwa of Buganda and one of the most successful men of his time</li>
                    <li><strong>Sir Apollo Kagwa:</strong> One of the most powerful leaders in Buganda history, Katikiro (Prime Minister) of Buganda, signatory to the 1900 Agreement, played a major role in shaping modern Buganda's political structure and authored important historical books</li>
                    <li><strong>Mama Jibwa Misango:</strong> Eldest daughter of Sir Apollo Kagwa and wife of Joswa Misango. Raised in Lubiri Mengo (King's Palace), she was entrusted with raising King Daudi Chwa of Buganda</li>
                    <li><strong>Prince Yoswa Jjunko</strong></li>
                    <li><strong>Prince Sauna Lukas</strong></li>
                    <li><strong>King Kateregga of Buganda:</strong> One of the greatest kings of Buganda, a warrior who helped expand Buganda territory and solidify the central authority of the monarchy</li>
                </ul>
            </div>

            <div class="heritage-note">
                This heritage strongly influences GK Choppa's values of leadership, responsibility, and community service.
            </div>

            <h3>Family Wealth</h3>
            <p>GK Choppa's financial foundation is strengthened by family wealth built over generations, including legacy assets and land holdings.</p>
        </section>

        <!-- Philosophy Section -->
        <section id="philosophy">
            <h2>Leadership Philosophy</h2>
            <p>Grounded in technology, heritage, and impact, GK Choppa believes wealth should serve a broader purpose—building institutions, empowering people, and sustaining communities for generations.</p>
            
            <h3>Focus Areas</h3>
            <div class="focus-grid">
                <div class="focus-item">Community Food & Financial Support</div>
                <div class="focus-item">Youth & Social Empowerment</div>
                <div class="focus-item">Real Estate & Construction</div>
                <div class="focus-item">Technology & Innovation</div>
                <div class="focus-item">Legacy & Institution Building</div>
            </div>

            <h3>Lifestyle</h3>
            <p>Known for a luxurious lifestyle, success, and building a business empire. GK Choppa lives and operates mainly from <strong>Durban, South Africa</strong>, and <strong>Kampala, Uganda</strong>.</p>
        </section>

    </div>

    <!-- Footer -->
    <footer>
        <p class="footer-text">© 2024 GK Choppa. All Rights Reserved.</p>
        <p class="locations">Durban, South Africa • Kampala, Uganda</p>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>

</body>
</html>
