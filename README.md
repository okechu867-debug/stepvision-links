<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>StepVisionStore.ng | Walk Your Vision in Style</title>

  <style>
    /* ===== Global Reset ===== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: linear-gradient(180deg, #000000, #1a1a1a, #000000);
      color: #ffffff;
      font-family: 'Poppins', sans-serif;
      text-align: center;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 40px 20px;
    }

    /* ===== Logo Section ===== */
    .logo {
      margin-bottom: 20px;
    }

    .logo img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 3px solid gold;
      box-shadow: 0 0 20px gold;
      animation: goldGlow 2.5s infinite alternate;
    }

    @keyframes goldGlow {
      from { box-shadow: 0 0 10px gold; }
      to { box-shadow: 0 0 25px gold; }
    }

    /* ===== Brand Identity ===== */
    h1 {
      font-size: 28px;
      color: gold;
      margin-bottom: 8px;
    }

    p.tagline {
      font-size: 15px;
      color: #bbb;
      margin-bottom: 40px;
      letter-spacing: 0.5px;
    }

    /* ===== Link Buttons ===== */
    .links a {
      display: block;
      background: gold;
      color: #000;
      text-decoration: none;
      padding: 14px 18px;
      margin: 10px auto;
      width: 80%;
      max-width: 320px;
      border-radius: 30px;
      font-weight: 600;
      letter-spacing: 0.5px;
      transition: all 0.3s ease;
      box-shadow: 0 0 8px rgba(255, 215, 0, 0.4);
    }

    .links a:hover {
      background: #fff;
      color: #000;
      transform: scale(1.05);
      box-shadow: 0 0 15px gold;
    }

    /* ===== Footer ===== */
    footer {
      margin-top: 50px;
      font-size: 13px;
      color: #888;
    }
  </style>
</head>

<body>
  <!-- ===== Logo ===== -->
  <div class="logo">
    <img src="logo.png" alt="StepVisionStore.ng Logo" />
  </div>

  <!-- ===== Brand Name & Tagline ===== -->
  <h1>StepVisionStore.ng</h1>
  <p class="tagline">Walk Your Vision in Style</p>

  <!-- ===== Social & Contact Links ===== -->
  <div class="links">
    <a href="https://wa.me/message/2348155471066" target="_blank">💬 Chat on WhatsApp Business</a>
    <a href="https://www.tiktok.com/@stepvisionstore?_t=ZS-90zkgrIIrmm&_r=1" target="_blank">🎵 Follow on TikTok</a>
    <a href="https://www.instagram.com/shopstepvision.ng?igsh=MXAyZTljZDlpZjdpMA==" target="_blank">📸 Follow on Instagram</a>
    <a href="https://www.stepvisionstore.ng" target="_blank">🌐 Visit Our Website</a>
  </div>

  <!-- ===== Footer ===== -->
  <footer>
    © 2025 StepVisionStore.ng — Walk Your Vision in Style
  </footer>
</body>
</html>
