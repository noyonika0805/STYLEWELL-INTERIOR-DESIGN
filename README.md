<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StyleWell | Interior Design Firm</title>
    <style>
        /* Global Styles */
        body { font-family: 'Georgia', serif; margin: 0; color: #333; line-height: 1.6; scroll-behavior: smooth; }
        header { background: #fff; padding: 20px 50px; display: flex; justify-content: space-between; align-items: center; border-bottom: 1px solid #eee; position: sticky; top: 0; z-index: 100; }
        .logo { font-size: 24px; font-weight: bold; letter-spacing: 2px; text-decoration: none; color: #333; }
        nav a { margin-left: 20px; text-decoration: none; color: #555; text-transform: uppercase; font-size: 12px; font-weight: bold; }
        
        /* Hero Section */
        .hero { height: 80vh; background: #f4f4f4 url('https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&q=80&w=1974') center/cover; display: flex; align-items: center; justify-content: center; text-align: center; color: white; }
        .hero-content { background: rgba(0,0,0,0.5); padding: 50px; border-radius: 2px; border: 1px solid rgba(255,255,255,0.3); }
        .hero-content h1 { font-size: 48px; margin: 0; letter-spacing: 5px; text-transform: uppercase; }
        
        /* Layout */
        .container { padding: 80px 10%; text-align: center; }
        .section-light { background: #fff; }
        .section-alt { background: #f9f9f9; }
        h2 { font-size: 32px; margin-bottom: 30px; text-transform: uppercase; letter-spacing: 3px; border-bottom: 1px solid #ddd; display: inline-block; padding-bottom: 10px; }
        
        /* Project Spotlight */
        .project-card { background: white; border: 1px solid #eee; text-align: left; padding: 40px; margin-top: 30px; display: flex; flex-direction: column; align-items: center; }
        .project-text { max-width: 800px; text-align: center; }

        /* Form */
        .contact-form { max-width: 600px; margin: 40px auto 0; text-align: left; }
        .contact-form input, .contact-form textarea { width: 100%; padding: 12px; margin: 10px 0; border: 1px solid #ddd; font-family: 'Arial', sans-serif; box-sizing: border-box; }
        .btn { background: #333; color: white; padding: 15px 40px; text-decoration: none; border: none; cursor: pointer; text-transform: uppercase; letter-spacing: 2px; transition: 0.3s; }
        .btn:hover { background: #555; }
        
        footer { padding: 50px; text-align: center; background: #333; color: #999; font-size: 12px; }
    </style>
</head>
<body>

<header>
    <a href="#" class="logo">STYLEWELL</a>
    <nav>
        <a href="#spotlight">Projects</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Livable Luxury.</h1>
        <p>Bespoke interiors designed for the modern lifestyle.</p>
        <a href="#contact" class="btn">Book a Consultation</a>
    </div>
</section>

<section id="spotlight" class="container section-light">
    <h2>Project Spotlight</h2>
    <div class="project-card">
        <div class="project-text">
            <h3>Urban Sanctuary</h3>
            <p>Our latest project focused on bringing natural light and organic textures into a downtown loft. By utilizing sustainable materials and an open-concept layout, we created a peaceful retreat amidst the city's energy.</p>
        </div>
    </div>
</section>

<section id="about" class="container section-alt">
    <h2>Our Philosophy</h2>
    <p>At StyleWell, we believe your environment dictates your energy. We specialize in creating high-end interiors that prioritize balance, light, and functional elegance. Our mission is to design spaces that feel curated yet deeply personal.</p>
</section>

<section id="contact" class="container section-light">
    <h2>Start Your Journey</h2>
    <p>Send an inquiry to our team below.</p>
    <div class="contact-form">
        <form action="https://formspree.io/f/xaqqldlv" method="POST">
            <input type="hidden" name="_next" value="https://noyonika0805.github.io/stylewell/thank-you.html">
            
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Describe your project vision..." rows="5" required></textarea>
            <button type="submit" class="btn">Send Inquiry</button>
        </form>
    </div>
</section>

<footer>
    &copy; 2026 StyleWell Interior Design. All rights reserved.
</footer>

</body>
</html>
