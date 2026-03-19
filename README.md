<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>EoE — Readme Language Tabs Demo</title>
  <style>
    /* Simple tabs using hidden radio inputs */
    .tabs { max-width: 900px; margin: 24px auto; font-family: system-ui, sans-serif; }
    .tab-labels { display:flex; gap:8px; }
    .tab-labels label {
      padding:8px 12px; border-radius:6px; background:#f1f1f1; cursor:pointer;
      user-select:none;
    }
    input[name="tab"] { display:none; }
    /* content sections hidden by default */
    .tab-content { border:1px solid #eee; padding:16px; margin-top:12px; border-radius:6px; background:#fff; }
    #tab-en:checked ~ .tab-labels label[for="tab-en"],
    #tab-zh:checked ~ .tab-labels label[for="tab-zh"] {
      background:#0366d6; color:#fff;
    }
    #tab-en:checked ~ .contents #en,
    #tab-zh:checked ~ .contents #zh {
      display:block;
    }
    .contents section { display:none; }
  </style>
</head>
<body>
  <main class="tabs" role="main">
    <!-- radio controls -->
    <input id="tab-en" type="radio" name="tab" checked>
    <input id="tab-zh" type="radio" name="tab">
    <!-- labels act as tab buttons -->
    <div class="tab-labels" aria-hidden="true">
      <label for="tab-en">English</label>
      <label for="tab-zh">中文（繁體）</label>
    </div>

    <!-- tab contents -->
    <div class="contents">
      <section id="en" class="tab-content" aria-labelledby="tab-en">
        <h1>Echoes of Emotion (EoE)</h1>
        <p>A website combining contemporary ceramic art with modern digital interactive technology.</p>
        <h2>Quick start</h2>
        <pre><code>python -m http.server 8000</code></pre>
      </section>

      <section id="zh" class="tab-content" aria-labelledby="tab-zh">
        <h1>Echoes of Emotion（EoE）</h1>
        <p>結合當代陶藝與數位互動技術的網站。</p>
        <h2>快速上手</h2>
        <pre><code>python -m http.server 8000</code></pre>
      </section>
    </div>
  </main>
</body>
</html>
