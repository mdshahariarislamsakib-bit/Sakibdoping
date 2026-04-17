<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Happy Birthday Sanjida 💖</title>
    <style>
        :root {
            --rose-pink: #ff4d6d;
            --soft-pink: #ffccd5;
            --neon-glow: rgba(255, 77, 109, 0.7);
            --bg-dark: #050505;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; user-select: none; -webkit-tap-highlight-color: transparent; }

        body {
            background-color: var(--bg-dark);
            color: white; font-family: 'Segoe UI', sans-serif;
            overflow: hidden; height: 100vh; width: 100vw;
            display: flex; justify-content: center; align-items: center;
        }

        #canvas-container { position: absolute; top: 0; left: 0; width: 100%; height: 100%; z-index: 1; }

        /* Background Vignette */
        .vignette {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: radial-gradient(circle, transparent 30%, rgba(0,0,0,0.8) 100%);
            z-index: 5; pointer-events: none;
        }

        /* Cinematic Intro Overlay */
        #intro-overlay {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: black; z-index: 1000; display: flex;
            flex-direction: column; justify-content: center; align-items: center;
            transition: opacity 2s ease-in-out;
        }

        .intro-text {
            font-family: 'Georgia', serif; font-style: italic; font-size: 1.6rem;
            color: var(--soft-pink); opacity: 0; position: absolute;
            text-align: center; text-shadow: 0 0 20px var(--neon-glow);
        }

        /* Main UI */
        #main-ui {
            position: relative; z-index: 10; text-align: center;
            opacity: 0; transition: opacity 3s ease-in; transform: scale(1.1);
        }

        .birthday-title {
            font-size: 3.2rem; font-weight: 800;
            background: linear-gradient(to bottom, #fff, var(--rose-pink));
            -webkit-background-clip: text; -webkit-text-fill-color: transparent;
            text-shadow: 0 10px 40px rgba(255, 77, 109, 0.5);
            margin-bottom: 10px;
        }

        .sub-title {
            font-family: 'Brush Script MT', cursive; font-size: 2.2rem;
            color: var(--soft-pink); animation: breathe 4s infinite ease-in-out;
        }

        /* Gift Button - Special Animation */
        #gift-btn {
            position: fixed; bottom: 50px; right: 30px; z-index: 100; font-size: 4rem;
            cursor: pointer; opacity: 0; transition: 1s;
            filter: drop-shadow(0 0 15px var(--rose-pink));
            animation: giftFloat 3s infinite ease-in-out;
        }

        /* Surprise Card */
        #reveal-overlay {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0, 0, 0, 0.95); z-index: 2000; display: none;
            justify-content: center; align-items: center; opacity: 0; transition: 0.5s;
        }

        .reveal-card {
            background: rgba(255, 255, 255, 0.05); backdrop-filter: blur(20px);
            padding: 20px; border-radius: 25px; border: 1px solid rgba(255, 77, 109, 0.5);
            text-align: center; box-shadow: 0 0 50px var(--neon-glow);
            max-width: 85%; transform: scale(0.2); transition: 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        #gift-image {
            width: 100%; border-radius: 15px; border: 2px solid white;
            box-shadow: 0 0 20px rgba(255,255,255,0.2);
        }

        #typing-text { margin-top: 15px; color: var(--soft-pink); font-family: 'Georgia', serif; font-size: 1.1rem; height: 25px; }

        @keyframes giftFloat {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(10deg); }
        }

        @keyframes breathe {
            0%, 100% { transform: scale(1); opacity: 0.8; }
            50% { transform: scale(1.05); opacity: 1; }
        }

        #footer { position: fixed; bottom: 10px; width: 100%; text-align: center; color: white; font-size: 9px; opacity: 0.4; z-index: 50; letter-spacing: 2px; }
    </style>
