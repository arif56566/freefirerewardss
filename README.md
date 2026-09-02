<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Garena Free Fire Team</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Arial, sans-serif; }
    body { 
      min-height: 100vh; 
      background-color: #121212; 
      display: flex; flex-direction: column; align-items: center; 
      color: #ffffff; padding-bottom: 30px;
    }
    .top-header {
      width: 100%;
      background: #7ec8e3;
      color: #000;
      font-size: 22px;
      font-weight: 800;
      text-align: center;
      padding: 14px 10px;
      margin-bottom: 20px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.3);
    }
    .main-container {
      width: 100%; max-width: 420px;
      padding: 0 12px;
      display: flex; flex-direction: column; gap: 20px;
    }
    .video-box {
      width: 100%;
      background: #000;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.6);
      border: 1px solid #333;
    }
    .video-box video {
      width: 100%;
      display: block;
      aspect-ratio: 16/9;
      object-fit: cover;
    }
    .panel-card {
      position: relative;
      background: #18181b;
      border-radius: 18px;
      padding: 22px 18px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.5);
    }
    .panel-card::before {
      content: '';
      position: absolute; inset: -2px; border-radius: 20px;
      background: linear-gradient(45deg, #ff0000, #ff7300, #ffeb00, #15ff00, #00ffd5, #002bff, #7a00ff, #ff00c8, #ff0000);
      z-index: -1;
      animation: rainbowBorder 6s linear infinite;
    }
    @keyframes rainbowBorder {
      0% { filter: hue-rotate(0deg); }
      100% { filter: hue-rotate(360deg); }
    }
    .panel-content-row {
      display: flex; align-items: flex-start; gap: 15px; margin-bottom: 18px;
    }
    .panel-logo {
      width: 55px; height: 55px; min-width: 55px; border-radius: 50%;
      background: #000; border: 2px solid #6b46c1;
      display: flex; align-items: center; justify-content: center;
      overflow: hidden; box-shadow: 0 0 10px rgba(107, 70, 193, 0.5);
    }
    .panel-logo img { width: 100%; height: 100%; object-fit: cover; }
    .panel-text-group { display: flex; flex-direction: column; gap: 8px; flex: 1; }
    .panel-titles h2 { font-size: 20px; font-weight: 900; color: #fff; text-transform: uppercase; }
    .panel-desc { font-size: 13px; color: #e0e0e0; font-weight: 600; }
    .stars { color: #ffc107; font-size: 19px; letter-spacing: 3px; }
    .install-btn {
      width: 100%; background: #2ecc71; color: #000;
      border: none; border-radius: 14px; padding: 16px;
      font-size: 20px; font-weight: 900; text-transform: uppercase;
      cursor: pointer; text-align: center; text-decoration: none; display: block;
    }
    .install-btn:hover { background: #27ae60; }
  </style>
</head>
<body>

  <div class="top-header">Garena Free Fire Team</div>

  <div class="main-container">
    
    <!-- Video Player with New Link -->
    <div class="video-box">
      <video controls playsinline>
        <source src="https://www.image2url.com/r2/default/videos/1788114071885-e4c256c7-a5e8-45f5-9017-bf86970f953e.mp4" type="video/mp4">
        Your browser does not support video.
      </video>
    </div>

    <!-- Claim Panel -->
    <div class="panel-card">
      <div class="panel-content-row">
        <div class="panel-logo">
          <img src="https://i.ibb.co/bjxQ86sB/IMG-20260817-213021.jpg" alt="Logo">
        </div>
        <div class="panel-text-group">
          <div class="panel-titles">
            <h2>FREE DIAMONDS CLAIM</h2>
          </div>
          <div class="panel-desc">FREE 10000 DIAMONDS CLAIM 💎🥳</div>
          <div class="stars">★★★★★</div>
        </div>
      </div>

      <a href="https://1024terabox.com/s/1BLOfvrFNZu_fSgZ-kze8hg" class="install-btn" target="_blank">CLAIM NOW</a>
    </div>

  </div>

</body>
</html>
