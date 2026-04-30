# CoreStrength-site
[best version.html](https://github.com/user-attachments/files/27239252/best.version.html)


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CoreStrength Marketing Co.</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

<style>
:root {
  --bg: #0a0a0a;
  --white: #ffffff;
  --accent: #3b82f6;
  --gray: #9ca3af;
  --success: #22c55e;
}

* { margin:0; padding:0; box-sizing:border-box; font-family:'Inter',sans-serif; }
body { background:var(--bg); color:var(--white); }

nav {
  position: fixed;
  width: 100%;
  top: 0;
  padding: 20px 5%;
  display: flex;
  justify-content: space-between;
  background: rgba(0,0,0,0.7);
  backdrop-filter: blur(10px);
}

nav a { color:white; text-decoration:none; margin-left:25px; }
.logo { font-weight:800; }

.btn {
  padding:12px 22px;
  border-radius:30px;
  text-decoration:none;
  font-weight:600;
  display:inline-block;
}

.btn-primary { background:var(--accent); color:white; }

.hero {
  height:100vh;
  display:flex;
  align-items:center;
  padding:0 5%;
  background:
    linear-gradient(rgba(0,0,0,0.75), rgba(0,0,0,0.85)),
    url('https://images.unsplash.com/photo-1556745757-8d76bdb6984b') center/cover;
}

.hero h1 { font-size:3.5rem; max-width:700px; }
.hero p { color:var(--gray); margin:20px 0; }

section { padding:100px 5%; }
.section-title { font-size:2.5rem; margin-bottom:20px; }

.section-sub {
  color: #9ca3af;
  margin-bottom: 50px;
  max-width: 600px;
}

.grid {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:30px;
}

.card {
  padding:30px;
  background:rgba(255,255,255,0.03);
  border-radius:15px;
}

.cta {
  text-align:center;
  background:linear-gradient(135deg,#3b82f6,#1d4ed8);
}

input, textarea {
  width:100%;
  padding:12px;
  margin:10px 0;
  border:none;
  border-radius:8px;
}

.success {
  display:none;
  text-align:center;
  margin-top:20px;
  color:var(--success);
}
</style>
</head>

<body>

<nav>
  <div class="logo">CoreStrength</div>
  <div>
    <a href="#services">Services</a>
    <a href="#process">Process</a>
    <a href="https://calendly.com/corestrengthmarketing-co/30min" target="_blank" class="btn btn-primary">
      Apply for a Strategy Call
    </a>
  </div>
</nav>

<section class="hero">
  <div>
    <h1>Get More Leads & Clients for Your Business</h1>
    <p>We build marketing systems that consistently bring you qualified leads.</p>

    <a href="https://calendly.com/corestrengthmarketing-co/30min" target="_blank" class="btn btn-primary">
      Apply for a Strategy Call
    </a>
  </div>
</section>

<!-- UPGRADED VALUE SECTION -->
<section>
  <h2 class="section-title">Built for Serious Business Growth</h2>
  <p class="section-sub">
    We don’t just run ads or build websites — we create complete systems designed to attract, convert, and scale your business consistently.
  </p>

  <div class="grid">
    <div class="card">
      <h3>🚀 Done-for-You Growth Systems</h3>
      <p>
        We handle everything — from strategy to execution — so you can focus on running your business while we bring in leads.
      </p>
    </div>

    <div class="card">
      <h3>📈 Predictable Lead Flow</h3>
      <p>
        No more guessing where your next client is coming from. We build systems that generate consistent, qualified leads.
      </p>
    </div>

    <div class="card">
      <h3>🛡️ Low-Risk, Data-Driven Approach</h3>
      <p>
        Every decision is backed by data and performance tracking — allowing us to optimize and improve results over time.
      </p>
    </div>

    <div class="card">
      <h3>⚡ Built to Scale</h3>
      <p>
        Our systems are designed not just to work — but to grow with your business as you increase revenue and demand.
      </p>
    </div>
  </div>
</section>

<!-- UPGRADED SERVICES -->
<section id="services">
  <h2 class="section-title">What We Do</h2>
  <p class="section-sub">
    We build and optimize the core systems your business needs to attract clients, convert leads, and scale revenue.
  </p>

  <div class="grid">

    <div class="card">
      <h3>Paid Advertising That Converts</h3>
      <p>
        We create and manage high-performing ad campaigns across platforms, focused on generating real leads — not just clicks.
      </p>
    </div>

    <div class="card">
      <h3>High-Converting Lead Systems</h3>
      <p>
        We design landing pages and funnels that turn visitors into qualified prospects ready to take action.
      </p>
    </div>

    <div class="card">
      <h3>Conversion-Focused Websites</h3>
      <p>
        Your website becomes a sales asset — built to capture attention, build trust, and drive conversions.
      </p>
    </div>

    <div class="card">
      <h3>Brand Positioning & Strategy</h3>
      <p>
        We help you stand out in your market with clear messaging, strong positioning, and a brand that attracts the right clients.
      </p>
    </div>

  </div>
</section>

<!-- PROCESS -->
<section id="process">
  <h2 class="section-title">Our Proven Growth Process</h2>
  <p class="section-sub">
    A simple, structured system designed to generate consistent leads and scale your business.
  </p>

  <div class="grid">
    <div class="card">
      <h3>1. Deep Audit</h3>
      <p>We analyze your marketing and identify where you're losing leads.</p>
    </div>

    <div class="card">
      <h3>2. Strategy Build</h3>
      <p>We create a custom plan to increase leads and conversions.</p>
    </div>

    <div class="card">
      <h3>3. Launch & Implementation</h3>
      <p>We build and launch your systems quickly.</p>
    </div>

    <div class="card">
      <h3>4. Optimize & Scale</h3>
      <p>We improve and scale what works to grow your revenue.</p>
    </div>
  </div>
</section>

<section class="cta">
  <h2>Find Out How to Scale Your Business Faster</h2>
  <p>Apply now and we’ll see if you’re a fit.</p>

  <a href="https://calendly.com/corestrengthmarketing-co/30min" target="_blank" class="btn btn-primary">
    Apply for a Strategy Call
  </a>
</section>

<section id="contact">
  <h2 class="section-title">Or Get a Free Growth Plan</h2>

  <form action="https://formspree.io/f/xkokdaez" method="POST" id="leadForm">
    <input type="text" name="name" placeholder="Full Name" required>
    <input type="email" name="email" placeholder="Email" required>
    <textarea name="message" placeholder="What do you need help with?"></textarea>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>

  <div class="success" id="successMsg">
    ✅ Thanks! Now apply for your strategy call 👇<br><br>

    <a href="https://calendly.com/corestrengthmarketing-co/30min" target="_blank" class="btn btn-primary">
      Apply for a Strategy Call
    </a>
  </div>

  <div style="text-align:center; margin-top:30px;">
    <p><strong>Email:</strong> corestrengthmarketing.co@gmail.com</p>
    <p><strong>Phone:</strong> 0422 297 570</p>
  </div>
</section>

<footer style="text-align:center; padding:40px; color:#9ca3af;">
  © 2026 CoreStrength Marketing Co.<br><br>
  corestrengthmarketing.co@gmail.com | 0422 297 570
</footer>

<script>
const form = document.getElementById('leadForm');
form.addEventListener('submit', function(e) {
  e.preventDefault();

  fetch(form.action, {
    method: "POST",
    body: new FormData(form),
    headers: { 'Accept': 'application/json' }
  }).then(response => {
    if (response.ok) {
      form.reset();
      document.getElementById("successMsg").style.display = "block";
    }
  });
});
</script>

</body>
</html>
