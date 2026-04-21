# Love-letter-
I want to make a website for my love 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>for my dearest jesicha my love</title>
  <style>
    body {
      margin: 0;
      font-family: "Georgia", serif;
      background: linear-gradient(135deg, #ffdde1, #ee9ca7);
      color: #4b2c20;
      display: flex;
      min-height: 100vh;
      align-items: center;
      justify-content: center;
      text-align: center;
      flex-direction: column;
      padding: 2rem;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 0.5em;
      animation: fadeIn 2s ease-in;
    }
    p {
      max-width: 600px;
      line-height: 1.6;
      font-size: 1.2em;
      animation: fadeIn 3s ease-in;
    }
    .signature {
      margin-top: 2em;
      font-style: italic;
      font-size: 1.3em;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .heart {
      font-size: 2em;
      color: #e63946;
      animation: beat 1.5s infinite;
    }
    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    /* hide video */
    .music {
      position: absolute;
      width: 0;
      height: 0;
      overflow: hidden;
    }
  </style>
</head>
<body>

  <!-- Background Music -->
  <div class="music">
    <iframe 
      src="https://www.youtube.com/embed/6uYb6tq0f5s?autoplay=1&loop=1&playlist=6uYb6tq0f5s"
      frameborder="0"
      allow="autoplay">
    </iframe>
  </div>

  <h1>for my dearest jesicha my love 💖</h1>

  <p>
    My Dearest, They say that distance makes the heart grow fonder, but honestly, it just makes me realize how much of my world is built around you. Even though there are hundreds of miles between us, I find traces of you in everything—in the songs I listen to, the quiet moments of my morning, and every wish I make. It’s not easy waking up without you by my side, but the thought of your smile is enough to get me through the toughest days. You aren’t just someone I’m dating; you are my home, and no amount of distance can ever change the way my heart beats only for you. I want you to know that every "goodnight" we say over the phone is just a countdown to the day I never have to let you go again. I’m constantly dreaming of the moment I can finally stop looking at you through a screen and actually hold you in my arms. Until that day comes, please remember that you are worth every second of the wait and every mile of the journey. You are my greatest adventure and my favorite person, and I’ll keep choosing you every single day, no matter how far apart we are. I love you more than words can ever describe
  </p>

  <div class="signature">Forever yours,<br> Jeremiah</div>
  <div class="heart">❤️</div>

</body>
</html>
