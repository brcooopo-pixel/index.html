# index.html
e2ee free
<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#101426">
  <title>PrivateChat — निजी बातचीत</title>
  <style>
    :root {
      color-scheme: dark;
      --bg: #101426;
      --panel: #191f35;
      --text: #f4f6ff;
      --muted: #b4bdd5;
      --accent: #8b7cff;
      --green: #78e0b2;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      background:
        radial-gradient(ellipse at 80% 0%, #392d72 0, transparent 38%),
        var(--bg);
      color: var(--text);
      font-family: system-ui, -apple-system, "Segoe UI", sans-serif;
      line-height: 1.6;
    }

    .wrap {
      width: min(100% - 36px, 980px);
      margin: auto;
    }

    header {
      padding: 22px 0;
      border-bottom: 1px solid #ffffff18;
    }

    .brand {
      font-weight: 750;
      font-size: 1.15rem;
      letter-spacing: .2px;
    }

    .brand span { color: var(--green); }

    main { padding: 72px 0 48px; }

    .badge {
      display: inline-block;
      padding: 6px 12px;
      border: 1px solid #78e0b255;
      border-radius: 999px;
      color: var(--green);
      font-size: .9rem;
    }

    h1 {
      max-width: 760px;
      margin: 20px 0 14px;
      font-size: clamp(2.5rem, 8vw, 5rem);
      line-height: 1.05;
      letter-spacing: -2px;
    }

    .intro {
      max-width: 680px;
      color: var(--muted);
      font-size: 1.12rem;
    }

    .notice {
      margin-top: 28px;
      padding: 16px 18px;
      border: 1px solid #8b7cff66;
      border-radius: 14px;
      background: #8b7cff12;
      color: #e2ddff;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 16px;
      margin-top: 42px;
    }

    .card {
      padding: 22px;
      border: 1px solid #ffffff18;
      border-radius: 18px;
      background: var(--panel);
    }

    .card h2 { margin: 0 0 8px; font-size: 1.1rem; }
    .card p { margin: 0; color: var(--muted); }

    footer {
      padding: 24px 0 36px;
      border-top: 1px solid #ffffff18;
      color: var(--muted);
      font-size: .92rem;
    }

    a { color: var(--green); }
  </style>
</head>
<body>
  <header>
    <div class="wrap brand">Private<span>Chat</span></div>
  </header>

  <main class="wrap">
    <span class="badge">परियोजना परिचय</span>
    <h1>निजी बातचीत के लिए बनाया गया विचार।</h1>
    <p class="intro">
      PrivateChat का लक्ष्य दो Android फोन के बीच Room Code से टेक्स्ट चैट
      करना है। यह पेज परियोजना की जानकारी देता है; यह खुद चैट स्क्रीन नहीं है।
    </p>

    <div class="notice">
      <strong>ज़रूरी जानकारी:</strong> इस वेबसाइट पर अभी चैट, Room Code से
      कनेक्शन या संदेश भेजने की सुविधा नहीं है। बिना सर्वर/रिले के इंटरनेट पर
      हर नेटवर्क में सीधा कनेक्शन संभव नहीं होता। ऐप में ये सुविधाएँ तभी काम
      करेंगी जब Android ऐप का वास्तविक कोड बनाया और दोनों फोन पर चलाया जाए।
    </div>

    <section class="grid" aria-label="परियोजना की जानकारी">
      <article class="card">
        <h2>Android ऐप</h2>
        <p>लक्ष्य Android-to-Android टेक्स्ट चैट ऐप बनाना है।</p>
      </article>
      <article class="card">
        <h2>Room Code</h2>
        <p>कोड के ज़रिए दो डिवाइस जोड़ने की सुविधा प्रस्तावित है।</p>
      </article>
      <article class="card">
        <h2>निजता</h2>
        <p>सुरक्षित संदेशों के लिए प्रमाणित क्रिप्टोग्राफी और सही peer authentication ज़रूरी हैं।</p>
      </article>
    </section>
  </main>

  <footer>
    <div class="wrap">PrivateChat — परियोजना जानकारी</div>
  </footer>
</body>
</html>
