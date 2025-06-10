<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Misango - Your Consultation Partner</title>
    <style>
        /* Basic Reset & Body Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        /* Header Styles */
        header {
            background-color: #004d40; /* Dark teal */
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap; /* Allows nav items to wrap on smaller screens */
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: #00796b; /* Lighter teal on hover */
            border-radius: 5px;
        }

        /* Main Content Styling */
        main {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }

        section {
            background-color: #fff;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #004d40;
            text-align: center;
            margin-bottom: 20px;
            font-size: 2em;
        }

        /* Hero Section */
        .hero {
            background-color: #e0f2f1; /* Very light teal */
            text-align: center;
            padding: 60px 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .hero h2 {
            color: #004d40;
            font-size: 3em;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.2em;
            color: #555;
            max-width: 800px;
            margin: 0 auto 30px auto;
        }

        .button {
            display: inline-block;
            background-color: #00796b; /* Lighter teal */
            color: #fff;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #004d40; /* Darker teal on hover */
        }

        /* Services Section Specifics */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .service-item {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.08);
            text-align: center;
        }

        .service-item h3 {
            color: #00796b;
            margin-top: 0;
        }

        /* Contact Section Specifics */
        .contact-info p {
            font-size: 1.1em;
            margin-bottom: 10px;
            text-align: center;
        }

        .contact-info a {
            color: #00796b;
            text-decoration: none;
            font-weight: bold;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 30px;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
            }
            nav ul li {
                margin: 10px 0;
            }
            .hero h2 {
                font-size: 2.5em;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Misango</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="home" class="hero">
            <h2>Empowering Your Vision, Together.</h2>
            <p>At Misango, we provide expert consultation services to help businesses and individuals navigate complex challenges, optimize operations, and achieve sustainable growth.</p>
            <a href="#contact" class="button">Get a Consultation</a>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <div class="services-grid">
                <div class="service-item">
                    <h3>Strategic Planning</h3>
                    <p>Develop clear, actionable strategies to align your goals with market opportunities.</p>
                </div>
                <div class="service-item">
                    <h3>Business Development</h3>
                    <p>Identify new growth avenues and expand your market presence effectively.</p>
                </div>
                <div class="service-item">
                    <h3>Financial Advisory</h3>
                    <p>Expert guidance on financial management, investment, and risk mitigation.</p>
                </div>
                <div class="service-item">
                    <h3>Digital Transformation</h3>
                    <p>Integrate modern technology to streamline processes and enhance productivity.</p>
                </div>
                <div class="service-item">
                    <h3>Operational Efficiency</h3>
                    <p>Analyze and optimize your operational workflows for maximum output.</p>
                </div>
                <div class="service-item">
                    <h3>Market Research</h3>
                    <p>Gain deep insights into market trends and customer behavior for informed decisions.</p>
                </div>
            </div>
        </section>

        <section id="about">
            <h2>About Misango</h2>
            <p>Misango is a dedicated consultation firm committed to delivering tailored solutions that drive tangible results. With a team of experienced professionals, we pride ourselves on our client-centric approach, deep industry knowledge, and unwavering commitment to excellence. We believe in fostering long-term partnerships built on trust, transparency, and shared success.</p>
            <p>Our mission is to empower our clients to make informed decisions, overcome challenges, and seize opportunities in an ever-evolving global landscape.</p>
        </section>

        <section id="contact" class="contact-info">
            <h2>Contact Us</h2>
            <p>Ready to transform your business? Get in touch with Misango today!</p>
            <p><strong>Phone:</strong> <a href="tel:+254759237349">+254759237349</a></p>
            <p><strong>Email:</strong> <a href="mailto:misangoi67@gmail.com">misangoi67@gmail.com</a></p>
            <p>We look forward to hearing from you and discussing how we can help achieve your goals.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Misango. All rights reserved.</p>
    </footer>
</body>
</html>


