<!DOCTYPE html>
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
        .project-card { background: white; border: 1px solid #eee; text-align: left; padding: 20px; margin-top: 30px; display: flex; flex-direction: column; align-items: center; }
        .project-text { max-width: 800px; text-align: center; }

        /* Meet the Team */
        .team-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; margin-top: 40px; }
        .team-member { padding: 20px; border: 1px solid #eee; background: white; }
        .team-member h3 { margin-bottom: 5px; color: #444; }
        .team-member span { font-style: italic; color: #888; font-size: 14px; }

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
        <a href="#team">Team</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Livable Luxury.</h1>
        <p>Turning historic estates into modern family homes.</p>
        <a href="#contact" class="btn">Book a Consultation</a>
    </div>
</section>

<section id="spotlight" class="container section-light">
    <h2>Project Spotlight</h2>
    <div class="project-card">
        <div class="project-text">
            <h3>The Manor Restoration</h3>
            <p>Our most rewarding project to date. We worked closely with the <strong>Malfoy family</strong> to transform a cold, imposing ancestral estate into a sanctuary of light. By softening stone walls with warm oak and replacing dark velvet with breathable linens, we helped create a space where a father and son could truly feel at home.</p>
            <p><em>"A home should reflect who you are today, not who you were yesterday." — L. Malfoy</em></p>
        </div>
    </div>
</section>

<section id="about" class="container section-alt">
    <h2>Our Philosophy</h2>
    <p>At StyleWell, we specialize in the "Redemption of Space." We believe that no room is too dark to be brightened and no history is too heavy to be modernized. Our designs focus on <strong>Well-being</strong>, ensuring that every corner of your home provides comfort, safety, and a sense of belonging.</p>
</section>

<section id="team" class="container section-light">
    <h2>Meet the Partners</h2>
    <div class="team-grid">
        <div class="team-member">
            <h3>Draco</h3>
            <span>Lead Aesthetic Director</span>
            <p>Specializes in high-end materials and preserving architectural heritage with a modern, elegant twist.</p>
        </div>
        <div class="team-member">
            <h3>Hermione</h3>
            <span>Lead Architect & Strategist</span>
            <p>The brilliance behind the structure. She ensures every design is functional, logical, and perfectly organized.</p>
        </div>
        <div class="team-member">
            <h3>Harry</h3>
            <span>Project Oversight</span>
            <p>Ensures the heart of the home is never lost, focusing on comfort and the feeling of sanctuary.</p>
        </div>
    </div>
</section>

<section id="contact" class="container section-alt">
    <h2>Start Your Journey</h2>
    <p>Send an inquiry to our team below.</p>
    <div class="contact-form">
        <form action="https://formspree.io/f/xaqqldlv" method="POST">
            <input type="hidden" name="_next" value="https://noyonika0805.github.io/stylewell/thank-you.html">
            
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Describe your dream space..." rows="5" required></textarea>
            <button type="submit" class="btn">Send Inquiry</button>
        </form>
    </div>
</section>

<footer>
    &copy; 2026 StyleWell Interior Design. All rights reserved. <br>
    Consulting on the redemption of historic estates.
</footer>

</body>
</html>
