# hubackova-photography
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hubáčková Photography</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            color: #333;
            line-height: 1.6;
            background-color: #f8f8f8;
        }
        header {
            background: #222;
            color: #fff;
            padding: 1rem 2rem;
            text-align: center;
        }
        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            margin: 0;
        }
        header p {
            margin: 0;
            font-size: 1.2rem;
        }
        nav {
            background: #444;
            color: #fff;
            padding: 0.5rem 2rem;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: 500;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x600') center/cover no-repeat;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
        }
        .hero h2 {
            font-size: 2.5rem;
            font-family: 'Playfair Display', serif;
        }
        .section {
            padding: 2rem;
            text-align: center;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }
        .gallery img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        footer {
            background: #222;
            color: #fff;
            text-align: center;
            padding: 1rem;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hubáčková Photography</h1>
        <p>Zachycení krásy okamžiku</p>
    </header>

    <nav>
        <a href="#portfolio">Portfolio</a>
        <a href="#about">O mně</a>
        <a href="#pricing">Ceník</a>
        <a href="#contact">Kontakt</a>
    </nav>

    <section class="hero">
        <h2>Vítejte ve světě fotografie</h2>
    </section>

    <section id="portfolio" class="section">
        <h2>Portfolio</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/400" alt="Ukázka 1">
            <img src="https://via.placeholder.com/400" alt="Ukázka 2">
            <img src="https://via.placeholder.com/400" alt="Ukázka 3">
            <img src="https://via.placeholder.com/400" alt="Ukázka 4">
        </div>
    </section>

    <section id="about" class="section">
        <h2>O mně</h2>
        <p>Jsem vášnivá fotografka, která miluje zachytit jedinečné okamžiky. Můj styl kombinuje kreativitu a přirozenost, aby vaše vzpomínky zůstaly nezapomenutelné.</p>
    </section>

    <section id="pricing" class="section">
        <h2>Ceník</h2>
        <p>Vytvořím balíček na míru podle vašich potřeb. Kontaktujte mě pro více informací!</p>
    </section>

    <section id="contact" class="section">
        <h2>Kontakt</h2>
        <p>Email: <a href="mailto:hubackova@example.com">hubackova@example.com</a></p>
        <p>Telefon: +420 123 456 789</p>
    </section>

    <footer>
        <p>&copy; 2025 Hubáčková Photography. Všechna práva vyhrazena.</p>
    </footer>
</body>
</html>
