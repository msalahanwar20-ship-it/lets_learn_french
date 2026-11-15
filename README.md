# lets_learn_french
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>L'Atelier de Français | Master French Grammar & Vocab</title>
    <style>
        :root {
            --primary: #2c3e50;
            --accent: #3498db;
            --bg: #f8f9fa;
            --card-bg: #ffffff;
            --text: #333333;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, var(--primary), var(--accent));
            color: white;
            padding: 2.5rem 1rem;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }
        nav {
            background: #1a252f;
            color: white;
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            padding: 0.8rem;
            flex-wrap: wrap;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            cursor: pointer;
            transition: color 0.3s;
        }
        nav a:hover {
            color: var(--accent);
        }
        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }
        .section {
            display: none;
            background: var(--card-bg);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            margin-bottom: 2rem;
        }
        .section.active {
            display: block;
        }
        h2 {
            color: var(--primary);
            border-bottom: 2px solid var(--accent);
            padding-bottom: 0.5rem;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 1rem 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: var(--primary);
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-top: 1rem;
        }
        .card {
            background: #fff;
            border: 1px solid #e1e8ed;
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.02);
        }
        .card h3 {
            margin-top: 0;
            color: var(--accent);
        }
        footer {
            text-align: center;
            padding: 2rem;
            background: var(--primary);
            color: white;
            margin-top: 3rem;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>L'Atelier de Français</h1>
        <p>Your Ultimate Hub for French Grammar, Vocabularies, and Study Guides</p>
    </header>

    <nav>
        <a onclick="showSection('home')">Home</a>
        <a onclick="showSection('grammar')">Grammar Rules</a>
        <a onclick="showSection('vocab')">Vocabulary</a>
        <a onclick="showSection('study')">Study Ways</a>
    </nav>

    <div class="container">
        <!-- HOME SECTION -->
        <div id="home" class="section active">
            <h2>Welcome to Your French Mastery Platform!</h2>
            <p>Bienvenue! This platform is carefully structured to guide you from beginner concepts to advanced fluency. Navigate through the tabs above to access complete grammar rulebooks, essential daily vocabularies, and proven study methodologies.</p>
            <div class="card-grid">
                <div class="card">
                    <h3>📚 Comprehensive Grammar</h3>
                    <p>Master verb conjugations, tense structures, pronouns, and agreement rules with clear tables.</p>
                </div>
                <div class="card">
                    <h3>🗣️ Essential Vocabularies</h3>
                    <p>Expand your lexicon with high-frequency thematic words and expressions.</p>
                </div>
                <div class="card">
                    <h3>💡 Proven Study Methods</h3>
                    <p>Discover actionable techniques to accelerate your retention and exam preparation.</p>
                </div>
            </div>
        </div>

        <!-- GRAMMAR SECTION -->
        <div id="grammar" class="section">
            <h2>Core French Grammar Rules</h2>
            <p>Here are the fundamental building blocks of French grammar:</p>
            
            <h3>1. Present Tense - Regular "-ER" Verbs (e.g., <em>Parler</em> - To speak)</h3>
            <table>
                <tr><th>Pronoun</th><th>Ending</th><th>Example (Parler)</th></tr>
                <tr><td>Je</td><td>-e</td><td>Je parle</td></tr>
                <tr><td>Tu</td><td>-es</td><td>Tu parles</td></tr>
                <tr><td>Il / Elle / On</td><td>-e</td><td>Il parle</td></tr>
                <tr><td>Nous</td><td>-ons</td><td>Nous parlons</td></tr>
                <tr><td>Vous</td><td>-ez</td><td>Vous parlez</td></tr>
                <tr><td>Ils / Elles</td><td>-ent</td><td>Ils parlent</td></tr>
            </table>

            <h3>2. Essential Auxiliary Verbs: Être (To be) & Avoir (To have)</h3>
            <table>
                <tr><th>Pronoun</th><th>Être (To be)</th><th>Avoir (To have)</th></tr>
                <tr><td>Je</td><td>suis</td><td>ai</td></tr>
                <tr><td>Tu</td><td>es</td><td>as</td></tr>
                <tr><td>Il / Elle</td><td>est</td><td>a</td></tr>
                <tr><td>Nous</td><td>sommes</td><td>avons</td></tr>
                <tr><td>Vous</td><td>êtes</td><td>avez</td></tr>
                <tr><td>Ils / Elles</td><td>sont</td><td>ont</td></tr>
            </table>
        </div>

        <!-- VOCABULARY SECTION -->
        <div id="vocab" class="section">
            <h2>Essential French Vocabularies</h2>
            <p>High-frequency words categorized by everyday themes:</p>
            
            <h3>Common Expressions & Greetings</h3>
            <table>
                <tr><th>French</th><th>English Translation</th></tr>
                <tr><td>Bonjour</td><td>Hello / Good morning</td></tr>
                <tr><td>S'il vous plaît</td><td>Please (formal)</td></tr>
                <tr><td>Merci beaucoup</td><td>Thank you very much</td></tr>
                <tr><td>À bientôt</td><td>See you soon</td></tr>
                <tr><td>Je ne comprends pas</td><td>I don't understand</td></tr>
            </table>
        </div>

        <!-- STUDY WAYS SECTION -->
        <div id="study" class="section">
            <h2>Effective Ways to Study French</h2>
            <div class="card-grid">
                <div class="card">
                    <h3>1. Active Recall & Flashcards</h3>
                    <p>Don't just passively read rules. Test yourself daily on verb conjugations and new vocabulary using digital flashcards or written notes.</p>
                </div>
                <div class="card">
                    <h3>2. Immersive Listening</h3>
                    <p>Tune your ear to French audio, podcasts, and dialogues to master natural pacing, liaison, and pronunciation nuances.</p>
                </div>
                <div class="card">
                    <h3>3. Contextual Writing</h3>
                    <p>Write short paragraphs or daily journal entries in French applying the exact grammar rules you learn each week.</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Shahd Mohamed Salah. All Rights Reserved. Created exclusively for L'Atelier de Français.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('.section');
            sections.forEach(sec => sec.classList.remove('active'));
            document.getElementById(sectionId).classList.add('active');
        }
    </script>
</body>
</html>
