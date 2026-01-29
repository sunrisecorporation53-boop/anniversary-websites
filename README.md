# anniversary-websites
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>365 Days of Us | Jan 30, 2026</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        :root {
            --bg: #050505;
            --card-bg: rgba(20, 20, 20, 0.6);
            --accent: #ff4d6d;
            --accent-glow: rgba(255, 77, 109, 0.4);
            --text-main: #ffffff;
            --text-dim: #a0a0a0;
            --border: rgba(255, 255, 255, 0.1);
        }

        body { background-color: var(--bg); color: var(--text-main); font-family: 'Inter', sans-serif; overflow-x: hidden; line-height: 1.6; }
        .container { max-width: 1100px; margin: 0 auto; padding: 0 20px; }
        
        /* Big Romantic Header */
        .big-love {
            font-family: 'Dancing Script', cursive;
            font-size: clamp(4rem, 15vw, 10rem);
            color: var(--accent);
            text-shadow: 0 0 30px var(--accent-glow);
            margin: 20px 0;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        section { min-height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; padding: 80px 0; }

        /* Photo Gallery */
        .photo-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            width: 100%;
            margin-top: 50px;
        }

        .photo-card {
            background: var(--card-bg
