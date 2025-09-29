<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>RinMizuki — Open for Commissions (Bot Setup & Custom Bots)</title>
<meta name="description" content="RinMizuki — Open for commissions: custom Discord bot setup, configuration, and personal bot development." />
<style>
  :root{
    --bg:#0f1724;
    --card:#0b1220;
    --muted:#9aa4b2;
    --accent:#5865F2;
    --glass: rgba(255,255,255,0.03);
    --max-width:980px;
    --radius:14px;
    font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  }
  html, body {height:100%; margin:0; background:linear-gradient(180deg,#071226 0%, var(--bg) 100%); color:#e6eef6;}
  .wrap {
    max-width: var(--max-width);
    margin: 20px auto;
    padding: 28px;
    background: linear-gradient(180deg,var(--glass),transparent);
    border-radius: var(--radius);
    box-shadow: 0 8px 30px rgba(2,6,23,0.6);
    backdrop-filter: blur(6px);
  }
  header {display:flex; gap:20px; align-items:center; flex-wrap:wrap; justify-content:center;}
  .logo {width:72px; height:72px; border-radius:12px; background:url('https://pbs.twimg.com/media/DGo0HjbU0AAbidc.jpg:large') center/cover no-repeat;}
  h1 {margin:0; font-size:28px; text-align:center;}
  p.lead {color:var(--muted); margin-top:6px; text-align:center;}
  .grid {display:grid; grid-template-columns: 1fr 1fr; gap:20px; margin-top:22px;}
  .card {background:var(--card); padding:18px; border-radius:12px; width:100%; box-sizing:border-box;}
  .services li {margin:10px 0; color:var(--muted);}
  .cta {display:flex; gap:10px; flex-wrap:wrap; margin-top:14px; justify-content:center;}
  .btn {background:var(--accent); color:white; padding:10px 14px; border-radius:10px; text-decoration:none; font-weight:600; display:inline-block; text-align:center;}
  .btn.ghost {background:transparent; border:1px solid rgba(255,255,255,0.06); color:var(--muted);}
  .price {font-weight:800; font-size:22px; color:white;}
  .small {font-size:13px; color:var(--muted);}
  footer {margin-top:18px; text-align:center; color:var(--muted); font-size:13px;}
  .features {display:grid; grid-template-columns:repeat(auto-fit,minmax(200px,1fr)); gap:12px; margin-top:16px;}
  .feature {background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent); padding:12px; border-radius:10px;}
  pre.code {background:#061124; padding:12px; border-radius:8px; color:#9ad4ff; overflow:auto; font-size:13px;}

  /* Responsive */
  @media(max-width: 860px){
    .grid {grid-template-columns:1fr; justify-items:center;}
    .logo {width:56px; height:56px;}
    header {flex-direction:column; gap:12px;}
    h1, p.lead {text-align:center;}
  }
  @media(max-width: 480px){
    .wrap {padding:16px;}
    .card {padding:12px;}
    .features {grid-template-columns:1fr;}
    .cta {flex-direction:column; gap:8px;}
    .btn {width:100%; text-align:center;}
  }
</style>
</head>
<body>
<main class="wrap" role="main">

  <header>
    <div class="logo"></div>
    <div>
      <h1>RinMizuki — Open for Commissions</h1>
      <p class="lead">I build and set up personal Discord bots, configure servers, and deliver ready-to-run projects tailored to you.</p>
    </div>
  </header>

  <div class="grid">

    <!-- Left column -->
    <section style="width:100%; max-width:600px;">
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

        <h3 style="margin-top:14px">How it works</h3>
        <ol style="color:var(--muted); padding-left:18px">
          <li>Tell me your idea — features, server size, and preferred behavior.</li>
          <li>I send a quote and a delivery ETA.</li>
          <li>After approval, I build and test the bot in your server.</li>
          <li>Delivery: bot files, setup guide, and optional hosting help.</li>
        </ol>

        <div style="margin-top:12px">
          <strong>Example starter packages</strong>
          <div style="display:flex;gap:10px;margin-top:8px;flex-wrap:wrap; justify-content:center;">
            <div class="card" style="padding:10px; border-radius:10px; min-width:140px;">
              <div class="small">Basic Setup</div>
              <div class="price">$6</div>
              <div class="small">Bot setup, basic commands, invite link</div>
            </div>
            <div class="card" style="padding:10px; border-radius:10px; min-width:140px;">
              <div class="small">Standard Bot</div>
              <div class="price">$15</div>
              <div class="small">Custom commands, welcome image, moderation</div>
            </div>
            <div class="card" style="padding:10px; border-radius:10px; min-width:140px;">
              <div class="small">Premium</div>
              <div class="price">$45+</div>
              <div class="small">Full custom bot, hosting guide, ongoing support</div>
            </div>
          </div>
          <div class="small" style="margin-top:8px">Prices are examples — final quote depends on requirements.</div>
        </div>
      </div>

      <div class="card" style="margin-top:12px">
        <h3>Why choose me</h3>
        <div class="features">
          <div class="feature"><strong>Fast delivery</strong><div class="small">Quick turnaround and clear milestones.</div></div>
          <div class="feature"><strong>Clear communication</strong><div class="small">Progress updates and testing in your server.</div></div>
          <div class="feature"><strong>Secure</strong><div class="small">I don't store private keys or passwords — I guide secure setup.</div></div>
          <div class="feature"><strong>Verified help</strong><div class="small">I assist with ToS/Privacy and verification steps for Discord.</div></div>
        </div>
      </div>

      <div class="card" style="margin-top:12px">
        <h3>Quick example (how I deliver)</h3>
        <pre class="code"># Example: invite link (generated in the Dev Portal)
https://discord.com/oauth2/authorize?client_id=123456789&permissions=8&scope=bot%20applications.commands
</pre>
        <div class="small">You receive the bot files, .env example, run instructions, and an install invite.</div>
      </div>
    </section>

    <!-- Right column -->
    <aside style="width:100%; max-width:320px;">
      <div class="card">
        <h3>Contact & Book</h3>
        <p class="small">To request a quote or start a commission, contact me with: your server size, desired features, and budget.</p>
        <p style="margin-top:8px"><strong>Email</strong><br> <a href="mailto:yrothebest@gmail.com" style="color:var(--accent);text-decoration:none">yrothebest@gmail.com</a></p>
        <p style="margin-top:6px"><strong>Discord</strong><br> <span style="color:var(--muted)">@rinmizukiofficial</span></p>

        <div class="cta">
          <a class="btn" href="mailto:yrothebest@gmail.com">Hire me on Email</a>
          <a class="btn ghost" href="https://discord.com/users/370404534838886401" target="_blank" rel="noopener">Message on Discord</a>
        </div>

        <hr style="border:none;border-top:1px solid rgba(255,255,255,0.04);margin:12px 0">

        <h4>What I need to start</h4>
        <ul style="color:var(--muted);padding-left:18px">
          <li>Bot purpose & core commands</li>
          <li>Desired permissions & example server ID</li>
          <li>Preferred hosting (I can advise)</li>
        </ul>
      </div>

      <div class="card" style="margin-top:12px">
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
