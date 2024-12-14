# rajai_digital_marketing-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rajai Digital Marketing</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #fffde7; /* Light yellow background */
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background: #4CAF50;
        }
        .container {
            padding: 20px;
        }
        .services, .offers, .about, .testimonials {
            margin-bottom: 20px;
        }
        .service-card, .offer-card, .testimonial-card {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            background: #f9f9f9;
            display: flex;
            align-items: center;
        }
        .service-card img, .testimonial-card img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            margin-right: 15px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
        }
        .whatsapp-chat {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25d366;
            border-radius: 50%;
            width: 60px;
            height: 60px;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .whatsapp-chat img {
            width: 40px;
            height: 40px;
        }
    </style>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const links = document.querySelectorAll("nav a");
            links.forEach(link => {
                link.addEventListener("click", function(event) {
                    event.preventDefault();
                    const target = document.querySelector(this.getAttribute("href"));
                    if (target) {
                        target.scrollIntoView({ behavior: "smooth" });
                    }
                });
            });
        });
    </script>
</head>
<body>
    <header>
        <h1>Welcome to Rajai Digital Marketing</h1>
    </header>
    <nav>
        <a href="#services">Services</a>
        <a href="#offers">Offers</a>
        <a href="#about">About</a>
        <a href="#testimonials">Testimonials</a>
    </nav>
    <div class="container">
        <section id="services" class="services">
            <h2>Our Services</h2>
            <div class="service-card">
                <img src="https://via.placeholder.com/80" alt="Social Media Management">
                <div>
                    <h3>Social Media Management</h3>
                    <p>Manage your social media with effective strategies and content creation.</p>
                </div>
            </div>
            <div class="service-card">
                <img src="https://via.placeholder.com/80" alt="Meta Ads Campaign">
                <div>
                    <h3>Meta Ads Campaign</h3>
                    <p>Boost your reach with targeted ad campaigns on social media.</p>
                </div>
            </div>
            <div class="service-card">
                <img src="https://via.placeholder.com/80" alt="Graphic Design">
                <div>
                    <h3>Graphic Design</h3>
                    <p>Get eye-catching designs for your brand's marketing needs.</p>
                </div>
            </div>
        </section>

        <section id="offers" class="offers">
            <h2>Our Offers</h2>
            <div class="offer-card">
                <h3>Basic Package</h3>
                <p>₹6,099/month - Social Media Management for 2 platforms and 20 posts/month.</p>
            </div>
            <div class="offer-card">
                <h3>Premium Package</h3>
                <p>₹11,099/month - Includes social media management for 3 platforms, 30 posts/month, and Meta Ads (₹5,000 Ad Spend Included).</p>
            </div>
        </section>

        <section id="about" class="about">
            <h2>About Us</h2>
            <p>Rajai Digital Marketing is dedicated to helping businesses grow through innovative marketing strategies, creative content, and result-driven campaigns. Our mission is to bring more leads and revenue to our clients.</p>
        </section>

        <section id="testimonials" class="testimonials">
            <h2>Customer Testimonials</h2>
            <div class="testimonial-card">
                <img src="https://via.placeholder.com/80" alt="Client Photo">
                <div>
                    <p>"Rajai Digital Marketing transformed our online presence and brought us more leads than ever before!" - Happy Client</p>
                </div>
            </div>
            <div class="testimonial-card">
                <img src="https://via.placeholder.com/80" alt="Customer Photo">
                <div>
                    <p>"Highly professional team with exceptional creativity. Highly recommended!" - Satisfied Customer</p>
                </div>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Rajai Digital Marketing. All Rights Reserved.</p>
    </footer>

    <!-- WhatsApp Chat Button -->
    <a href="https://wa.me/7339033687" target="_blank" class="whatsapp-chat">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp Chat">
    </a>
</body>
</html>
