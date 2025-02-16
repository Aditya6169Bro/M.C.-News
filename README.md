<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minecraft 2 - Latest News & Rumors</title>

    <!-- ✅ SEO Meta Tags -->
    <meta name="description" content="Get the latest updates, rumors, and official news about Minecraft 2. Is Mojang working on a sequel? Find out here!">
    <meta name="keywords" content="Minecraft 2, Minecraft News, Mojang, Gaming Updates">
    <meta name="author" content="6169 Plays">
    <meta name="robots" content="index, follow">
    
    <!-- ✅ Open Graph (for Facebook & WhatsApp) -->
    <meta property="og:title" content="Minecraft 2 - Latest News & Rumors">
    <meta property="og:description" content="Find out everything about Minecraft 2: rumors, leaks, and official Mojang statements.">
    <meta property="og:image" content="https://wallpapercave.com/wp/wp11903650.jpg">
    <meta property="og:url" content="https://yourusername.github.io/minecraft2-news/">
    <meta property="og:type" content="website">

    <!-- ✅ Twitter Card -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Minecraft 2 - Latest News & Rumors">
    <meta name="twitter:description" content="Latest leaks & updates about Minecraft 2. Is it coming? Read now!">
    <meta name="twitter:image" content="https://wallpapercave.com/wp/wp11903650.jpg">

    <!-- ✅ Performance Optimization -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <script src="https://cdn.tailwindcss.com"></script>

    <style>
        /* Premium Grey Theme */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap');

        body {
            background: linear-gradient(180deg, #2d2d2d, #1c1c1c);
            color: #f5f5f5;
            font-family: 'Inter', sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background: #333;
            padding: 20px;
            border-bottom: 2px solid #555;
        }

        h1 {
            font-size: 2.2rem;
            font-weight: bold;
            color: #ffffff;
        }

        .news-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 40px;
        }

        .news-card {
            background: #404040;
            border: 1px solid #666;
            border-radius: 10px;
            padding: 20px;
            width: 90%;
            max-width: 500px;
            cursor: pointer;
            transition: transform 0.2s ease-in-out, background 0.3s ease-in-out;
            position: relative;
            overflow: hidden;
        }

        .news-card:hover {
            transform: scale(1.05);
            background: #505050;
        }

        .news-title {
            font-size: 1.4rem;
            font-weight: bold;
            color: #e0e0e0;
        }

        .news-content {
            font-size: 1rem;
            color: #d0d0d0;
            max-height: 0;
            overflow: hidden;
            opacity: 0;
            transition: max-height 0.4s ease-in-out, opacity 0.2s ease-in-out;
        }

        /* Expanded State */
        .news-card.expanded .news-content {
            max-height: 300px;
            opacity: 1;
            padding-top: 10px;
        }

        /* Footer */
        footer {
            background: #222;
            padding: 20px;
            margin-top: 30px;
            border-top: 2px solid #444;
            font-size: 0.9rem;
            color: #aaa;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Minecraft 2 - Latest News & Rumors</h1>
        <p style="font-size: 1rem; color: #bbbbbb;">Gaming News | Updates | Leaks</p>
    </header>

    <!-- News Section -->
    <div class="news-container">
        <!-- News 1 -->
        <div class="news-card" onclick="toggleNews(this)">
            <div class="news-title">Is 'Minecraft 2' Really Happening?</div>
            <div class="news-content">
                Rumors about **Minecraft 2** have been circulating online, but **Mojang officially denied working on a sequel**. Instead, they plan to continue **expanding the original game** with updates like "Ender Expansion" and AI Villagers.
            </div>
        </div>

        <!-- News 2 -->
        <div class="news-card" onclick="toggleNews(this)">
            <div class="news-title">What Would 'Minecraft 2' Look Like?</div>
            <div class="news-content">
                If Minecraft 2 ever happens, fans expect **improved graphics, larger biomes, smarter AI villagers, and infinite dimensions**. Some believe **RTX-style lighting** could be added as a default feature.
            </div>
        </div>

        <!-- News 3 -->
        <div class="news-card" onclick="toggleNews(this)">
            <div class="news-title">Why Mojang Prefers Updates Over a Sequel</div>
            <div class="news-content">
                Mojang believes **Minecraft is a platform, not just a game**. Instead of releasing a sequel, they focus on **major updates** to keep the game fresh while keeping the entire player base together.
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Premium Gaming News. All Rights Reserved.</p>
    </footer>

    <!-- JavaScript for Expanding News Cards -->
    <script>
        function toggleNews(card) {
            card.classList.toggle("expanded");
        }
    </script>

</body>
</html>
