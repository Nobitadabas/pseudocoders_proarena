# pseudocoders_proarena
#ProArena is your ultimate esports platform, designed to bring the competitive gaming community together.Dive into eSPL (Esports Premier League), our #exclusive franchise-style league, complete with live match stats, multi-cam viewing, and smart AI commentary — just like professional sports.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ProArena - Your Next GG Starts Here</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0f0f0f;
      color: white;
      scroll-behavior: smooth;
    }
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #1a1a1a;
      padding: 0.8rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 999;
    }
    .logo {
      color: #8a2be2;
      font-size: 1.8rem;
      font-weight: bold;
    }
    .nav-links {
      list-style: none;
      display: flex;
      gap: 1rem;
    }
    .nav-links a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: 0.3s;
    }
    .nav-links a:hover,
    .nav-links a.active {
      color: #8a2be2;
    }
    section {
      padding: 4rem 1.5rem;
      max-width: 1000px;
      margin: auto;
    }

    .hero {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: url('./assets/background.jpg') center/cover no-repeat;
      position: relative;
    }

    .hero-overlay {
      background-color: rgba(0,0,0,0.75);
      padding: 4rem 2rem;
      border-radius: 10px;
    }

    .hero h1 {
      font-size: 5rem;
      color: #8a2be2;
      margin-bottom: 1.5rem;
      text-shadow: 2px 2px #000;
    }

    .btn {
      display: inline-block;
      margin: 0.5rem;
      padding: 1rem 2rem;
      background-color: #8a2be2;
      color: white;
      border: none;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: background 0.3s;
    }
    .btn:hover {
      background-color: #6f22c0;
    }

    .btn.secondary {
      background-color: transparent;
      border: 2px solid #8a2be2;
    }

    .feature-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: #1a1a1a;
      padding: 1.5rem;
      border-radius: 10px;
      border: 1px solid #333;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 15px #8a2be2aa;
    }

    footer {
      background-color: #1a1a1a;
      text-align: center;
      padding: 2rem;
      color: #aaa;
      margin-top: 2rem;
    }

    h2 {
      color: #8a2be2;
      margin-bottom: 1rem;
      text-align: center;
    }

    p {
      text-align: center;
      line-height: 1.6;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1rem;
      animation: fadeIn 1.2s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    th, td {
      padding: 0.75rem;
      border-bottom: 1px solid #444;
    }

    thead {
      background-color: #1a1a1a;
      color: #8a2be2;
    }

    tr:nth-child(even) {
      background-color: #161616;
    }

    tr:hover {
      background-color: #222;
    }

    /* Smooth section animation */
    section {
      animation: fadeIn 1.2s ease-in-out;
    }
  </style>
</head>
<body>

    <div class="signup-container">
      <h2>Create Your ProArena Account</h2>
      <form onsubmit="event.preventDefault(); alert('Signed up successfully!');">
        <input type="text" placeholder="Gamer Tag" required />
        <input type="email" placeholder="Email" required />
        <input type="password" placeholder="Password" required />
        <button type="submit" class="btn">Sign Up</button>
      </form>
      <a href="index.html">← Back to Home</a>
    </div>
  
  </body>
<body>

  <nav>
    <div class="logo">ProArena</div>
    <ul class="nav-links">
      <li><a href="#home" class="active">Home</a></li>
      <li><a href="signup.html" class="btn">Sign Up</a></li>
      <li><a href="#events">Events</a></li>
      <li><a href="#matchmaking">Matchmaking</a></li>
      <li><a href="#streaming">Streaming</a></li>
      <li><a href="#espl">eSPL</a></li>
      <li><a href="#leaderboard">Leaderboard</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="home" class="hero">
    <div class="hero-overlay">
      <h1>PROARENA</h1>
      <a href="#profiles" class="btn">Sign Up</a>
    </div>
  </section>

  <section id="espl">
    <h2>🏆 eSPL – The Esports Premier League</h2>
    <div class="feature-grid">
      <div class="card">
        <h3>League Format</h3>
        <p>Compete in franchise-style teams. Climb the table, every match counts!</p>
      </div>
      <div class="card">
        <h3>Live Match Stats</h3>
        <p>Round-by-round stats, MVPs, K/Ds, win probability — updated live.</p>
      </div>
      <div class="card">
        <h3>Multi-Cam View</h3>
        <p>Switch between player POVs. Choose your view, just like real sports.</p>
      </div>
      <div class="card">
        <h3>Smart Commentary</h3>
        <p>AI or live commentary explains gameplay — even beginners understand.</p>
      </div>
    </div>
  </section>

  <section id="leaderboard">
    <h2>📊 Leaderboards & Trophy Room</h2>
    <p>Track global and regional rankings. Show off your trophies and climb the ProArena ladder!</p>

    <div style="overflow-x: auto; margin-top: 2rem;">
      <table>
        <thead>
          <tr>
            <th>Rank</th>
            <th>Gamer Tag</th>
            <th>Game</th>
            <th>K/D Ratio</th>
            <th>Wins</th>
            <th>Region</th>
          </tr>
        </thead>
        <tbody id="leaderboard-body">
          <!-- Dynamic content via JS -->
        </tbody>
      </table>
    </div>
  </section>

  

  <footer>
    <h2>📬 Contact Us</h2>
    <p>Built by <strong>PseudoCoders</strong></p>
  </footer>

  <script>
    // Highlight active link
    const sections = document.querySelectorAll("section");
    const navLinks = document.querySelectorAll(".nav-links a");

    window.onscroll = () => {
      let current = "";
      sections.forEach((sec) => {
        const top = window.scrollY;
        const offset = sec.offsetTop - 150;
        const height = sec.offsetHeight;
        if (top >= offset && top < offset + height) {
          current = sec.getAttribute("id");
        }
      });

      navLinks.forEach((a) => {
        a.classList.remove("active");
        if (a.getAttribute("href").includes(current)) {
          a.classList.add("active");
        }
      });
    };

    // Dynamically fill leaderboard
    const leaderboardData = [
      ["1", "ShadowAce", "Valorant", "3.5", "420", "NA"],
      ["2", "PixelGhost", "CS:GO", "3.2", "398", "EU"],
      ["3", "NoobHunter", "PUBG", "2.9", "375", "ASIA"],
      ["4", "SnipeQueen", "COD", "3.1", "362", "EU"],
      ["5", "QuickScope", "Valorant", "2.7", "340", "NA"]
    ];

    const tbody = document.getElementById("leaderboard-body");
    leaderboardData.forEach(row => {
      const tr = document.createElement("tr");
      row.forEach(cell => {
        const td = document.createElement("td");
        td.textContent = cell;
        tr.appendChild(td);
      });
      tbody.appendChild(tr);
    });
  </script>
</body>
</html>
