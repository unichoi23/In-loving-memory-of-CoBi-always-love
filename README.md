<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cobi | 2013—2026</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Playfair+Display:ital,wght@0,400;1,400&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #F9F7F2;      /* Soft architectural off-white */
            --primary-brown: #5D4037; /* The "Classic Brown" from the tote project */
            --text-main: #2C2C2C;
            --accent-tan: #D7CCC8;
        }

        body {
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
        }

        header {
            padding: 80px 20px;
            text-align: center;
            border-bottom: 1px solid var(--accent-tan);
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3.5rem;
            margin: 0;
            font-weight: 400;
            letter-spacing: -1px;
        }

        .dates {
            font-size: 1.1rem;
            color: var(--primary-brown);
            letter-spacing: 3px;
            margin-top: 10px;
            text-transform: uppercase;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        .hero-image {
            width: 100%;
            height: 500px;
            background-color: var(--accent-tan);
            background-image: url('cobi-main.jpg'); /* Replace with your favorite photo */
            background-size: cover;
            background-position: center;
            margin-bottom: 60px;
            border-radius: 2px;
        }

        .story {
            font-size: 1.2rem;
            margin-bottom: 80px;
            column-count: 2;
            column-gap: 40px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .gallery img {
            width: 100%;
            aspect-ratio: 1 / 1;
            object-fit: cover;
            filter: grayscale(20%);
            transition: filter 0.3s ease;
        }

        .gallery img:hover {
            filter: grayscale(0%);
        }

        footer {
            text-align: center;
            padding: 100px 20px;
            font-family: 'Playfair Display', serif;
            font-style: italic;
            color: var(--primary-brown);
        }

        @media (max-width: 768px) {
            .story { column-count: 1; }
            h1 { font-size: 2.5rem; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Cobi</h1>
        <div class="dates">2013 — 2026</div>
    </header>

    <div class="container">
        <div class="hero-image"></div>
        
        <section class="story">
            <p>
                From the sidewalks of New York to every site visit and quiet evening, 
                Cobi was more than a companion—she was the heart of the home for thirteen years. 
                Her presence was a constant, grounding force through every project and change of season.
            </p>
            <p>
                This space serves as a digital memorial to a life well-lived, 
                capturing the spirit of a dog who saw the world with quiet wisdom 
                and unconditional loyalty.
            </p>
        </section>

        <div class="gallery">
            <img src="gallery1.jpg" alt="Cobi in NYC">
            <img src="gallery2.jpg" alt="Cobi relaxing">
            <img src="gallery3.jpg" alt="Cobi memorial">
        </div>
    </div>

    <footer>
        "A piece of New York, a piece of our hearts."
    </footer>

</body>
</html>
