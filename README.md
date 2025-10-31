<! html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title></title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; }

    body {
      font-family: 'Cairo', sans-serif;
      background: linear-gradient(120deg, #6a11cb 0%, #2575fc 100%);
      margin: 0;
      padding: 0;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      margin-top: 40px;
      animation: fadeIn 1.5s ease;
    }

    .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid rgba(255,255,255,0.8);
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
      margin-bottom: 20px;
      transition: transform 0.4s ease;
    }
    .profile-img:hover {
      transform: scale(1.05);
    }

    header h1 {
      font-size: 2.2em;
      margin: 10px 0;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.3);
    }

    header p {
      font-size: 1.1em;
      color: #f1f1f1;
      opacity: 0.9;
      margin-bottom: 10px;
    }

    .social-links {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-top: 10px;
    }

    .social-links a {
      background: rgba(255, 255, 255, 0.15);
      border-radius: 50%;
      width: 45px;
      height: 45px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      transition: 0.3s ease;
    }

    .social-links a:hover {
      background: rgba(255,255,255,0.3);
      transform: translateY(-4px);
    }

    .social-links img {
      width: 24px;
      height: 24px;
      filter: invert(1);
    }

    .projects {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
      margin: 50px 0;
      animation: fadeUp 2s ease;
    }

    .project {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      padding: 25px;
      width: 280px;
      backdrop-filter: blur(8px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
      transition: transform 0.4s ease, background 0.4s ease;
    }

    .project:hover {
      transform: translateY(-10px) scale(1.03);
      background: rgba(255,255,255,0.2);
    }

    .project h3 {
      color: #fff;
      margin-bottom: 10px;
    }

    .project p {
      color: #eaeaea;
      font-size: 0.95em;
      line-height: 1.6;
      min-height: 60px;
    }

    .project a {
      display: inline-block;
      margin-top: 10px;
      background: #ff6b6b;
      color: #fff;
      padding: 10px 18px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s ease;
    }

    .project a:hover {
      background: #ff8e8e;
      transform: translateY(-2px);
    }

    footer {
      margin-top: auto;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      opacity: 0.8;
      animation: fadeIn 2s ease;
    }

    footer a {
      color: #ffdf6b;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }

    /* Animation */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://uploads.onecompiler.io/442e5ty36/44386xdn8/1000032453.webp" alt="أياد شلال" class="profile-img">
    <h1>أياد شلال</h1>
    <p>مبرمج تطبيقات ومواقع ويب | متخصص في واجهات وتجربة المستخدم</p>

    <div class="social-links">
      <a href="https://wa.me/9647711651135" target="_blank" title="واتساب">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="واتساب">
      </a>
      <a href="https://www.instagram.com/pr_ayad?igsh=YWEya2dqMHNzcnht" target="_blank" title="إنستغرام">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="إنستغرام">
      </a>
    </div>
  </header>

  <section class="projects">
    <div class="project">
      <h3>👶 موقع عناية الطفل</h3>
      <p>موقع جميل للعناية بالأطفال والتعليم المبكر، صُمم بواجهة بسيطة وجذابة.</p>
      <a href="https://ayadshll.github.io/baby/" target="_blank">عرض المشروع</a>
    </div>

    <div class="project">
      <h3>⚙️ مشروع جديد</h3>
      <p>تطبيق ويب تفاعلي قيد التطوير — سيتم الإعلان عنه قريبًا.</p>
      <a href="#">قريبًا</a>
    </div>
  </section>

  <footer>
    © 2025 أياد شلال |<a href="ayadshlal282.com">تواصل عبر البريد</a>
  </footer>>
</body>
</html>
