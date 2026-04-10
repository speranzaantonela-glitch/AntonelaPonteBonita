# <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ponte Bonita | Catálogo</title>
    <style>
        :root {
            --accent-pink: #ff2d55;
            --soft-purple: #7928ca;
            --neon-blue: #00f2fe;
            --dark-bg: #0d0d0d;
        }

        body {
            background: linear-gradient(180deg, #0d0d0d 0%, #1a1a1a 100%);
            color: white;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 20px;
            text-align: center;
        }

        h1 {
            font-size: 2.5rem;
            background: linear-gradient(to right, var(--accent-pink), var(--neon-blue));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 30px;
        }

        .grid-productos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .card {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 20px;
            padding: 15px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
            backdrop-filter: blur(10px);
        }

        .card:hover {
            transform: translateY(-10px);
            border-color: var(--accent-pink);
            box-shadow: 0 10px 25px rgba(255, 45, 85, 0.3);
        }

        .image-container {
            width: 100%;
            height: 200px;
            border-radius: 15px;
            overflow: hidden;
            background: #222;
        }

        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .nombre {
            font-size: 1.2rem;
            margin: 15px 0 10px;
            color: var(--neon-blue);
            font-weight: bold;
        }

        .precio {
            font-size: 1.5rem;
            color: #4cd137;
            font-weight: 800;
            margin-bottom: 10px;
        }

        .btn-comprar {
            background: var(--accent-pink);
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 50px;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            transition: 0.3s;
        }

        .btn-comprar:hover {
            background: white;
            color: var(--accent-pink);
            box-shadow: 0 0 15px white;
        }
    </style>
</head>
<body>

    <h1>✨ Ponte Bonita ✨</h1>

    <div class="grid-productos">

        <div class="card">
            <div class="image-container">
                <img src="https://i.ibb.co/mFbZRs7b/Ampollas.jpg" alt="Ampollas">
            </div>
            <div class="nombre">Ampollas</div>
            <div class="precio">$1.500</div>
            <a href="#" class="btn-comprar">Pedir por WhatsApp</a>
        </div>

        <div class="card">
            <div class="image-container">
                <img src="https://i.ibb.co/C51QtYML/Arqueadores.jpg" alt="Arqueadores">
            </div>
            <div class="nombre">Arqueadores</div>
            <div class="precio">$4.000</div>
            <a href="#" class="btn-comprar">Pedir por WhatsApp</a>
        </div>

        <div class="card">
            <div class="image-container">
                <img src="https://i.ibb.co/Nd9K7Ls5/Balsamo-Limon.jpg" alt="Balsamo Limon">
            </div>
            <div class="nombre">Bálsamo Limón</div>
            <div class="precio">$2.000</div>
            <a href="#" class="btn-comprar">Pedir por WhatsApp</a>
        </div>

    </div>

</body>
</html>
