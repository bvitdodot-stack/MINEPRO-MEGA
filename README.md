**<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MINEPRO MEGA | Minecraft Hub</title>
    <style>
        :root {
            --primary: #00ff00;
            --bg-dark: #050505;
            --card-bg: #121212;
            --gold: #ffcc00;
        }

        body {
            background-color: var(--bg-dark);
            color: #e0e0e0;
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            scroll-behavior: smooth;
        }

        header {
            background: rgba(0,0,0,0.9);
            padding: 20px;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 2px solid var(--primary);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            color: var(--primary);
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 14px;
            transition: 0.3s;
        }

        nav a:hover { color: var(--primary); }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://wallpaperaccess.com/full/215112.jpg');
            background-size: cover;
        }

        .search-box {
            margin: 20px 0;
            padding: 10px;
            width: 300px;
            border-radius: 20px;
            border: none;
            outline: none;
        }

        .section-title {
            text-align: center;
            margin-top: 50px;
            font-size: 32px;
            color: var(--primary);
        }

        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            padding: 40px;
        }

        .card {
            background: var(--card-bg);
            border-radius: 15px;
            padding: 20px;
            border: 1px solid #222;
            transition: 0.4s;
            position: relative;
        }

        .card:hover {
            border-color: var(--primary);
            transform: scale(1.03);
        }

        .tag {
            background: var(--primary);
            color: black;
            padding: 2px 8px;
            border-radius: 5px;
            font-size: 12px;
            font-weight: bold;
        }

        .btn {
            display: block;
            background: var(--primary);
            color: black;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 8px;
        }

        .vip-free {
            border: 2px solid var(--gold);
        }

        .vip-badge {
            color: var(--gold);
            font-size: 12px;
            font-weight: bold;
        }

        footer {
            background: #000;
            padding: 30px;
            text-align: center;
            border-top: 1px solid #222;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">MINEPRO MEGA</div>
    <nav>
        <a href="#mods">MODS / MODLAR</a>
        <a href="#resource">RESOURCES / RESURSLAR</a>
        <a href="#vip">FREE VIP / TEKIN VIP</a>
    </nav>
</header>

<div class="hero">
    <h1>Welcome to MINEPRO MEGA</h1>
    <p>Download the best Minecraft Mods & Resource Packs for Free!</p>
    <input type="text" class="search-box" placeholder="Search mods... / Modlarni qidirish...">
</div>

<h2 class="section-title" id="mods">LATEST MODS / YANGI MODLAR</h2>
<div class="container">
    <div class="card">
        <span class="tag">Forge</span>
        <h3>Furniture Mod</h3>
        <p>EN: Add modern furniture to your house.<br>UZ: Uyingiz uchun zamonaviy mebellar qo'shing.</p>
        <a href="https://www.curseforge.com/minecraft/mc-mods" class="btn">DOWNLOAD / YUKLASH</a>
    </div>

    <div class="card">
        <span class="tag">Fabric</span>
        <h3>Better Nether</h3>
        <p>EN: Complete overhaul of the Nether dimension.<br>UZ: Nether olamini butunlay yangilaydi.</p>
        <a href="https://www.curseforge.com/minecraft/mc-mods" class="btn">DOWNLOAD / YUKLASH</a>
    </div>
</div>

<h2 class="section-title" id="vip">FREE VIP SECTION / TEKIN VIP BO'LIMI</h2>
<div class="container">
    <div class="card vip-free">
        <span class="vip-badge">✨ EXCLUSIVE</span>
        <h3>God Mode Tools</h3>
        <p>EN: Get access to overpowered tools for free.<br>UZ: Eng kuchli asboblarni tekinga yuklab oling.</p>
        <a href="#" class="btn" style="background: var(--gold);">GET NOW / OLISH</a>
    </div>
    
    <div class="card vip-free">
        <span class="vip-badge">✨ PREMIUM</span>
        <h3>Custom Capes</h3>
        <p>EN: Amazing capes for your character.<br>UZ: Personajingiz uchun ajoyib plashlar.</p>
        <a href="#" class="btn" style="background: var(--gold);">GET NOW / OLISH</a>
    </div>
</div>

<footer>
    <p>MINEPRO MEGA &copy; 2026 | Created for Minecraft Fans</p>
    <p style="font-size: 12px; color: #666;">English & Uzbek Language Supported</p>
</footer>

</body>
</html>**
