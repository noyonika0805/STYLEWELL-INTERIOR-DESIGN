<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StyleWell | Bespoke Interior Design</title>
    <style>
        /* CSS RESET & BASE */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Georgia', serif; color: #333; line-height: 1.6; scroll-behavior: smooth; overflow-x: hidden; }

        /* NAVIGATION - Spread across the top */
        header { 
            background: #fff; 
            padding: 20px 5%; 
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
            border-bottom: 1px solid #eee; 
            position: fixed; 
            width: 100%; 
            top: 0; 
            z-index: 1000; 
        }
        .logo { font-size: 26px; font-weight: bold; letter-spacing: 4px; text-decoration: none; color: #1a1a1a; }
        nav a { margin-left: 35px; text-decoration: none; color: #555; text-transform: uppercase; font-size: 11px; font-weight: bold; letter-spacing: 1px; transition: 0.3s; }
        nav a:hover { color: #000; }

        /* HERO SECTION - Full screen height */
        .hero { 
            height: 100vh; 
            background: linear-gradient(rgba(0,0,0,0.2), rgba(0,0,0,0.2)), url('https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&q=80&w=1974') center/cover; 
            display: flex; 
            align-items: center; 
            padding: 0 5%; 
            color: white; 
        }
        .hero-content { max-width: 800px; }
        .hero-content h1 { font-size: 72px; text-transform: uppercase; letter-spacing: 8px; margin-bottom: 10px; line-height: 1; }
        .hero-content p { font-size: 20px; font-style: italic; margin-bottom: 30px; }

        /* SECTION STYLING - Spread edge-to-edge */
        section { width: 100%; padding: 100px 5%; min-height: 60vh; }
        .section-title { font-size: 32px; text-transform: uppercase; letter-spacing: 5px; margin-bottom: 50px; text-align: left; border-bottom: 1px solid #eee; padding-bottom: 15px; }

        /* PROJECTS GRID - Spread across the screen */
        .project-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
        .project-item { height: 600px; background-size: cover; background-position: center; position: relative; display: flex; align-items: flex-end; padding: 40px; color: white; text-decoration: none; transition: 0.4s; }
        .project-item:hover { filter: brightness(1.1); transform: scale(0.99); }
        .project-item h3 { font-size: 24px; text-transform: uppercase; letter-spacing: 2px; }

        /* ABOUT SECTION */
        #about { background-color: #f9f9f9; display: flex; align-items: center; gap: 50px; }
        .about-text { flex: 1; }
        .about-image { flex: 1; height: 500px; background: url('https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&q=80&w=1000') center/cover; }

        /* CONTACT SECTION */
        #contact { display: grid; grid-template-columns: 1fr 1fr; gap: 80px; background: #fff; }
        .form-area input, .form-area textarea { width: 100%; padding: 15px; margin-bottom: 20px; border: 1px solid #ddd; font-family: 'Arial', sans-serif; }
        .btn-send { background: #1a1a1a; color: #fff; padding: 15px 45px; border: none; text-transform: uppercase; letter-spacing: 2px; cursor: pointer; transition: 0.3s; }
        .btn-send:hover { background: #444; }

        /* FOOTER - Wide and Dark */
        footer { background: #111; color: #fff; padding: 80px 5%; display: grid; grid-template-columns: 2fr 1fr 1fr; gap: 50px; }
        footer h4 { text-transform: uppercase; letter-spacing: 2px; margin-bottom: 25px; color: #888; }
        footer p, footer a { color: #ccc; text-decoration: none; margin-bottom: 10px; display: block; font-size: 14px; }
        .copyright { grid-column: 1 / span 3; border-top: 1px solid #222; margin-top: 40px; padding-top: 20px; font-size: 11px; color: #555; }
    </style>
</head>
<body>

<header>
    <a href="#" class="logo">STYLEWELL</a>
    <nav>
        <a href="#home">Home</a>
        <a href="#projects">Portfolio</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</
