<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>My Unhealthy Obsession</title>

    <style>
      body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #eeeeee;
        color: #222;
      }

      /* Top Navigation */
      .top-nav {
        background-color: #041e42;
        padding: 15px 25px;
        text-align: left;
      }

      .back-button {
        display: inline-block;
        background-color: #0064b1;
        color: white;
        padding: 12px 22px;
        font-size: 16px;
        font-weight: bold;
        text-decoration: none;
        border-radius: 8px;
        transition: 0.3s;
      }

      .back-button:hover {
        background-color: white;
        color: #041e42;
        transform: scale(1.05);
      }

      /* Header */
      header {
        background: linear-gradient(135deg, #041e42, #0064b1);
        color: white;
        text-align: center;
        padding: 70px 20px;
        border-bottom: 8px solid #b0b7bc;
      }

      header h1 {
        font-size: 55px;
        margin: 0;
        text-transform: uppercase;
        letter-spacing: 2px;
      }

      header p {
        font-size: 22px;
        margin-top: 15px;
      }

      /* Main Container */
      .container {
        width: 85%;
        max-width: 1000px;
        margin: 40px auto;
      }

      /* Introduction */
      .intro {
        background-color: white;
        padding: 30px;
        border-radius: 15px;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        margin-bottom: 35px;
        text-align: center;
      }

      .intro h2 {
        color: #0064b1;
        font-size: 32px;
      }

      .intro p {
        font-size: 19px;
        line-height: 1.7;
      }

      /* Images */
      .image-container {
        margin: 30px 0;
        text-align: center;
      }

      .image-container img {
        width: 100%;
        max-width: 900px;
        border-radius: 15px;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.25);
      }

      .caption {
        font-size: 14px;
        color: #555;
        margin-top: 8px;
      }

      /* Sections */
      .card {
        background-color: white;
        padding: 30px;
        margin-bottom: 30px;
        border-radius: 15px;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
        border-left: 7px solid #0064b1;
      }

      .card h2 {
        color: #041e42;
        font-size: 30px;
      }

      .card p {
        font-size: 18px;
        line-height: 1.7;
      }

      .highlight {
        font-weight: bold;
        color: #0064b1;
      }

      /* Cowboys Facts */
      .facts {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
        margin-top: 25px;
      }

      .fact {
        background-color: #041e42;
        color: white;
        padding: 25px;
        border-radius: 12px;
        text-align: center;
      }

      .fact h3 {
        font-size: 24px;
        margin-top: 0;
      }

      .fact p {
        font-size: 16px;
      }

      /* Next Page Button */
      .next-page {
        text-align: center;
        margin: 50px 0;
      }

      .next-page button {
        background-color: #0064b1;
        color: white;
        border: none;
        padding: 16px 40px;
        font-size: 20px;
        font-weight: bold;
        border-radius: 10px;
        cursor: pointer;
        transition: 0.3s;
      }

      .next-page button:hover {
        background-color: #041e42;
        transform: scale(1.05);
      }

      /* Footer */
      footer {
        background-color: #041e42;
        color: white;
        text-align: center;
        padding: 25px;
        margin-top: 50px;
      }

      /* Mobile */
      @media (max-width: 700px) {
        header h1 {
          font-size: 38px;
        }

        .facts {
          grid-template-columns: 1fr;
        }

        .container {
          width: 90%;
        }
      }
    </style>
  </head>

  <body>
    <!-- Back to First Page Button -->
    <div class="top-nav">
      <a href="index.html" class="back-button"> ← Back to My Page </a>
    </div>

    <!-- Header -->
    <header>
      <h1>My Unhealthy Obsession</h1>
      <p>The Dallas Cowboys</p>
    </header>

    <!-- Main Content -->
    <div class="container">
      <!-- Introduction -->
      <div class="intro">
        <h2>Why Am I Obsessed With The Cowboys?</h2>

        <p>
          If you know me personally, you know I don't mess around the Cowboys. I
          am deeply envolved with Cowboys news 24/7 and when we lose I don't
          take it lightly
        </p>
      </div>

      <!-- Image 1 -->
      <div class="image-container">
        <img
          src="https://www.omnihotels.com/-/media/images/partnerships/dallas-cowboys.jpg?h=660&iar=0&w=1170"
          alt="Dallas Cowboys players"
        />

        <p class="caption">Dallas Cowboys players preparing for a game.</p>
      </div>

      <!-- Why I Like Them -->
      <div class="card">
        <h2>Why I Love The Cowboys</h2>

        <p>
          I have always liked the Cowboys because they are one of the most
          recognizable teams in football. The star logo, the uniforms, the
          stadium, and the history of the team all make them stand out.
        </p>

        <p>
          What really makes me a fan is being able to watch the games with my
          parents . Even when the Cowboys lose, I still find myself watching the
          next game even when I want to stop being a fan.
        </p>
      </div>

      <!-- Image 2 -->
      <div class="image-container"></div>

      <!-- Football Season -->
      <div class="card">
        <h2>September Through February</h2>

        <p>
          September through February basically means one thing to me:
          <span class="highlight">NFL football.</span>
        </p>

        <p>
          During football season, I always check the Cowboys schedule, hoping we
          play one team, the Packers. I despise them ever since the playoff game
          where Dez caught it.
        </p>

        <p>
          And yes, I already know what you're thinking...
          <strong>Cowboys 2027 Super Bowl Champs.</strong>
        </p>
      </div>

      <div class="fact">
        <h3>🏟️</h3>
        <h3>AT&T Stadium</h3>
        <p>AT&T Stadium is the home of the Dallas Cowboys.</p>
      </div>
    </div>

    <!-- Image 3 -->
    <div class="image-container">
      <img
        src="https://www.tudn.com/api/image/og/us/nfl/dallas-cowboys-la-franquicia-mas-valiosa-de-la-nfl"
        alt="Dallas Cowboys at AT&T Stadium"
      />

      <!-- Next Page -->
      <div class="next-page">
        <button onclick="goToNextPage()">Next Page →</button>
      </div>
    </div>

    <!-- Footer -->
    <footer>
      <p>My Unhealthy Obsession — Dallas Cowboys</p>
    </footer>

    <script>
      function goToNextPage() {
        document.body.innerHTML = "";
        document.body.style.backgroundColor = "white";
        document.title = "Next Page";
      }
    </script>
  </body>
</html>
