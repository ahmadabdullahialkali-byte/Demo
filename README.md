<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Business Name - Professional Solutions</title>
    <style>
        /* Simple modern CSS - fully responsive */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', Arial, sans-serif; line-height: 1.6; color: #333; }
        header { background: linear-gradient(135deg, #007bff, #00c6ff); color: white; padding: 1rem 0; position: sticky; top: 0; z-index: 100; }
        nav { max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; padding: 0 2rem; }
        .logo { font-size: 1.8rem; font-weight: bold; }
        .nav-links a { color: white; text-decoration: none; margin-left: 2rem; font-weight: 500; }
        .hero { background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://picsum.photos/1920/1080?business') center/cover no-repeat; height: 100vh; display: flex; align-items: center; color: white; text-align: center; }
        .hero-content { max-width: 800px; margin: 0 auto; padding: 2rem; }
        .hero h1 { font-size: 3.5rem; margin-bottom: 1rem; }
        .hero p { font-size: 1.4rem; margin-bottom: 2rem; }
        .btn { background: #ff9800; color: white; padding: 14px 32px; border: none; border-radius: 50px; font-size: 1.1rem; cursor: pointer; text-decoration: none; display: inline-block; }
        .btn:hover { background: #f57c00; }
        section { padding: 80px 20px; max-width: 1200px; margin: 0 auto; }
        h2 { text-align: center; font-size: 2.5rem; margin-bottom: 3rem; color: #222; }
        .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .card { background: white; padding: 2rem; border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); text-align: center; transition: transform 0.3s; }
        .card:hover { transform: translateY(-10px); }
        .testimonial { background: #f8f9fa; font-style: italic; }
        .footer { background: #222; color: white; text-align: center; padding: 3rem 1rem; }
        form { max-width: 600px; margin: 0 auto; display: grid; gap: 1rem; }
        input, textarea { padding: 12px; border: 1px solid #ddd; border-radius: 8px; }
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            nav { flex-direction: column; gap: 1rem; }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo"> Alkali's exchange </div>
            <div class="nav-links">
                <a href="#about">About</a>
                <a href="#services">Services</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1> Simplify Your Currency Exchange with Trusted Expertise</h1>
            <p> We provide fast, secure, and reliable foreign exchange services to help you send, receive, and convert money with ease.</p>
            <a href="#contact" class="btn">Get a Free Consultation</a>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p style="max-width: 800px; margin: 0 auto; text-align: center; font-size: 1.2rem;">
            At Alkalis exchange, we are committed to providing fast, secure, and reliable currency exchange and international money transfer services. With a strong focus on customer satisfaction, we make it easy for individuals and businesses to access foreign currencies and carry out cross-border transactions with confidence.
        </p>
    </section>

    <section id="services" style="background: #f8f9fa;">
        <h2>Our Services</h2>
        <div class="services">
            <div class="card">
                <h3>currency Exchange </h3>
                <p>Buying and selling foreign currencies (e.g., USD, EUR, GBP)</p>
                <p>Converting one currency into another at current exchange rates</p>
            </div>
            <div class="card">
                <h3> International Money Transfers</h3>
                <p> Sending money abroad to individuals or businesses</p>
                <p> Receiving money from other countries</p>
            </div>
            <div class="card">
                <h3> Travel Money Services</h3>
                <p> Providing foreign cash for travelers</p>
                <p> Prepaid travel cards loaded with multiple currencies</p>
            </div>
            <div class="card">
            <h3>Foreign Currency Accounts</h3>
            <p>Holding money in different currencies for businesses or individuals</p>
            <p>Useful for international trade or frequent travelers</p>
        </div>
    </section>

    <section class="testimonial">
        <h2>What Our Clients Say</h2>
        <p style="max-width: 700px; margin: 0 auto; text-align: center; font-size: 1.3rem;">
            "Working with Alkalis Exchange Company has made our international transactions fast and stress-free. Their rates are competitive and their service is highly reliable." 
            <br><strong>-- Muhammad Sani, Import & Export Trader</strong>
            <p style="max-width: 700px; margin: 0 auto; text-align: center; font-size: 1.3rem;">
            "Thanks to Alkalis Exchange Company, managing foreign payments for my business has become smooth and efficient"
            <br><strong>Ibrahim Musa, Entrepreneur</strong>
        </p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="https://formspree.io/f/your-form-id" method="POST"> <!-- Replace with your Formspree or similar free service -->
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit" class="btn" style="width: 100%;">Send Message</button>
        </form>
        <p style="text-align: center; margin-top: 2rem;">📍 kano, Nigeria | 📞 +2347038128953 | ✉️ info@alkalisexchange.com</p>
    </section>

    <footer class="footer">
        <p>&copy; 2026 Your Business Name. All Rights Reserved.</p>
    </footer>

    <script>
        // Simple smooth scrolling for navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
