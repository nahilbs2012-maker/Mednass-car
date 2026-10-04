# Mednass-car<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mednass Car - Location de Voitures à Mohammedia</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #1a1a1a;
            color: #fff;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #e63946;
        }

        .btn-header {
            background-color: #25d366;
            color: white;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
            height: 70vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 0 1rem;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            max-width: 600px;
        }

        .btn-primary {
            background-color: #e63946;
            color: white;
            padding: 0.8rem 2rem;
            text-decoration: none;
            font-size: 1.1rem;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn-primary:hover {
            background-color: #c1121f;
        }

        .container {
            max-width: 1100px;
            margin: 3rem auto;
            padding: 0 1rem;
        }

        .section-title {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
            color: #1a1a1a;
        }

        .fleet-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }

        .car-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            text-align: center;
            padding-bottom: 1.5rem;
        }

        .car-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .car-card h3 {
            margin: 1rem 0 0.5rem 0;
        }

        .car-card p {
            color: #666;
            margin-bottom: 1rem;
        }

        .info-section {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            margin-top: 3rem;
        }

        footer {
            background-color: #1a1a1a;
            color: white;
            text-align: center;
            padding: 1.5rem;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Mednass Car</div>
        <a href="https://wa.me/212661731841" class="btn-header" target="_blank">WhatsApp</a>
    </header>

    <section class="hero">
        <h1>Location de Voitures à Mohammedia</h1>
        <p>Un service rapide, fiable et au meilleur prix. Réservez votre véhicule en quelques clics.</p>
        <a href="https://wa.me/212661731841" class="btn-primary" target="_blank">Réserver sur WhatsApp</a>
    </section>

    <div class="container">
        <h2 class="section-title">Nos Véhicules</h2>
        <div class="fleet-grid">
            <div class="car-card">
                <img src="https://images.unsplash.com/photo-1541899481282-d53bffe3c35d?auto=format&fit=crop&w=500&q=80" alt="Voiture Citadine">
                <h3>Citadines</h3>
                <p>Idéal pour vos déplacements en ville.</p>
                <a href="https://wa.me/212661731841?text=Bonjour,%20je%20souhaite%20réserver%20une%20citadine." class="btn-primary" target="_blank">Réserver</a>
            </div>
            <div class="car-card">
                <img src="https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=500&q=80" alt="Voiture Berline">
                <h3>Berlines</h3>
                <p>Confort optimal pour les longs trajets.</p>
                <a href="https://wa.me/212661731841?text=Bonjour,%20je%20souhaite%20réserver%20une%20berline." class="btn-primary" target="_blank">Réserver</a>
            </div>
            <div class="car-card">
                <img src="https://images.unsplash.com/photo-1519641471654-76ce0107ad1b?auto=format&fit=crop&w=500&q=80" alt="Voiture SUV">
                <h3>SUVs</h3>
                <p>Espace et puissance pour vos sorties.</p>
                <a href="https://wa.me/212661731841?text=Bonjour,%20je%20souhaite%20réserver%20un%20SUV." class="btn-primary" target="_blank">Réserver</a>
            </div>
        </div>

        <div class="info-section">
            <h2 class="section-title">Contact & Localisation</h2>
            <p><strong>Adresse :</strong> Immeuble 01 N°3, Résidence Nassime, GH 08, boulevard de la résistance, Mohammédia 28830</p>
            <p><strong>Téléphone / WhatsApp :</strong> +212 6 61 73 18 41</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Mednass Car Mohammedia. Tous droits réservés.</p>
    </footer>

</body>
</html>
