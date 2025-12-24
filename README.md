# omarhanafy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Explore the World</title>

    <!-- CSS INSIDE THE SAME FILE -->
    <style>
        /* General */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Header */
        header {
            background: #111;
            color: gold;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 40px;
        }

        header h1 {
            margin: 0;
        }

        nav a {
            color: gold;
            margin-left: 20px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(to right, #000, #333);
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        .hero h2 {
            font-size: 40px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        .hero button {
            background: gold;
            border: none;
            padding: 12px 25px;
            font-size: 16px;
            cursor: pointer;
            font-weight: bold;
        }

        .hero button:hover {
            background: #d4af37;
        }

        /* Cards */
        .cards {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 40px;
        }

        .card {
            background: white;
            padding: 25px;
            width: 250px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .card h3 {
            color: #111;
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            background: #111;
            color: gold;
            text-align: center;
            padding: 15px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .cards {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <header>
        <h1>Explore</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Destinations</a>
            <a href="#">Gallery</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <!-- Hero -->
    <section class="hero">
        <h2>Discover Beautiful Places</h2>
        <p>Travel the world and create unforgettable memories.</p>
        <button>Get Started</button>
    </section>

    <!-- Cards -->
    <section class="cards">
        <div class="card">
            <h3>Europe</h3>
            <p>History, culture, and breathtaking cities.</p>
        </div>
        <div class="card">
            <h3>Asia</h3>
            <p>Traditions, food, and stunning landscapes.</p>
        </div>
        <div class="card">
            <h3>Africa</h3>
            <p>Nature, wildlife, and ancient civilizations.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2025 Explore the World. All rights reserved.</p>
    </footer>

</body>
</html>
