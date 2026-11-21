<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Gelo | Customer Support & E-commerce Support</title>
<style>
:root{
  --bg:#fbf8f4;--surface:#ffffff;--text:#1f2430;--muted:#5d6475;--accent:#e8643c;--accent2:#2f6f6a;--soft:#fdeee7;--border:#ece5dc;
  box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){--bg:#14161c;--surface:#1d2029;--text:#f1eee9;--muted:#a3a9b8;--accent:#ff8059;--accent2:#5fc2b8;--soft:#2a2320;--border:#2c303c;}
}
:root[data-theme="dark"]{--bg:#14161c;--surface:#1d2029;--text:#f1eee9;--muted:#a3a9b8;--accent:#ff8059;--accent2:#5fc2b8;--soft:#2a2320;--border:#2c303c;}
html{scroll-behavior:smooth;scroll-padding-top:calc(80px + env(safe-area-inset-top,0px))}
*{box-sizing:border-box;margin:0}
body{font-family:'Segoe UI',system-ui,-apple-system,Roboto,sans-serif;background:var(--bg);color:var(--text);line-height:1.65;overflow-x:hidden;transition:background .3s,color .3s}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);z-index:99;background:var(--bg)}
.progress{position:fixed;top:env(safe-area-inset-top,0px);left:0;height:3px;background:linear-gradient(90deg,var(--accent),var(--accent2));width:0;z-index:101}
nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:100;display:flex;justify-content:space-between;align-items:center;padding:14px 5vw;background:color-mix(in srgb,var(--bg) 85%,transparent);backdrop-filter:blur(10px);border-bottom:1px solid var(--border)}
.logo{font-weight:800;font-size:1.3rem;color:var(--text);text-decoration:none}
.logo span{color:var(--accent)}
.links{display:flex;gap:6px;align-items:center}
.links a{color:var(--muted);text-decoration:none;font-size:.92rem;padding:8px 12px;border-radius:99px;transition:.25s}
.links a:hover,.links a.active{color:var(--accent);background:var(--soft)}
.icon-btn{background:var(--surface);border:1px solid var(--border);color:var(--text);width:38px;height:38px;border-radius:50%;cursor:pointer;font-size:1rem;transition:.25s}
.icon-btn:hover{transform:rotate(20deg) scale(1.08)}
.burger{display:none}
section{padding:90px 5vw;max-width:1100px;margin:0 auto}
h2{font-size:clamp(1.7rem,4vw,2.3rem);margin-bottom:8px}
h2::after{content:"";display:block;width:56px;height:4px;border-radius:4px;background:var(--accent);margin-top:10px}
.sub{color:var(--muted);margin:14px 0 36px;max-width:620px}
/* hero */
#home{min-height:calc(100vh - 70px);display:flex;align-items:center;position:relative}
.blob{position:absolute;border-radius:50%;filter:blur(60px);opacity:.35;z-index:-1;animation:float 9s ease-in-out infinite}
.b1{width:300px;height:300px;background:var(--accent);top:5%;right:0}
.b2{width:240px;height:240px;background:var(--accent2);bottom:5%;left:-40px;animation-delay:-4s}
@keyframes float{50%{transform:translate(30px,-30px) scale(1.1)}}
.badge{display:inline-block;background:var(--soft);color:var(--accent);padding:6px 14px;border-radius:99px;font-size:.85rem;font-weight:600;margin-bottom:18px}
.wave{display:inline-block;animation:wave 2s infinite;transform-origin:70% 70%}
@keyframes wave{0%,60%,100%{transform:rotate(0)}10%,30%{transform:rotate(16deg)}20%{transform:rotate(-8deg)}40%{transform:rotate(-4deg)}50%{transform:rotate(10deg)}}
h1{font-size:clamp(2.4rem,7vw,4.4rem);line-height:1.1;margin-bottom:12px}
h1 em{font-style:normal;color:var(--accent)}
.typed{font-size:clamp(1.1rem,2.6vw,1.5rem);color:var(--accent2);font-weight:600;min-height:2em}
.typed::after{content:"|";animation:blink 1s infinite}
@keyframes blink{50%{opacity:0}}
.tag{color:var(--muted);margin:10px 0 28px;max-width:560px;font-size:1.08rem}
.btn{display:inline-block;padding:13px 26px;border-radius:99px;font-weight:600;text-decoration:none;border:2px solid var(--accent);cursor:pointer;font-size:.98rem;transition:.25s;font-family:inherit}
.btn.primary{background:var(--accent);color:#fff}
.btn.ghost{background:transparent;color:var(--accent)}
.btn:hover{transform:translateY(-3px);box-shadow:0 10px 22px color-mix(in srgb,var(--accent) 35%,transparent)}
.btns{display:flex;gap:14px;flex-wrap:wrap}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:16px;margin-top:48px;max-width:640px}
.stat{background:var(--surface);border:1px solid var(--border);border-radius:16px;padding:18px;text-align:center}
.stat b{display:block;font-size:1.9rem;color:var(--accent)}
.stat span{font-size:.85rem;color:var(--muted)}
/* about */
.about p{color:var(--muted);margin-bottom:16px;font-size:1.05rem}
.quote{border-left:4px solid var(--accent);background:var(--surface);padding:18px 22px;border-radius:0 14px 14px 0;font-style:italic;margin-top:24px}
/* tabs */
.tabs{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:24px}
.tab{padding:10px 20px;border-radius:99px;border:1px solid var(--border);background:var(--surface);color:var(--text);cursor:pointer;font-weight:600;font-family:inherit;transition:.25s}
.tab:hover{border-color:var(--accent)}
.tab.on{background:var(--accent);color:#fff;border-color:var(--accent)}
.panel{display:none;animation:fade .45s}
.panel.on{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:14px}
@keyframes fade{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:none}}
.chip{background:var(--surface);border:1px solid var(--border);padding:16px 18px;border-radius:14px;display:flex;gap:12px;align-items:flex-start;transition:.25s}
.chip:hover{transform:translateY(-4px);border-color:var(--accent);box-shadow:0 10px 24px rgba(0,0,0,.08)}
.chip i{color:var(--accent2);font-style:normal;font-weight:800}
/* timeline */
.job{background:var(--surface);border:1px solid var(--border);border-radius:18px;padding:26px;margin-bottom:22px;transition:.3s}
.job:hover{transform:translateY(-4px);box-shadow:0 14px 30px rgba(0,0,0,.08)}
.job-head{display:flex;justify-content:space-between;flex-wrap:wrap;gap:8px;cursor:pointer;align-items:center}
.job h3{font-size:1.2rem}
.job .yr{background:var(--soft);color:var(--accent);padding:4px 12px;border-radius:99px;font-size:.85rem;font-weight:600}
.job ul{list-style:none;margin-top:0;max-height:0;overflow:hidden;transition:max-height .5s ease,margin .3s}
.job.open ul{max-height:600px;margin-top:16px}
.job li{padding:7px 0 7px 26px;position:relative;color:var(--muted)}
.job li::before{content:"✓";position:absolute;left:0;color:var(--accent2);font-weight:800}
.hint{font-size:.8rem;color:var(--muted);margin-top:6px}
.toggle{font-size:.85rem;color:var(--accent);font-weight:600}
/* tools */
.tools{display:flex;flex-wrap:wrap;gap:12px}
.tool{background:var(--surface);border:1px solid var(--border);padding:12px 22px;border-radius:99px;font-weight:600;transition:.25s;cursor:default}
.tool:hover{background:var(--accent);color:#fff;transform:translateY(-4px) rotate(-2deg)}
/* approach */
.approach{background:linear-gradient(135deg,var(--accent2),var(--accent));color:#fff;border-radius:24px;padding:44px 36px}
.approach h2::after{background:#fff}
.approach p{opacity:.95;margin-top:14px;max-width:720px}
.steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:14px;margin-top:28px}
.step{background:rgba(255,255,255,.16);border-radius:14px;padding:16px;backdrop-filter:blur(4px);transition:.25s}
.step:hover{background:rgba(255,255,255,.28);transform:scale(1.04)}
.step b{display:block;font-size:1.4rem}
/* contact */
.cta{text-align:center}
.cta h2::after{margin:10px auto 0}
.cta .sub{margin-left:auto;margin-right:auto}
form{max-width:520px;margin:30px auto 0;display:grid;gap:12px;text-align:left}
input,textarea{width:100%;padding:14px 16px;border-radius:12px;border:1px solid var(--border);background:var(--surface);color:var(--text);font:inherit}
input:focus,textarea:focus{outline:2px solid var(--accent);border-color:transparent}
.msg{color:var(--accent2);font-weight:600;text-align:center;min-height:1.5em}
footer{text-align:center;color:var(--muted);padding:30px;font-size:.88rem;border-top:1px solid var(--border)}
.top{position:fixed;right:20px;bottom:calc(20px + env(safe-area-inset-bottom,0px));width:46px;height:46px;border-radius:50%;border:none;background:var(--accent);color:#fff;font-size:1.2rem;cursor:pointer;opacity:0;pointer-events:none;transition:.3s;z-index:100}
.top.show{opacity:1;pointer-events:auto}
.top:hover{transform:translateY(-4px)}
.reveal{opacity:0;transform:translateY(34px);transition:opacity .8s,transform .8s}
.reveal.in{opacity:1;transform:none}
@media(max-width:780px){
  .burger{display:inline-block}
  .links{position:absolute;top:100%;left:0;right:0;flex-direction:column;background:var(--bg);padding:12px;border-bottom:1px solid var(--border);display:none}
  .links.open{display:flex}
  section{padding:70px 5vw}
  .approach{padding:32px 22px}
}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}.reveal{opacity:1;transform:none}}
</style>
</head>
<body>
<div class="progress" id="progress"></div>
<nav>
  <a href="#home" class="logo">Gelo<span>.</span></a>
  <div class="links" id="links">
    <a href="#home">Home</a><a href="#about">About</a><a href="#services">Services</a><a href="#experience">Experience</a><a href="#tools">Tools</a><a href="#approach">Approach</a><a href="#contact">Contact</a>
  </div>
  <div style="display:flex;gap:8px">
    <button class="icon-btn" id="theme" aria-label="Toggle theme">🌙</button>
    <button class="icon-btn burger" id="burger" aria-label="Menu">☰</button>
  </div>
</nav>

<section id="home">
  <div class="blob b1"></div><div class="blob b2"></div>
  <div>
    <span class="badge">Customer Support &amp; E-commerce Support</span>
    <h1>Hi, I'm <em>Gelo</em> <span class="wave">👋</span></h1>
    <div class="typed" id="typed"></div>
    <p class="tag">Helping customers feel heard, supported, and taken care of.</p>
    <div class="btns">
      <a href="#contact" class="btn primary">Let's Work Together</a>
      <a href="#experience" class="btn ghost">View My Experience</a>
    </div>
    <div class="stats">
      <div class="stat"><b data-count="5">0</b><span>Years at Pencil Spaces</span></div>
      <div class="stat"><b data-count="74000">0</b><span>Intercom conversations</span></div>
      <div class="stat"><b data-count="30">0</b><span>Emails handled daily (max)</span></div>
    </div>
  </div>
</section>

<section id="about" class="reveal about">
  <h2>About Me</h2>
  <p class="sub">Reliable, patient, organized, and customer-focused.</p>
  <p>Hi! I'm Gelo, a Customer Support professional with experience supporting customers, managing inquiries, and assisting with e-commerce operations.</p>
  <p>I have a background in customer and technical support, including five years supporting Pencil Spaces, an online learning and tutoring platform. I've also handled e-commerce support tasks, including product inquiries, order concerns, customer follow-ups, and product research.</p>
  <div class="quote">I believe good customer support is more than just answering questions. It's about understanding the customer's concern, taking ownership, and making sure they receive the help they need.</div>
</section>

<section id="services" class="reveal">
  <h2>What I Can Help With</h2>
  <p class="sub">Pick a category to see how I can support your business.</p>
  <div class="tabs" id="tabs">
    <button class="tab on" data-t="p1">Customer Support</button>
    <button class="tab" data-t="p2">E-commerce Support</button>
    <button class="tab" data-t="p3">Administrative Support</button>
  </div>
  <div class="panel on" id="p1">
    <div class="chip"><i>✓</i>Email, chat, and phone support</div>
    <div class="chip"><i>✓</i>Customer inquiries and issue resolution</div>
    <div class="chip"><i>✓</i>Order and delivery concerns</div>
    <div class="chip"><i>✓</i>Returns and refund inquiries</div>
    <div class="chip"><i>✓</i>Customer follow-ups</div>
    <div class="chip"><i>✓</i>Complaint handling and escalation</div>
  </div>
  <div class="panel" id="p2">
    <div class="chip"><i>✓</i>Shopify order management</div>
    <div class="chip"><i>✓</i>Product research and inquiries</div>
    <div class="chip"><i>✓</i>Order status and tracking assistance</div>
    <div class="chip"><i>✓</i>Returns and refund request handling</div>
    <div class="chip"><i>✓</i>Customer information updates</div>
    <div class="chip"><i>✓</i>Product and order documentation</div>
  </div>
  <div class="panel" id="p3">
    <div class="chip"><i>✓</i>Google Sheets tracking and reporting</div>
    <div class="chip"><i>✓</i>Data entry and record management</div>
    <div class="chip"><i>✓</i>Inbox management</div>
    <div class="chip"><i>✓</i>Documentation and organization</div>
    <div class="chip"><i>✓</i>Research and information gathering</div>
  </div>
</section>

<section id="experience" class="reveal">
  <h2>My Experience</h2>
  <p class="sub">Click a card to expand or collapse the details.</p>
  <div class="job open">
    <div class="job-head"><div><h3>Customer Support &amp; Team Lead</h3><div class="hint">Pencil Spaces</div></div><div><span class="yr">2021–2026</span> <span class="toggle">▾</span></div></div>
    <ul>
      <li>Supported students, tutors, parents, and school administrators.</li>
      <li>Handled customer inquiries through Intercom, email, chat, and calls.</li>
      <li>Managed a high volume of customer conversations, with 74,000+ Intercom conversations handled.</li>
      <li>Assisted with account access, billing, scheduling, and technical concerns.</li>
      <li>Helped onboard new users and provided platform guidance.</li>
      <li>Supported and trained team members while helping manage daily support operations.</li>
    </ul>
  </div>
  <div class="job">
    <div class="job-head"><div><h3>E-commerce Customer Support</h3><div class="hint">Product &amp; order support</div></div><div><span class="yr">15–30 emails/day</span> <span class="toggle">▾</span></div></div>
    <ul>
      <li>Responded to approximately 15–30 customer emails daily.</li>
      <li>Assisted customers with product questions and order-related concerns.</li>
      <li>Conducted product research to provide accurate information.</li>
      <li>Helped with customer follow-ups and support documentation.</li>
      <li>Assisted with organizing order and supplier information.</li>
    </ul>
  </div>
</section>

<section id="tools" class="reveal">
  <h2>Tools I Use</h2>
  <p class="sub">Platforms I'm comfortable working with every day.</p>
  <div class="tools">
    <div class="tool">Shopify</div><div class="tool">TikTok Shop</div><div class="tool">Amazon</div><div class="tool">GoHighLevel</div><div class="tool">Intercom</div><div class="tool">Google Workspace</div><div class="tool">Google Sheets</div><div class="tool">Gmail</div><div class="tool">WhatsApp</div>
  </div>
</section>

<section id="approach" class="reveal">
  <div class="approach">
    <h2>My Approach to Customer Support</h2>
    <p>I don't just answer customer inquiries. I make sure every customer feels heard, valued, and taken care of. I take the time to understand each concern, provide clear information, double-check details, and follow through until the issue is properly addressed.</p>
    <div class="steps">
      <div class="step"><b>1</b>Understand the concern</div>
      <div class="step"><b>2</b>Provide clear information</div>
      <div class="step"><b>3</b>Double-check details</div>
      <div class="step"><b>4</b>Follow through</div>
    </div>
  </div>
</section>

<section id="contact" class="reveal cta">
  <h2>Let's Work Together!</h2>
  <p class="sub">If you're looking for someone reliable, patient, organized, and customer-focused to support your business, I'd be happy to be part of your team.</p>
  <form id="form">
    <input type="text" id="name" placeholder="Your name" required>
    <input type="email" id="email" placeholder="Your email" required>
    <textarea id="message" rows="4" placeholder="How can I help your business?" required></textarea>
    <button class="btn primary" type="submit">Send Message</button>
    <div class="msg" id="msg"></div>
  </form>
</section>

<footer>© 2026 Gelo · Customer Support &amp; E-commerce Support</footer>
<button class="top" id="top" aria-label="Back to top">↑</button>

<script>
(function(){
  // Typing effect
  var words=["Customer Support Professional","E-commerce Support Specialist","Team Lead & Trainer","Administrative Support"];
  var el=document.getElementById('typed'),w=0,c=0,del=false;
  function type(){
    var cur=words[w];
    el.textContent=cur.substring(0,c);
    if(!del&&c===cur.length){del=true;return setTimeout(type,1500)}
    if(del&&c===0){del=false;w=(w+1)%words.length}
    c+=del?-1:1;
    setTimeout(type,del?35:70);
  }
  type();

  // Mobile menu
  var links=document.getElementById('links');
  document.getElementById('burger').onclick=function(){links.classList.toggle('open')};
  links.querySelectorAll('a').forEach(function(a){a.addEventListener('click',function(){links.classList.remove('open')})});

  // Theme
  var root=document.documentElement,tbtn=document.getElementById('theme');
  function setTheme(t){root.setAttribute('data-theme',t);tbtn.textContent=t==='dark'?'☀️':'🌙'}
  var dark=window.matchMedia&&window.matchMedia('(prefers-color-scheme: dark)').matches;
  setTheme(dark?'dark':'light');
  tbtn.onclick=function(){setTheme(root.getAttribute('data-theme')==='dark'?'light':'dark')};

  // Tabs
  document.querySelectorAll('.tab').forEach(function(t){
    t.onclick=function(){
      document.querySelectorAll('.tab').forEach(function(x){x.classList.remove('on')});
      document.querySelectorAll('.panel').forEach(function(x){x.classList.remove('on')});
      t.classList.add('on');
      document.getElementById(t.dataset.t).classList.add('on');
    };
  });

  // Job accordion
  document.querySelectorAll('.job-head').forEach(function(h){
    h.onclick=function(){
      var j=h.parentElement;j.classList.toggle('open');
      h.querySelector('.toggle').textContent=j.classList.contains('open')?'▴':'▾';
    };
  });
  document.querySelector('.job.open .toggle').textContent='▴';

  // Reveal + counters
  var counted=false;
  function count(){
    document.querySelectorAll('[data-count]').forEach(function(n){
      var target=+n.dataset.count,start=null;
      function f(ts){
        if(!start)start=ts;
        var p=Math.min((ts-start)/1600,1);
        var v=Math.floor(target*p);
        n.textContent=v.toLocaleString()+(p===1&&target>=1000?'+':'');
        if(p<1)requestAnimationFrame(f);
      }
      requestAnimationFrame(f);
    });
  }
  var io=new IntersectionObserver(function(es){
    es.forEach(function(e){if(e.isIntersecting)e.target.classList.add('in')});
  },{threshold:.12});
  document.querySelectorAll('.reveal').forEach(function(r){io.observe(r)});
  var so=new IntersectionObserver(function(es){
    if(es[0].isIntersecting&&!counted){counted=true;count()}
  },{threshold:.4});
  so.observe(document.querySelector('.stats'));

  // Scroll: progress, back-to-top, active link
  var secs=['home','about','services','experience','tools','approach','contact'];
  var navA=links.querySelectorAll('a');
  var topBtn=document.getElementById('top');
  function onScroll(){
    var h=document.documentElement;
    var pct=h.scrollTop/(h.scrollHeight-h.clientHeight)*100;
    document.getElementById('progress').style.width=pct+'%';
    topBtn.classList.toggle('show',h.scrollTop>500);
    var cur='home';
    secs.forEach(function(id){
      var s=document.getElementById(id);
      if(s.getBoundingClientRect().top<150)cur=id;
    });
    navA.forEach(function(a){a.classList.toggle('active',a.getAttribute('href')==='#'+cur)});
  }
  window.addEventListener('scroll',onScroll,{passive:true});onScroll();
  topBtn.onclick=function(){window.scrollTo({top:0,behavior:'smooth'})};

  // Contact form (demo: opens the visitor's email app)
  document.getElementById('form').onsubmit=function(e){
    e.preventDefault();
    var n=document.getElementById('name').value,em=document.getElementById('email').value,m=document.getElementById('message').value;
    var body=encodeURIComponent(m+'\n\nFrom: '+n+' ('+em+')');
    document.getElementById('msg').textContent='Thanks, '+n+'! Opening your email app to send your message…';
    window.location.href='mailto:?subject='+encodeURIComponent('Inquiry for Gelo')+'&body='+body;
    this.reset();
  };
})();
</script>
</body>
</html>
