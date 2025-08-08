<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Pepsi Landing Page — README</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      line-height: 1.6;
      color: #111;
      background: #f7f9fc;
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    header { text-align: center; margin-bottom: 1.5rem; }
    h1 { margin: 0; font-size: 1.8rem; }
    p.lead { color: #333; margin-top: .3rem; }
    section { background: white; padding: 1rem 1.25rem; border-radius: 10px; box-shadow: 0 6px 18px rgba(16,24,40,.06); margin-bottom: 1rem; }
    h2 { margin-top: 0; }
    pre { background: #0b1220; color: #d6f8ff; padding: .75rem; border-radius: 6px; overflow:auto; font-size: .95rem; }
    ul { margin-left: 1.15rem; }
    code { background: #eef6ff; padding: .15rem .35rem; border-radius: 4px; }
    .small { font-size: .9rem; color: #555; }
    .note { background: #fff7d6; padding: .6rem; border-left: 4px solid #ffbf00; border-radius:6px; margin-top:.5rem; }
    footer { text-align:center; color:#666; margin-top:1rem; }
    a { color: #0b66ff; text-decoration: none; }
  </style>
</head>
<body>
  <header>
    <h1>Pepsi Landing Page</h1>
    <p class="lead">A responsive HTML &amp; CSS mini project — simple landing page inspired by Pepsi branding.</p>
  </header>

  <section>
    <h2>📌 Project Overview</h2>
    <p>This mini project is a static landing page made with plain <strong>HTML</strong> and <strong>CSS</strong>. It demonstrates a responsive layout, basic animations, and use of an external icon font for social links.</p>
  </section>

  <section>
    <h2>✅ What I built</h2>
    <ul>
      <li>A full <code>index.html</code> page containing:
        <ul>
          <li>Navigation with logo and menu links</li>
          <li>Hero section with headline, paragraph and CTA button</li>
          <li>Product image (Pepsi can) and decorative image set</li>
          <li>Social media icons</li>
        </ul>
      </li>
      <li>Responsive stylesheet <code>style.css</code> with:
        <ul>
          <li>Desktop, tablet and mobile breakpoints</li>
          <li>Keyframe animations for entrance effects</li>
          <li>Fluid spacing and a simple layout using flexbox</li>
        </ul>
      </li>
      <li>An <code>img/</code> folder for images (logo and product images).</li>
    </ul>
  </section>

  <section>
    <h2>🧰 Technologies & Resources Used</h2>
    <ul>
      <li><strong>HTML5</strong> — semantic structure</li>
      <li><strong>CSS3</strong> — layout, responsive rules, animations</li>
      <li><strong>Flexbox</strong> — primary layout technique</li>
      <li><strong>Google Fonts</strong> (Roboto) — page font</li>
      <li><strong>Font Awesome</strong> — social icons (CDN link)</li>
      <li>Images stored locally under <code>img/</code></li>
      <li>Optional: <code>Git</code> for version control and <code>GitHub</code> for hosting</li>
    </ul>
  </section>

  <section>
    <h2>📁 Project Structure</h2>
    <pre>
pepsi-landing-page/
├─ index.html
├─ style.css
├─ img/
│  ├─ pepsi_logo.png
│  ├─ pepsi_can.png
│  └─ three_pepsi.png
└─ README.html
    </pre>
  </section>

  <section>
    <h2>🚀 How to run locally</h2>
    <ol>
      <li>Clone the repository:
        <pre>git clone https://github.com/YOUR-USERNAME/pepsi-landing-page.git</pre>
      </li>
      <li>Open the folder and double-click <code>index.html</code>, or serve it using a simple static server (recommended):
        <pre>npx http-server .   # or use Live Server extension in VS Code</pre>
      </li>
      <li>Open <code>http://localhost:8080</code> (or the port your server shows).</li>
    </ol>
  </section>

  <section>
    <h2>📣 Deploy to GitHub Pages</h2>
    <ol>
      <li>Push your project to a GitHub repo (for example <code>pepsi-landing-page</code>).</li>
      <li>In the repository on GitHub: Settings → Pages → Source: <code>main</code> branch, / (root) → Save.</li>
      <li>After a minute, your site will be available at:
        <br><span class="small">https://<em>YOUR-USERNAME</em>.github.io/pepsi-landing-page/</span>
      </li>
    </ol>
  </section>

  <section>
    <h2>📝 Notes & Tips</h2>
    <div class="note">
      <strong>Fix suggestion for <code>index.html</code>:</strong>
      <div class="small" style="margin-top:.35rem;">
        Your original viewport meta had `content="width= , initial-scale=1.0"`. Replace it with:
        <pre>&lt;meta name="viewport" content="width=device-width, initial-scale=1"&gt;</pre>
        This ensures the page scales correctly on mobile devices.
      </div>
    </div>

    <p style="margin-top:.6rem;" class="small">If you want improved accessibility, add <code>alt</code> text that describes each image more fully and ensure link contrast is high enough.</p>
  </section>

  <section>
    <h2>🤝 Contribution</h2>
    <p>For now this is a solo mini project. If you want to accept contributions later, add a <code>CONTRIBUTING.md</code> and enable issues on GitHub.</p>
  </section>

  <section>
    <h2>📬 Contact</h2>
    <p>If you’d like feedback or improvements, add an issue on the GitHub repo or contact me at <em>your-email@example.com</em> (replace with your real email).</p>
  </section>

  <footer>
    <small>Made with ❤️ — Pepsi Landing Page • Static HTML &amp; CSS</small>
  </footer>
</body>
</html>