</head>
<body>

    <div id="intro-overlay">
        <div class="intro-text" id="intro-1">Today is a Golden Day... ✨</div>
        <div class="intro-text" id="intro-2">A Queen was Born... 👑</div>
        <div class="intro-text" id="intro-3">Happy Birthday Sanji 💕</div>
    </div>

    <div class="vignette"></div>
    <div id="canvas-container"><canvas id="mainCanvas"></canvas></div>
    
    <div id="gift-btn" onclick="openGift()">🎁</div>

    <div id="main-ui">
        <h1 class="birthday-title">HAPPY<br>BIRTHDAY</h1>
        <p class="sub-title">Sanjida ❤️</p>
    </div>

    <div id="reveal-overlay">
        <div class="reveal-card" id="card">
            <img id="gift-image" src="https://i.postimg.cc/BnBvxpMr/1000004432.jpg" alt="Sanjida">
            <div id="typing-text"></div>
            <button onclick="closeGift()" style="margin-top:20px; background:var(--rose-pink); border:none; color:white; padding:10px 30px; border-radius:20px; font-weight:bold; cursor:pointer;">With Love ❤️</button>
        </div>
    </div>

    <div id="footer">QALPÍK - AI ANIME STORIES. FOLLOW FOR MORE!</div>

    <script>
        const canvas = document.getElementById('mainCanvas');
        const ctx = canvas.getContext('2d');
        const phrases = ["Sanji 💖", "Bow Jan ❤️", "Valobashi 💕", "My Life 💍", "Jaan ✨", "Queen 👑"];
        let width, height, rainText = [], particles = [], hearts = [];

        function resize() { width = canvas.width = window.innerWidth; height = canvas.height = window.innerHeight; }
        window.addEventListener('resize', resize); resize();

        class Particle {
            constructor() { this.reset(); }
            reset() {
                this.x = Math.random() * width; this.y = Math.random() * height;
                this.size = Math.random() * 2 + 0.5; this.speedY = -Math.random() * 0.5;
                this.opacity = Math.random() * 0.5;
            }
            update() { this.y += this.speedY; if (this.y < 0) this.reset(); }
            draw() { ctx.fillStyle = `rgba(255, 77, 109, ${this.opacity})`; ctx.beginPath(); ctx.arc(this.x, this.y, this.size, 0, Math.PI*2); ctx.fill(); }
        }

        class RainText {
            constructor() { this.reset(); this.y = Math.random() * height; }
            reset() {
                this.x = Math.random() * width; this.y = -50;
                this.text = phrases[Math.floor(Math.random() * phrases.length)];
                this.speed = Math.random() * 0.8 + 0.4; this.opacity = 0;
            }
            update() {
                this.y += this.speed;
                if (this.y < height * 0.25) this.opacity += 0.01;
                if (this.y > height * 0.75) this.opacity -= 0.01;
                if (this.y > height) this.reset();
            }
            draw() {
                ctx.font = 'italic 13px serif';
                ctx.fillStyle = `rgba(255, 204, 213, ${this.opacity})`;
                ctx.fillText(this.text, this.x, this.y);
            }
        }

        function init() {
            for(let i=0; i<100; i++) particles.push(new Particle());
            for(let i=0; i<15; i++) rainText.push(new RainText());
            animate();
            runIntro();
        }

        function runIntro() {
            const delay = 1800;
            const seq = [document.getElementById('intro-1'), document.getElementById('intro-2'), document.getElementById('intro-3')];
            seq.forEach((el, i) => {
                setTimeout(() => el.style.opacity = 1, i * delay);
                setTimeout(() => el.style.opacity = 0, (i + 1) * delay - 400);
            });
            setTimeout(() => {
                document.getElementById('intro-overlay').style.opacity = 0;
                setTimeout(() => document.getElementById('intro-overlay').style.display = 'none', 2000);
                document.getElementById('main-ui').style.opacity = 1;
                document.getElementById('main-ui').style.transform = "scale(1)";
                document.getElementById('gift-btn').style.opacity = 1;
            }, seq.length * delay);
        }

        function animate() {
            ctx.fillStyle = '#050505'; ctx.fillRect(0, 0, width, height);
            particles.forEach(p => { p.update(); p.draw(); });
            rainText.forEach(t => { t.update(); t.draw(); });
            requestAnimationFrame(animate);
        }

        function openGift() {
            const overlay = document.getElementById('reveal-overlay');
            overlay.style.display = 'flex';
            setTimeout(() => {
                overlay.style.opacity = 1;
                document.getElementById('card').style.transform = "scale(1)";
                typeNote();
                if ('speechSynthesis' in window) {
                    let m = new SpeechSynthesisUtterance("Happy Birthday Sanjida, Amar Kolija, I love you so much");
                    m.rate = 0.8; window.speechSynthesis.speak(m);
                }
            }, 50);
        }

        function typeNote() {
            const text = "Tumi amar jiboner shera upohar... 💍";
            let i = 0; const el = document.getElementById('typing-text');
            el.innerHTML = "";
            const t = setInterval(() => {
                if(i < text.length) { el.innerHTML += text.charAt(i); i++; }
                else clearInterval(t);
            }, 70);
        }

        function closeGift() {
            document.getElementById('reveal-overlay').style.opacity = 0;
            setTimeout(() => {
                document.getElementById('reveal-overlay').style.display = 'none';
                document.getElementById('card').style.transform = "scale(0.2)";
            }, 500);
        }

        window.onload = init;
    </script>
</body>
</html>
