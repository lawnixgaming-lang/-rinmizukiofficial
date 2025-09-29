<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>RinMizuki — Open for Commissions</title>
<meta name="description" content="RinMizuki — Open for commissions: custom Discord bot setup, configuration, and personal bot development." />
<style>
  :root {
    --bg:#0f1724;
    --card:#0b1220;
    --muted:#9aa4b2;
    --accent:#5865F2;
    --glass: rgba(255,255,255,0.03);
    --radius:14px;
    --max-width:980px;
    font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  }

  html, body {
    height: 100%;
    margin: 0;
    background: linear-gradient(180deg,#071226 0%, var(--bg) 100%);
    color: #e6eef6;
    text-align: center;
  }

  .wrap {
    max-width: var(--max-width);
    margin: 20px auto;
    padding: 20px;
    background: linear-gradient(180deg,var(--glass),transparent);
    border-radius: var(--radius);
    box-shadow: 0 8px 30px rgba(2,6,23,0.6);
    backdrop-filter: blur(6px);
  }

  header {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 12px;
  }
  .logo {
    width: 72px;
    height: 72px;
    border-radius: 12px;
    background: url('https://pbs.twimg.com/media/DGo0HjbU0AAbidc.jpg:large') center/cover no-repeat;
  }
  h1 { margin:0; font-size:28px; }
  p.lead { color: var(--muted); margin-top:6px; }

  .grid {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    margin-top: 22px;
  }

  section, aside {
    width: 100%;
    max-width: 600px;
  }

  .card {
    background: var(--card);
    padding: 18px;
    border-radius: 12px;
    margin-bottom: 16px;
    text-align: center;
  }

  ul, ol { padding-left: 20px; text-align: left; margin: 0 auto; }
  ul li, ol li { margin-bottom: 8px; }

  .services li { color: var(--muted); }
  .features {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    justify-content: center;
    margin-top: 16px;
  }
  .feature {
    background: linear-gradient(180deg, rgba(255,255,255,0.01), transparent);
    padding: 12px;
    border-radius: 10px;
    min-width: 140px;
    flex: 1;
  }

  .cta {
    display: flex;
    flex-direction: column;
    gap: 10px;
    align-items: center;
    margin-top: 12px;
  }
  .btn {
    background: var(--accent);
    color: white;
    padding: 10px 14px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: 600;
    width: 100%;
    max-width: 220px;
    text-align: center;
  }
  .btn.ghost { background: transparent; border: 1px solid rgba(255,255,255,0.06); color: var(--muted); }

  pre.code { background:#061124; padding:12px; border-radius:8px; color:#9ad4ff; overflow:auto; font-size:13px; text-align:left; }
  .price { font-weight:800; font-size:22px; color:white; margin-top:4px; }
  .small { font-size:13px; color:var(--muted); margin-top:2px; }

  footer { margin-top:18px; font-size:13px; color: var(--muted); }

  /* Responsive */
  @media(max-width: 860px){
    .logo { width: 56px; height: 56px; }
    ul, ol { padding-left: 16px; }
  }
  @media(max-width: 480px){
    .wrap { padding: 16px; }
    .card { padding: 12px; }
    .feature { min-width: 100%; }
    .btn { max-width: 100%; }
    ul, ol { padding-left: 12px; }
  }
</style>
</head>
<body>
<main class="wrap" role="main">

  <header>
    <div class="logo"></div>
    <h1>RinMizuki — Open for Commissions</h1>
    <p class="lead">I build and set up personal Discord bots, configure servers, and deliver ready-to-run projects tailored to you.</p>
  </header>

  <div class="grid">

    <!-- Left column -->
    <section>
      <div class="card">
        <h2>What I offer</h2>
        <ul class="services">
          <li>✅ Custom Discord bot development (commands, moderation, economy, music, etc.)</li>
          <li>✅ Bot setup & hosting guidance (Heroku, Replit, VPS, Termux)</li>
          <li>✅ Welcome images, embeds, and automated messages</li>
          <li>✅ Slash commands, admin tools, and role management</li>
          <li>✅ Bot verification preparation (ToS, Privacy, OAuth install links)</li>
          <li>✅ Ongoing maintenance and feature additions (by request)</li>
        </ul>

        <h3>How it works</h3>
        <ol>
          <li>Tell me your idea — features, server size, and preferred behavior.</li>
          <li>I send a quote and a delivery ETA.</li>
          <li>After approval, I build and test the bot in your server.</li>
          <li>Delivery: bot files, setup guide, and optional hosting help.</li>
        </ol>

        <div>
          <strong>Example starter packages</strong>
          <div style="display:flex; gap:10px; flex-wrap:wrap; justify-content:center; margin-top:8px;">
            <div class="card" style="padding:10px; min-width:140px;">
              <div class="small">Basic Setup</div>
              <div class="price">$6</div>
              <div class="small">Bot setup, basic commands, invite link</div>
            </div>
            <div class="card" style="padding:10px; min-width:140px;">
              <div class="small">Standard Bot</div>
              <div class="price">$15</div>
              <div class="small">Custom commands, welcome image, moderation</div>
            </div>
            <div class="card" style="padding:10px; min-width:140px;">
              <div class="small">Premium</div>
              <div class="price">$45+</div>
              <div class="small">Full custom bot, hosting guide, ongoing support</div>
            </div>
          </div>
          <div class="small" style="margin-top:6px;">Prices are examples — final quote depends on requirements.</div>
        </div>
      </div>

      <div class="card">
        <h3>Why choose me</h3>
        <div class="features">
          <div class="feature"><strong>Fast delivery</strong><div class="small">Quick turnaround and clear milestones.</div></div>
          <div class="feature"><strong>Clear communication</strong><div class="small">Progress updates and testing in your server.</div></div>
          <div class="feature"><strong>Secure</strong><div class="small">I don't store private keys or passwords — I guide secure setup.</div></div>
          <div class="feature"><strong>Verified help</strong><div class="small">I assist with ToS/Privacy and verification steps for Discord.</div></div>
        </div>
      </div>

      <div class="card">
        <h3>Quick example (how I deliver)</h3>
        <pre class="code"># Example: invite link (generated in the Dev Portal)
https://discord.com/oauth2/authorize?client_id=123456789&permissions=8&scope=bot%20applications.commands
</pre>
        <div class="small">You receive the bot files, .env example, run instructions, and an install invite.</div>
      </div>
    </section>

    <!-- Right column -->
    <aside>
      <div class="card">
        <h3>Contact & Book</h3>
        <p class="small">To request a quote or start a commission, contact me with: your server size, desired features, and budget.</p>
        <p style="margin-top:8px"><strong>Email</strong><br> <a href="mailto:yrothebest@gmail.com" style="color:var(--accent); text-decoration:none;">yrothebest@gmail.com</a></p>
        <p style="margin-top:6px"><strong>Discord</strong><br><span style="color:var(--muted)">@rinmizukiofficial</span></p>

        <div class="cta">
          <a class="btn" href="mailto:yrothebest@gmail.com">Hire me on Email</a>
          <a class="btn ghost" href="https://discord.com/users/370404534838886401" target="_blank" rel="noopener">Message on Discord</a>
        </div>

        <hr style="border:none;border-top:1px solid rgba(255,255,255,0.04);margin:12px 0">

        <h4>What I need to start</h4>
        <ul style="color:var(--muted);">
          <li>Bot purpose & core commands</li>
          <li>Desired permissions & example server ID</li>
          <li>Preferred hosting (I can advise)</li>
        </ul>
      </div>

      <div class="card">
        <h4>Terms</h4>
        <p class="small">All commissions require agreement on scope and a delivery timeline. I may ask for a partial upfront payment for large projects.</p>
      </div>
    </aside>

  </div>

  <footer>
    <div class="small">© RinMizuki • Open for Commissions • Email: yrothebest@gmail.com • Discord: @rinmizukiofficial</div>
  </footer>

</main>
</body>
</html>
