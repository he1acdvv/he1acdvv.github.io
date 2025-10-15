<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>mrjajkes</title>
  <style>
    body {
      margin: 0;
      font-family: 'Courier New', monospace;
      background-color: #0b0b0b;
      background-image: radial-gradient(#1a1a1a 1px, transparent 1px);
      background-size: 4px 4px;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      color: #2b2b1a;
    }

    .card {
      background-color: #8b935a;
      border: 1px solid #3f4222;
      box-shadow: 0 0 8px #000;
      width: 380px;
      padding: 20px;
      text-align: left;
      color: #2a2a16;
    }

    .header {
      display: flex;
      align-items: flex-start;
      gap: 16px;
      margin-bottom: 10px;
    }

    .avatar {
      width: 70px;
      height: 70px;
      background-color: #5e6237;
      background-image: url("placeholder-avatar.png");
      background-size: cover;
      background-position: center;
      border: 1px solid #3f4222;
    }

    .name {
      font-weight: bold;
      font-style: italic;
      font-size: 1.3em;
      color: #303414;
      margin-bottom: 4px;
    }

    .divider {
      border-top: 1px dashed #3f4222;
      margin: 6px 0;
    }

    .content {
      font-size: 0.95em;
      line-height: 1.5;
    }

    .content p {
      margin: 4px 0;
    }

    .links {
      display: flex;
      justify-content: space-between;
      margin-top: 20px;
    }

    .icon {
      width: 60px;
      height: 60px;
      background-color: #3f4222;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      color: #b8bc85;
      text-decoration: none;
      transition: 0.2s;
    }

    .icon:hover {
      background-color: #5a5e34;
    }

    .icon img {
      width: 26px;
      height: 26px;
      filter: invert(80%);
      margin-bottom: 5px;
    }

    .footer {
      margin-top: 10px;
      font-size: 0.75em;
      text-align: center;
      color: #505535;
    }

    .footer a {
      color: inherit;
      text-decoration: none;
    }

    .more {
      font-size: 0.75em;
      color: #737b48;
      text-align: right;
      margin-top: 8px;
    }

    .more:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="header">
      <div class="avatar"></div>
      <div>
        <div class="name">mrjajkes</div>
        <div class="divider"></div>
        <div class="content">
          <p>> i create art.</p>
          <p>> i create music.</p>
          <p>> i experiment.</p>
        </div>
      </div>
    </div>

    <div class="more">. . . more in person</div>

    <div class="links">
      <a href="#" class="icon">
        <img src="youtube-icon.png" alt="YouTube">
        <span>> youtube</span>
      </a>
      <a href="#" class="icon">
        <img src="spotify-icon.png" alt="Spotify">
        <span>> spotify</span>
      </a>
      <a href="#" class="icon">
        <img src="bluesky-icon.png" alt="Bluesky">
        <span>> bluesky</span>
      </a>
      <a href="#" class="icon">
        <img src="kofi-icon.png" alt="Ko-fi">
        <span>> kofi</span>
      </a>
    </div>

    <div class="footer">( Made with Carrd )</div>
  </div>
</body>
</html>
