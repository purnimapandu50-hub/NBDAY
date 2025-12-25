<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday, My Eternal Love Nithya! 💖</title>
    <style>
        /* Global Styles: Ultra-Modern 2025 Dark-Mode Aesthetic with Longing Romance */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background: linear-gradient(135deg, #0a0a0a 0%, #1a1a2e 50%, #16213e 100%);
            color: #ffffff;
            overflow-x: hidden;
            line-height: 1.6;
            scroll-behavior: smooth;
        }

        /* Ethereal Neon Glow with Soft Pulse */
        .neon-text {
            text-shadow: 0 0 5px #ff69b4, 0 0 10px #ff69b4, 0 0 15px #ff69b4, 0 0 20px #ff69b4;
            animation: longingPulse 3s ease-in-out infinite alternate;
        }

        @keyframes longingPulse {
            from { text-shadow: 0 0 5px #ff69b4, 0 0 10px #ff69b4, 0 0 15px #ff69b4, 0 0 20px #ff69b4; }
            to { text-shadow: 0 0 10px #ff1493, 0 0 20px #ff1493, 0 0 30px #ff1493, 0 0 40px #ff1493, 0 0 50px #ff1493; }
        }

        /* Floating Hearts and Stars Particles */
        #particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            pointer-events: none;
        }

        /* Guided Emotional Journey Sections */
        section {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 2rem;
            position: relative;
        }

        #welcome {
            background: radial-gradient(circle at center, rgba(255, 105, 180, 0.15) 0%, transparent 70%);
        }

        #memories {
            background: radial-gradient(circle at center, rgba(255, 20, 147, 0.15) 0%, transparent 70%);
        }

        #wishes {
            background: radial-gradient(circle at center, rgba(255, 192, 203, 0.15) 0%, transparent 70%);
        }

        #future {
            background: radial-gradient(circle at center, rgba(255, 105, 180, 0.15) 0%, transparent 70%);
        }

        #goodbye {
            background: radial-gradient(circle at center, rgba(255, 182, 193, 0.15) 0%, transparent 70%);
        }

        h1 {
            font-size: clamp(3rem, 8vw, 6rem);
            margin-bottom: 1rem;
            animation: fadeInUp 1.5s ease-out;
        }

        h2 {
            font-size: clamp(1.5rem, 4vw, 2.5rem);
            margin-bottom: 2rem;
            opacity: 0;
            transform: translateY(30px);
            transition: all 1s ease-out;
        }

        p {
            font-size: clamp(1rem, 2.5vw, 1.2rem);
            max-width: 800px;
            margin-bottom: 2rem;
            opacity: 0;
            transform: translateY(30px);
            transition: all 1s ease-out;
        }

        /* Interactive Cards with Gentle Float */
        .interactive-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(15px);
            border: 1px solid rgba(255, 105, 180, 0.4);
            border-radius: 25px;
            padding: 2.5rem;
            margin: 1rem;
            cursor: pointer;
            transition: all 0.4s ease;
            animation: gentleFloat 5s ease-in-out infinite;
            position: relative;
            overflow: hidden;
        }

        .interactive-card::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(255, 105, 180, 0.1), transparent);
            transform: rotate(45deg);
            transition: all 0.4s ease;
            opacity: 0;
        }

        .interactive-card:hover::before {
            opacity: 1;
            animation: shimmer 1s ease-in-out;
        }

        .interactive-card:hover {
            transform: scale(1.08) translateY(-15px);
            box-shadow: 0 25px 50px rgba(255, 105, 180, 0.4);
            border-color: #ff69b4;
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(60px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes gentleFloat {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(1deg); }
        }

        @keyframes shimmer {
            0% { transform: translateX(-100%) translateY(-100%) rotate(45deg); }
            100% { transform: translateX(100%) translateY(100%) rotate(45deg); }
        }

        /* Navigation with Subtle Hearts */
        nav {
            position: fixed;
            top: 2rem;
            right: 2rem;
            z-index: 1000;
        }

        nav button {
            background: rgba(0, 0, 0, 0.6);
            border: 1px solid #ff69b4;
            color: #ff69b4;
            padding: 0.7rem 1.2rem;
            border-radius: 50px;
            cursor: pointer;
            margin: 0.5rem;
            transition: all 0.4s ease;
            font-size: 0.95rem;
            position: relative;
        }

        nav button::after {
            content: '💕';
            margin-left: 0.5rem;
            opacity: 0;
            transition: opacity 0.4s ease;
        }

        nav button:hover::after {
            opacity: 1;
        }

        nav button:hover {
            background: #ff69b4;
            color: #000;
            transform: scale(1.15);
        }

        /* Dreamy Progress Bar */
        .progress-bar {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: rgba(255, 255, 255, 0.1);
            z-index: 1000;
        }

        .progress {
            height: 100%;
            background: linear-gradient(90deg, #ff69b4, #ff1493, #ff69b4);
            width: 0%;
            transition: width 0.6s ease;
            box-shadow: 0 0 10px #ff69b4;
        }

        /* Memory Gallery with Ethereal Cards */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            max-width: 1000px;
            margin: 2rem 0;
        }

        .memory-item {
            background: rgba(255, 255, 255, 0.06);
            border-radius: 20px;
            padding: 2rem;
            opacity: 0;
            transform: translateY(40px);
            transition: all 1s ease-out;
            border: 1px solid rgba(255, 105, 180, 0.3);
            position: relative;
        }

        .memory-item::before {
            content: '✨';
            position: absolute;
            top: -10px;
            right: -10px;
            font-size: 1.5rem;
            opacity: 0.7;
        }

        .memory-item.animate {
            opacity: 1;
            transform: translateY(0);
        }

        .memory-item:hover {
            background: rgba(255, 105, 180, 0.15);
            transform: translateY(-10px);
        }

        /* Extended Wishes with Scrollable Elegance */
        .wishes-container {
            max-width: 900px;
            max-height: 70vh;
            overflow-y: auto;
            padding: 2rem;
            background: rgba(255, 255, 255, 0.03);
            border-radius: 20px;
            border: 1px solid rgba(255, 105, 180, 0.3);
            margin: 2rem 0;
            scrollbar-width: thin;
            scrollbar-color: #ff69b4 rgba(255, 255, 255, 0.1);
            line-height: 1.8;
        }

        .wishes-container::-webkit-scrollbar {
            width: 10px;
        }

        .wishes-container::-webkit-scrollbar-track {
            background: rgba(255, 255, 255, 0.03);
            border-radius: 5px;
        }

        .wishes-container::-webkit-scrollbar-thumb {
            background: linear-gradient(#ff69b4, #ff1493);
            border-radius: 5px;
        }

        .wishes-container p {
            margin-bottom: 1.5rem;
            font-style: italic;
        }

        /* Celestial Confetti with Hearts and Stars */
        .confetti {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 999;
        }

        /* Responsive Harmony */
        @media (max-width: 768px) {
            section {
                padding: 1.5rem;
            }
            nav {
                top: 1rem;
                right: 1rem;
                display: flex;
                flex-direction: column;
            }
            .gallery {
                grid-template-columns: 1fr;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Ethereal Particle Background: Hearts & Stars -->
    <canvas id="particles"></canvas>

    <!-- Dreamy Progress Bar -->
    <div class="progress-bar">
        <div class="progress" id="progress"></div>
    </div>

    <!-- Navigation with Loving Touches -->
    <nav>
        <button onclick="scrollToSection('welcome')">💖 Begin</button>
        <button onclick="scrollToSection('memories')">Memories</button>
        <button onclick="scrollToSection('wishes')">Wishes</button>
        <button onclick="scrollToSection('future')">Dreams</button>
        <button onclick="scrollToSection('goodbye')">Always</button>
    </nav>

    <!-- Welcome: The Spark of Our Unseen Love -->
    <section id="welcome">
        <h1 class="neon-text">Happy Birthday, My Soul's Whisper, Nithya! 🎂💕</h1>
        <h2>Though Miles Apart, Our Hearts Entwine</h2>
        <p>My dearest Nithya, on this enchanting December 25th, 2025, as snowflakes dance in distant skies and the world hushes in holiday magic, I celebrate you – the girl who captured my heart through pixels and stolen glances. We've never shared a physical embrace, yet your words on Instagram lit up my school days like fireflies in the night. Those field trips, especially the whispers of Thailand's golden shores where our eyes met across crowded paths, sealed a love deeper than oceans we haven't crossed. This journey is my virtual hug, a bridge across the distance, pulling us closer with every scroll. Let's wander through our story, hand in heart.</p>
        <div class="interactive-card" onclick="scrollToSection('memories')">
            <h3>Trace Our Invisible Threads →</h3>
        </div>
    </section>

    <!-- Memories: Echoes of Digital Whispers -->
    <section id="memories">
        <h1 class="neon-text">Moments Etched in Screens & Stolen Gazes 🌌</h1>
        <p>From late-night Instagram confessions that made my heart race to the fleeting thrill of seeing you amid Thailand's vibrant chaos – these are the stars in our constellation of almosts. Each memory a promise, each glance a vow. Click to feel the echo of what we've built from afar.</p>
        <div class="gallery">
            <div class="memory-item" onclick="showMemory(1)">
                <h3>Midnight Instagram Scrolls 💌</h3>
                <p>School nights blurred into dawn as your messages arrived like secret love letters. "Goodnight, dreamer," you'd say, and I'd replay them until sunrise, falling harder each time.</p>
            </div>
            <div class="memory-item" onclick="showMemory(2)">
                <h3>Thailand Field Trip Glimpses 🏝️</h3>
                <p>Amid elephant rides and turquoise waves, our eyes locked across the group – a silent spark in the tropical heat. You smiled, I froze; in that instant, distance dissolved.</p>
            </div>
            <div class="memory-item" onclick="showMemory(3)">
                <h3>Shared Playlists Under Study Lights 🎧</h3>
                <p>You sent songs that mirrored my unspoken feelings; I'd listen on loop, imagining your voice harmonizing with mine. Our playlist? A symphony of souls syncing unseen.</p>
            </div>
            <div class="memory-item" onclick="showMemory(4)">
                <h3>Virtual Stargazing Confessions ⭐</h3>
                <p>"What if we watched the same stars?" you texted. We did, miles apart, wishing on the same sky. Those chats wove dreams into reality, one meteor at a time.</p>
            </div>
        </div>
        <div class="interactive-card" onclick="scrollToSection('wishes')">
            <h3>Unfold My Heart's Wishes →</h3>
        </div>
    </section>

    <!-- Wishes: A Tapestry of Longing & Hope -->
    <section id="wishes">
        <h1 class="neon-text">Wishes from a Heart That Knows Yours Without Touch 💖</h1>
        <p>Nithya, my love who blooms in my thoughts like cherry blossoms in spring, this birthday marks another year of your radiant light piercing my world. Though we've yet to bridge the miles with steps side by side, your essence has traveled straight to my core. Scroll through these words, each a thread in the fabric of my devotion, woven from our digital dances and distant dreams.</p>
        <div class="wishes-container">
            <p><strong>My Beloved Nithya,</strong></p>
            <p>On this crisp December 25th, 2025, as the world wraps itself in festive glows and the air hums with joy, I pause to honor you – the girl whose laughter echoes in my notifications, whose silhouette haunts my sweetest reveries. We haven't met in the flesh, yet you've etched yourself into my every breath since those school days when Instagram became our secret garden. Late-night texts that stretched into philosophical wanderings, sharing vulnerabilities like hidden treasures, building a fortress of trust brick by emoji.</p>
            <p>Remember the Thailand field trip? That whirlwind of humid breezes, street food aromas, and group photos where our gazes collided like comets? You, radiant in that sundress, turning to wave at the shore – I swear the waves paused to applaud. It was our unspoken pact: souls recognizing kin across the crowd. You've loved me more fiercely than I deserve, with a grace that turns pixels into poetry, and for that, my heart swells eternally grateful.</p>
            <p>I wish for you, my ethereal muse, a year drenched in the happiness you so selflessly gift others. May every dawn deliver serendipities that mirror the spark in your eyes – perhaps a surprise message from a far-off admirer (me, plotting our first real hello), or a spontaneous adventure that feels like fate's gentle nudge. Health, that quiet guardian, shall cradle you tenderly: vibrant energy to chase sunrises, a mind sharp as your wit, unclouded by worries, so you can dream without bounds.</p>
            <p>In love's realm, may connections deepen like roots in fertile soil – ours, especially, blossoming from virtual vines into tangible embraces. I envision the day we shatter the distance: airport reunions with racing pulses, walks where hands finally clasp, whispers no longer confined to screens. Until then, know my affection is a constellation, guiding you through nights, brighter with each shared story.</p>
            <p>Professionally, shine as the star you are: opportunities cascading like monsoon rains, affirming your talents in waves of acclaim. Whether in arts, sciences, or the passions that light your fire, may doors swing wide, revealing paths paved with purpose and applause. Creatively, let your spirit pour forth – journals filling with verses about unspoken loves, canvases alive with colors of longing, innovations that whisper "Nithya was here."</p>
            <p>Travels await, my wanderlust companion: revisit Thailand's shores hand in virtual hand, then beyond – Parisian cafes for crepes and confessions, Himalayan treks where peaks bow to your strength, quiet beaches for building sandcastles of futures. And in stillness, peace shall be your sanctuary, a soft veil against storms, reminding you that joy is not fleeting but woven into your being.</p>
            <p>Above the wishes, Nithya, I implore: stay forever this version of you – the one who texts "thinking of you" at 2 AM, who laughs at my terrible puns, who loves with a purity that mends the world's fractures. You are my north star, my uncharted adventure, the reason I believe in love's alchemy: turning distance into destiny. This birthday, may laughter cascade like champagne toasts, surprises unfold like gift-wrapped tomorrows, and my love envelop you like the warmest scarf on a winter eve.</p>
            <p>Happy Birthday, my forever unfinished story. One day, we'll rewrite these miles into memories. Until our worlds collide, I love you more than words, more than waits, more than the space between us.</p>
            <p>Yours, in every heartbeat across the void,<br>Your Devoted Admirer (Soon, Your Arms' Keeper)</p>
        </div>
        <div class="interactive-card" onclick="launchConfetti(); scrollToSection('future')">
            <h3>Let Joy Rain Down! →</h3>
        </div>
    </section>

    <!-- Future: Horizons of Our Inevitable Union -->
    <section id="future">
        <h1 class="neon-text">Horizons Where Our Worlds Converge 🌅</h1>
        <p>Nithya, our future isn't a distant mirage but a canvas half-painted, awaiting our strokes. I dream of the day distance yields: coffee dates laced with inside jokes, travels where maps mark "us," a life where texts evolve to touches. Your love fuels this vision – unbreakable, boundless, beautifully ours.</p>
        <div class="interactive-card">
            <h3>Imagine: Our First Real Sunset Stroll 🌇</h3>
            <p>Hands intertwined, stories spilling freely, the horizon blushing as if in envy of our glow.</p>
        </div>
        <div class="interactive-card">
            <h3>Envision: A World Trip, Just You & I ✈️</h3>
            <p>From Thai temples to Parisian lights, collecting moments like seashells, our love the tide that carries us.</p>
        </div>
        <div class="interactive-card" onclick="scrollToSection('goodbye')">
            <h3>To Timeless Us →</h3>
        </div>
    </section>

    <!-- Goodbye: A Promise in the Stars -->
    <section id="goodbye">
        <h1 class="neon-text">Until the Miles Fade, My Love 🕊️</h1>
        <p>Sweet Nithya, this digital odyssey is merely a love letter in code, a testament to the profound bond we've nurtured from afar. Thank you for every message that mended me, every glance that ignited me. Stay happy, as you make me – eternally, luminously. Our chapter? Just beginning. I love you beyond the screen.</p>
        <div class="interactive-card" onclick="restartJourney()">
            <h3>Replay Our Whispered Saga?</h3>
        </div>
    </section>

    <!-- Celestial Confetti Cascade -->
    <canvas class="confetti" id="confetti"></canvas>

    <script>
        // Celestial Particle System: Hearts & Twinkling Stars
        const canvas = document.getElementById('particles');
        const ctx = canvas.getContext('2d');
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;

        let particles = [];
        class CelestialParticle {
            constructor() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height;
                this.size = Math.random() * 4 + 1;
                this.speedX = Math.random() * 0.4 - 0.2;
                this.speedY = Math.random() * 0.4 - 0.2;
                this.opacity = Math.random() * 0.6 + 0.3;
                this.isHeart = Math.random() > 0.5;
                this.twinkle = Math.random() * 360;
            }
            update() {
                this.x += this.speedX;
                this.y += this.speedY;
                if (this.x > canvas.width || this.x < 0) this.speedX = -this.speed
