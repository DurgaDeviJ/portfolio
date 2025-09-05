**#home page**
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Durga | Portfolio - Home</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">Durga<span>.</span></a>
      <nav class="site-nav" id="siteNav">
        <a href="index.html" class="active">Home</a>
        <a href="about.html">About</a>
        <a href="skills.html">Skills</a>
        <a href="services.html">Services</a>
        <a href="contact.html">Contact</a>
      </nav>
      <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation" aria-expanded="false">
        <span></span><span></span><span></span>
      </button>
    </div>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="container hero-grid">
        <div class="hero-text">
          <p class="eyebrow">Hello, I'm</p>
          <h1>Durga</h1>
          <h2 class="profession">Front-End Developer</h2>
          <p class="subtitle">I design and build modern, fast, and accessible web experiences.</p>
          <div class="hero-actions">
            <a href="contact.html" class="btn btn-primary">Hire Me</a>
            <a href="about.html" class="btn btn-outline">Learn More</a>
          </div>
          <ul class="hero-badges">
            <li>Responsive</li>
            <li>Accessible</li>
            <li>Performance‑first</li>
          </ul>
          <div class="social-links">
            <a href="#" aria-label="GitHub">🐙</a>
            <a href="#" aria-label="LinkedIn">🔗</a>
            <a href="#" aria-label="Twitter">🐦</a>
          </div>
        </div>
        <div class="hero-media">
          <img src="assets/hero-placeholder.svg" alt="Illustration" />
        </div>
      </div>
    </section>

    <section class="featured" aria-label="Highlights">
      <div class="container features">
        <div class="feature-card">
          <div class="icon">🚀</div>
          <h3>Performance</h3>
          <p>Optimized, responsive interfaces focused on speed and usability.</p>
        </div>
        <div class="feature-card">
          <div class="icon">🎨</div>
          <h3>Design</h3>
          <p>Clean, modern aesthetics aligned with your brand and audience.</p>
        </div>
        <div class="feature-card">
          <div class="icon">🔒</div>
          <h3>Quality</h3>
          <p>Accessible, maintainable code with best practices and testing.</p>
        </div>
        <div class="feature-card">
          <div class="icon">🤝</div>
          <h3>Collaboration</h3>
          <p>Clear communication and iterative delivery to meet goals.</p>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Durga. All rights reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

**#about page**

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Durga | About</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">Durga<span>.</span></a>
      <nav class="site-nav" id="siteNav">
        <a href="index.html">Home</a>
        <a href="about.html" class="active">About</a>
        <a href="skills.html">Skills</a>
        <a href="services.html">Services</a>
        <a href="contact.html">Contact</a>
      </nav>
      <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation" aria-expanded="false">
        <span></span><span></span><span></span>
      </button>
    </div>
  </header>

  <main>
    <section class="page-hero small">
      <div class="container">
        <h1>About Me</h1>
        <p>Passionate about crafting beautiful, user-centric web apps.</p>
      </div>
    </section>

    <section class="about-content">
      <div class="container about-grid">
        <div class="about-media">
          <img src="assets/profile-placeholder.svg" alt="Durga profile" />
        </div>
        <div class="about-text">
          <h2>I'm Durga, a Front-End Developer</h2>
          <p>
            I specialize in building responsive, accessible, and performant web interfaces.
            With a strong eye for design and a love for clean code, I turn ideas into
            engaging digital products. I collaborate closely with teams and stakeholders
            to deliver outcomes that delight users and drive business value.
          </p>
          <ul class="about-highlights">
            <li>Modern stacks: HTML, CSS, JavaScript, React</li>
            <li>Accessibility-first and mobile-first mindset</li>
            <li>Performance optimization and best practices</li>
          </ul>
          <a href="contact.html" class="btn btn-primary">Work With Me</a>
        </div>
      </div>
    </section>

    <section class="about-stats">
      <div class="container">
        <div class="skill-metrics">
          <div class="metric">
            <span class="metric-number" data-target="5">0</span>
            <span class="metric-label">Years Experience</span>
          </div>
          <div class="metric">
            <span class="metric-number" data-target="40">0</span>
            <span class="metric-label">Projects Delivered</span>
          </div>
          <div class="metric">
            <span class="metric-number" data-target="20">0</span>
            <span class="metric-label">Happy Clients</span>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Durga. All rights reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

****# home page ****

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Durga | Portfolio - Home</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">Durga<span>.</span></a>
      <nav class="site-nav" id="siteNav">
        <a href="index.html" class="active">Home</a>
        <a href="about.html">About</a>
        <a href="skills.html">Skills</a>
        <a href="services.html">Services</a>
        <a href="contact.html">Contact</a>
      </nav>
      <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation" aria-expanded="false">
        <span></span><span></span><span></span>
      </button>
    </div>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="container hero-grid">
        <div class="hero-text">
          <p class="eyebrow">Hello, I'm</p>
          <h1>Durga</h1>
          <h2 class="profession">Front-End Developer</h2>
          <p class="subtitle">I design and build modern, fast, and accessible web experiences.</p>
          <div class="hero-actions">
            <a href="contact.html" class="btn btn-primary">Hire Me</a>
            <a href="about.html" class="btn btn-outline">Learn More</a>
          </div>
          <ul class="hero-badges">
            <li>Responsive</li>
            <li>Accessible</li>
            <li>Performance‑first</li>
          </ul>
          <div class="social-links">
            <a href="#" aria-label="GitHub">🐙</a>
            <a href="#" aria-label="LinkedIn">🔗</a>
            <a href="#" aria-label="Twitter">🐦</a>
          </div>
        </div>
        <div class="hero-media">
          <img src="assets/hero-placeholder.svg" alt="Illustration" />
        </div>
      </div>
    </section>

    <section class="featured" aria-label="Highlights">
      <div class="container features">
        <div class="feature-card">
          <div class="icon">🚀</div>
          <h3>Performance</h3>
          <p>Optimized, responsive interfaces focused on speed and usability.</p>
        </div>
        <div class="feature-card">
          <div class="icon">🎨</div>
          <h3>Design</h3>
          <p>Clean, modern aesthetics aligned with your brand and audience.</p>
        </div>
        <div class="feature-card">
          <div class="icon">🔒</div>
          <h3>Quality</h3>
          <p>Accessible, maintainable code with best practices and testing.</p>
        </div>
        <div class="feature-card">
          <div class="icon">🤝</div>
          <h3>Collaboration</h3>
          <p>Clear communication and iterative delivery to meet goals.</p>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Durga. All rights reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

**#java script code**

// Durga Portfolio - Interactivity & Utilities

// Mobile navigation toggle
const navToggleButton = document.getElementById('navToggle');
const siteNav = document.getElementById('siteNav');
if (navToggleButton && siteNav) {
  navToggleButton.addEventListener('click', () => {
    const willOpen = !siteNav.classList.contains('open');
    siteNav.classList.toggle('open', willOpen);
    navToggleButton.setAttribute('aria-expanded', String(willOpen));
  });

  siteNav.querySelectorAll('a').forEach((link) => {
    link.addEventListener('click', () => {
      siteNav.classList.remove('open');
      navToggleButton.setAttribute('aria-expanded', 'false');
    });
  });
}

// Dynamic year in footer
const yearSpan = document.getElementById('year');
if (yearSpan) {
  yearSpan.textContent = String(new Date().getFullYear());
}

// Smooth scroll for in-page anchors (if any)
document.querySelectorAll('a[href^="#"]').forEach((anchor) => {
  anchor.addEventListener('click', (event) => {
    const href = anchor.getAttribute('href');
    if (!href || href.length < 2) return;
    const target = document.querySelector(href);
    if (target) {
      event.preventDefault();
      target.scrollIntoView({ behavior: 'smooth', block: 'start' });
    }
  });
});

// Contact form validation
const contactForm = document.getElementById('contactForm');
if (contactForm) {
  const nameInput = document.getElementById('name');
  const emailInput = document.getElementById('email');
  const messageInput = document.getElementById('message');
  const nameError = document.getElementById('nameError');
  const emailError = document.getElementById('emailError');
  const messageError = document.getElementById('messageError');
  const formSuccess = document.getElementById('formSuccess');

  function isValidEmail(email) {
    return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(String(email).toLowerCase());
  }

  function resetErrors() {
    [nameError, emailError, messageError].forEach((el) => (el.textContent = ''));
    formSuccess.textContent = '';
  }

  contactForm.addEventListener('submit', (event) => {
    event.preventDefault();
    resetErrors();

    let isValid = true;
    if (!nameInput.value.trim()) {
      nameError.textContent = 'Please enter your name.';
      isValid = false;
    }
    if (!emailInput.value.trim()) {
      emailError.textContent = 'Please enter your email.';
      isValid = false;
    } else if (!isValidEmail(emailInput.value)) {
      emailError.textContent = 'Please enter a valid email address.';
      isValid = false;
    }
    if (!messageInput.value.trim()) {
      messageError.textContent = 'Please enter a message.';
      isValid = false;
    }

    if (!isValid) return;

    // Simulate successful submission
    formSuccess.textContent = 'Thanks! Your message has been sent.';
    contactForm.reset();
  });
}

// Skills page: tabs and progress animation
const tabButtons = document.querySelectorAll('.tab-button');
const tabPanels = document.querySelectorAll('.tab-panel');
if (tabButtons.length && tabPanels.length) {
  tabButtons.forEach((btn) => {
    btn.addEventListener('click', () => {
      const targetId = btn.getAttribute('aria-controls');
      // update tabs
      tabButtons.forEach((b) => {
        b.classList.toggle('active', b === btn);
        b.setAttribute('aria-selected', String(b === btn));
      });
      // update panels
      tabPanels.forEach((panel) => {
        const isTarget = panel.id === targetId;
        panel.classList.toggle('show', isTarget);
        panel.hidden = !isTarget;
      });
      // animate progress bars when panel shown
      animateVisibleProgress();
    });
  });

  function animateVisibleProgress() {
    document.querySelectorAll('.tab-panel.show .progress').forEach((bar) => {
      const span = bar.querySelector('span');
      const target = Number(bar.getAttribute('data-progress')) || 0;
      requestAnimationFrame(() => {
        span.style.width = target + '%';
      });
    });
  }

  // Trigger animation on load for default panel
  animateVisibleProgress();
}

// Skills page: metric counters
const metricNumbers = document.querySelectorAll('.metric-number');
if (metricNumbers.length) {
  const observer = new IntersectionObserver((entries, obs) => {
    entries.forEach((entry) => {
      if (entry.isIntersecting) {
        const el = entry.target;
        const target = Number(el.getAttribute('data-target')) || 0;
        const durationMs = 1200;
        const start = performance.now();
        const startVal = 0;
        function tick(now) {
          const progress = Math.min(1, (now - start) / durationMs);
          const value = Math.floor(startVal + progress * (target - startVal));
          el.textContent = String(value);
          if (progress < 1) requestAnimationFrame(tick);
        }
        requestAnimationFrame(tick);
        obs.unobserve(el);
      }
    });
  }, { threshold: 0.6 });

  metricNumbers.forEach((n) => observer.observe(n));
}
**#Services page

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Durga | Services</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">Durga<span>.</span></a>
      <nav class="site-nav" id="siteNav">
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="skills.html">Skills</a>
        <a href="services.html" class="active">Services</a>
        <a href="contact.html">Contact</a>
      </nav>
      <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation" aria-expanded="false">
        <span></span><span></span><span></span>
      </button>
    </div>
  </header>

  <main>
    <section class="page-hero small">
      <div class="container">
        <h1>Services</h1>
        <p>What I can do for your product and business.</p>
      </div>
    </section>

    <section class="services-content">
      <div class="container">
        <div class="skills-tabs" role="tablist" aria-label="Service categories">
          <button class="tab-button active" role="tab" aria-selected="true" aria-controls="panel-web" id="tab-web">Web</button>
          <button class="tab-button" role="tab" aria-selected="false" aria-controls="panel-design" id="tab-design">Design</button>
          <button class="tab-button" role="tab" aria-selected="false" aria-controls="panel-perf" id="tab-perf">Performance</button>
          <button class="tab-button" role="tab" aria-selected="false" aria-controls="panel-consult" id="tab-consult">Consulting</button>
        </div>

        <div class="tab-panel show" id="panel-web" role="tabpanel" aria-labelledby="tab-web">
          <div class="service-grid rich">
            <div class="service-card">
              <div class="service-icon">🖥️</div>
              <div class="skill-head"><h3>Web Development</h3><span class="badge">Core</span></div>
              <p>Responsive, accessible sites with clean, maintainable code.</p>
              <ul class="tags"><li>HTML</li><li>CSS</li><li>JS</li></ul>
            </div>
            <div class="service-card">
              <div class="service-icon">⚛️</div>
              <div class="skill-head"><h3>SPA Development</h3><span class="badge">Pro</span></div>
              <p>Building reactive UIs with modern frameworks and tooling.</p>
              <ul class="tags"><li>React</li><li>Routing</li><li>State</li></ul>
            </div>
            <div class="service-card">
              <div class="service-icon">🔐</div>
              <div class="skill-head"><h3>Best Practices</h3><span class="badge">QA</span></div>
              <p>Testing, code review, and healthy CI to ensure quality.</p>
              <ul class="tags"><li>Testing</li><li>CI</li><li>Git</li></ul>
            </div>
          </div>
        </div>

        <div class="tab-panel" id="panel-design" role="tabpanel" aria-labelledby="tab-design" hidden>
          <div class="service-grid rich">
            <div class="service-card">
              <div class="service-icon">🎨</div>
              <div class="skill-head"><h3>UI Implementation</h3><span class="badge">Pixel‑perfect</span></div>
              <p>Translating Figma into live, responsive, and accessible UI.</p>
              <ul class="tags"><li>Figma</li><li>Grid</li><li>Animation</li></ul>
            </div>
            <div class="service-card">
              <div class="service-icon">🧭</div>
              <div class="skill-head"><h3>UX Enhancements</h3><span class="badge">CX</span></div>
              <p>Micro-interactions and flows that guide users to success.</p>
              <ul class="tags"><li>Motion</li><li>IA</li><li>A11y</li></ul>
            </div>
            <div class="service-card">
              <div class="service-icon">🧩</div>
              <div class="skill-head"><h3>Design Systems</h3><span class="badge">Scale</span></div>
              <p>Reusable components and tokens for consistency and speed.</p>
              <ul class="tags"><li>Components</li><li>Tokens</li><li>Docs</li></ul>
            </div>
          </div>
        </div>

        <div class="tab-panel" id="panel-perf" role="tabpanel" aria-labelledby="tab-perf" hidden>
          <div class="service-grid rich">
            <div class="service-card">
              <div class="service-icon">⚙️</div>
              <div class="skill-head"><h3>Performance Audit</h3><span class="badge">LCP</span></div>
              <p>Diagnose bottlenecks and deliver a prioritized action plan.</p>
              <ul class="tags"><li>Lighthouse</li><li>CWV</li><li>Bundle</li></ul>
            </div>
            <div class="service-card">
              <div class="service-icon">⚡</div>
              <div class="skill-head"><h3>Optimization</h3><span class="badge">Speed</span></div>
              <p>Code-splitting, lazy loading, and asset optimization.</p>
              <ul class="tags"><li>Code Split</li><li>Lazy</li><li>Cache</li></ul>
            </div>
            <div class="service-card">
              <div class="service-icon">🔍</div>
              <div class="skill-head"><h3>Accessibility</h3><span class="badge">WCAG</span></div>
              <p>Inclusive experiences that meet accessibility standards.</p>
              <ul class="tags"><li>ARIA</li><li>Contrast</li><li>Keyboard</li></ul>
            </div>
          </div>
        </div>

        <div class="tab-panel" id="panel-consult" role="tabpanel" aria-labelledby="tab-consult" hidden>
          <div class="service-grid rich">
            <div class="service-card">
              <div class="service-icon">🧠</div>
              <div class="skill-head"><h3>Front-end Consulting</h3><span class="badge">Advisor</span></div>
              <p>Roadmapping, tech choices, and delivery guidance.</p>
              <ul class="tags"><li>Planning</li><li>Roadmap</li><li>Review</li></ul>
            </div>
            <div class="service-card">
              <div class="service-icon">🤝</div>
              <div class="skill-head"><h3>Team Enablement</h3><span class="badge">Mentor</span></div>
              <p>Mentoring and pairing to level-up delivery and practices.</p>
              <ul class="tags"><li>Mentor</li><li>Standards</li><li>Toolkit</li></ul>
            </div>
            <div class="service-card">
              <div class="service-icon">📈</div>
              <div class="skill-head"><h3>SEO Foundations</h3><span class="badge">Growth</span></div>
              <p>Technical SEO to help users and crawlers find your content.</p>
              <ul class="tags"><li>Meta</li><li>Sitemap</li><li>Structured Data</li></ul>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Durga. All rights reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

 # Skills page
 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Durga | Skills</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">Durga<span>.</span></a>
      <nav class="site-nav" id="siteNav">
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="skills.html" class="active">Skills</a>
        <a href="services.html">Services</a>
        <a href="contact.html">Contact</a>
      </nav>
      <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation" aria-expanded="false">
        <span></span><span></span><span></span>
      </button>
    </div>
  </header>

  <main>
    <section class="page-hero small">
      <div class="container">
        <h1>Skills</h1>
        <p>Tools and technologies I use to craft web experiences.</p>
      </div>
    </section>

    <section class="skills-content">
      <div class="container">
        <div class="skills-tabs" role="tablist" aria-label="Skill categories">
          <button class="tab-button active" role="tab" aria-selected="true" aria-controls="panel-frontend" id="tab-frontend">Front-end</button>
          <button class="tab-button" role="tab" aria-selected="false" aria-controls="panel-tools" id="tab-tools">Tools</button>
          <button class="tab-button" role="tab" aria-selected="false" aria-controls="panel-soft" id="tab-soft">Soft skills</button>
        </div>

        <div class="tab-panel show" id="panel-frontend" role="tabpanel" aria-labelledby="tab-frontend">
          <div class="skills-grid rich">
            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>HTML5</h3>
                <span class="badge">Expert</span>
              </div>
              <p class="skill-desc">Semantic, accessible markup and SEO-friendly structure.</p>
              <ul class="tags">
                <li>ARIA</li><li>SEO</li><li>Semantics</li>
              </ul>
              <div class="progress" data-progress="95"><span></span></div>
            </div>

            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>CSS3</h3>
                <span class="badge">Advanced</span>
              </div>
              <p class="skill-desc">Responsive layouts with Grid/Flexbox and modern theming.</p>
              <ul class="tags">
                <li>Grid</li><li>Flexbox</li><li>Animations</li>
              </ul>
              <div class="progress" data-progress="90"><span></span></div>
            </div>

            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>JavaScript</h3>
                <span class="badge">Advanced</span>
              </div>
              <p class="skill-desc">Modern ES features, modular code, and performance.</p>
              <ul class="tags">
                <li>ES6+</li><li>Modules</li><li>Performance</li>
              </ul>
              <div class="progress" data-progress="85"><span></span></div>
            </div>

            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>React</h3>
                <span class="badge">Proficient</span>
              </div>
              <p class="skill-desc">Component-driven UIs with hooks and state management.</p>
              <ul class="tags">
                <li>Hooks</li><li>SPA</li><li>State</li>
              </ul>
              <div class="progress" data-progress="80"><span></span></div>
            </div>
          </div>
        </div>

        <div class="tab-panel" id="panel-tools" role="tabpanel" aria-labelledby="tab-tools" hidden>
          <div class="skills-grid rich">
            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>Git & GitHub</h3>
                <span class="badge">Advanced</span>
              </div>
              <p class="skill-desc">Feature branches, PR reviews, and clean commit history.</p>
              <ul class="tags">
                <li>PRs</li><li>Rebase</li><li>Code Review</li>
              </ul>
              <div class="progress" data-progress="88"><span></span></div>
            </div>
            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>Webpack/Vite</h3>
                <span class="badge">Proficient</span>
              </div>
              <p class="skill-desc">Fast dev builds and optimized production bundles.</p>
              <ul class="tags">
                <li>HMR</li><li>Code Split</li><li>Minify</li>
              </ul>
              <div class="progress" data-progress="82"><span></span></div>
            </div>
            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>Testing</h3>
                <span class="badge">Proficient</span>
              </div>
              <p class="skill-desc">Unit and integration tests for critical flows.</p>
              <ul class="tags">
                <li>Jest</li><li>RTL</li><li>MSW</li>
              </ul>
              <div class="progress" data-progress="75"><span></span></div>
            </div>
          </div>
        </div>

        <div class="tab-panel" id="panel-soft" role="tabpanel" aria-labelledby="tab-soft" hidden>
          <div class="skills-grid rich">
            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>Communication</h3>
                <span class="badge">Strong</span>
              </div>
              <p class="skill-desc">Clear, concise updates and collaborative approach.</p>
              <ul class="tags">
                <li>Docs</li><li>Stakeholders</li><li>Teamwork</li>
              </ul>
              <div class="progress" data-progress="90"><span></span></div>
            </div>
            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>Problem Solving</h3>
                <span class="badge">Strong</span>
              </div>
              <p class="skill-desc">Breaking down complexity and delivering pragmatic solutions.</p>
              <ul class="tags">
                <li>Analysis</li><li>Debugging</li><li>Ownership</li>
              </ul>
              <div class="progress" data-progress="92"><span></span></div>
            </div>
            <div class="skill-card rich-card">
              <div class="skill-head">
                <h3>Leadership</h3>
                <span class="badge">Growing</span>
              </div>
              <p class="skill-desc">Mentoring and driving initiatives to completion.</p>
              <ul class="tags">
                <li>Mentorship</li><li>Planning</li><li>Quality</li>
              </ul>
              <div class="progress" data-progress="78"><span></span></div>
            </div>
          </div>
        </div>

        <div class="skill-metrics">
          <div class="metric">
            <span class="metric-number" data-target="5">0</span>
            <span class="metric-label">Years Experience</span>
          </div>
          <div class="metric">
            <span class="metric-number" data-target="40">0</span>
            <span class="metric-label">Projects</span>
          </div>
          <div class="metric">
            <span class="metric-number" data-target="20">0</span>
            <span class="metric-label">Happy Clients</span>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Durga. All rights reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

# css code
/*
  Durga Portfolio - Central Stylesheet
  Theme Colors: Deep Purple #6C63FF, Teal #00BFA6, Dark Navy #2C2C54, Light BG #F8F9FA
*/

:root {
  --color-primary: #6C63FF;
  --color-accent: #00BFA6;
  --color-navy: #2C2C54;
  --color-bg: #F8F9FA;
  --color-text: #1f2330;
  --color-muted: #6b7280;
  --radius: 14px;
  --radius-sm: 10px;
  --shadow-sm: 0 6px 20px rgba(0, 0, 0, 0.06);
  --shadow-md: 0 12px 32px rgba(0, 0, 0, 0.08);
}

/* Base */
html { scroll-behavior: smooth; }
* { box-sizing: border-box; }
body {
  margin: 0;
  font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  color: var(--color-text);
  background: var(--color-bg);
  line-height: 1.6;
}

img { max-width: 100%; height: auto; display: block; }
a { color: inherit; text-decoration: none; }

.container {
  width: min(1120px, 92%);
  margin-inline: auto;
}

/* Header & Navigation */
.site-header {
  position: sticky; top: 0; z-index: 10;
  background: #fff;
  border-bottom: 1px solid rgba(44, 44, 84, 0.06);
  backdrop-filter: blur(10px);
}
.nav-container {
  display: grid; grid-template-columns: auto 1fr auto; align-items: center;
  gap: 16px; padding: 14px 0;
}
.brand { font-weight: 800; font-size: 1.25rem; color: var(--color-navy); letter-spacing: 0.3px; }
.brand span { color: var(--color-primary); }

.site-nav { display: flex; gap: 20px; justify-content: center; }
.site-nav a {
  padding: 10px 14px; border-radius: 10px; color: var(--color-navy); font-weight: 600;
  transition: background 0.2s ease, color 0.2s ease, transform 0.2s ease;
}
.site-nav a:hover { background: rgba(108, 99, 255, 0.1); transform: translateY(-1px); }
.site-nav a.active { color: #fff; background: var(--color-primary); box-shadow: var(--shadow-sm); }

.nav-toggle { display: none; width: 44px; height: 44px; border-radius: 12px; border: 1px solid rgba(0,0,0,0.08); background: #fff; align-items: center; justify-content: center; gap: 4px; }
.nav-toggle span { width: 20px; height: 2px; background: var(--color-navy); display: block; border-radius: 2px; }

/* Hero */
.hero { padding: 72px 0 40px; background: linear-gradient(180deg, #ffffff 0%, #f3f5ff 100%); }
.hero-grid { display: grid; grid-template-columns: 1.15fr 0.85fr; align-items: center; gap: 32px; }
.eyebrow { color: var(--color-accent); font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase; margin: 0 0 8px; }
.hero h1 { font-size: clamp(2rem, 4vw, 3rem); line-height: 1.1; margin: 0 0 8px; color: var(--color-navy); }
.profession { margin: 0 0 14px; color: var(--color-primary); font-weight: 700; }
.subtitle { color: var(--color-muted); max-width: 52ch; }
.hero-actions { display: flex; gap: 12px; margin-top: 22px; }
.hero-media { filter: drop-shadow(var(--shadow-sm)); }
.hero-badges { display: flex; gap: 8px; list-style: none; padding: 0; margin: 18px 0 8px; }
.hero-badges li { background: #f0f3fb; color: #3c3f55; padding: 6px 10px; border-radius: 999px; font-size: 12px; font-weight: 700; }
.social-links { display: flex; gap: 10px; }
.social-links a { width: 36px; height: 36px; display: grid; place-items: center; border: 1px solid #e6e8ef; border-radius: 10px; transition: background .2s ease, transform .2s ease; }
.social-links a:hover { background: rgba(108,99,255,0.08); transform: translateY(-2px); }

/* Page Hero */
.page-hero.small { padding: 56px 0 20px; text-align: left; background: linear-gradient(180deg, #ffffff 0%, #f3f5ff 100%); }
.page-hero h1 { margin: 0 0 6px; color: var(--color-navy); }
.page-hero p { margin: 0; color: var(--color-muted); }

/* Sections */
.featured { padding: 32px 0 64px; }
.features { display: grid; grid-template-columns: repeat(4, 1fr); gap: 18px; }
.feature-card { background: #fff; padding: 20px; border-radius: var(--radius); box-shadow: var(--shadow-sm); transition: transform .2s ease, box-shadow .2s ease; }
.feature-card:hover { transform: translateY(-6px); box-shadow: var(--shadow-md); }
.feature-card .icon { font-size: 24px; }

/* About */
.about-content { padding: 36px 0 72px; }
.about-grid { display: grid; grid-template-columns: 0.9fr 1.1fr; gap: 28px; align-items: center; }
.about-media img { border-radius: var(--radius); box-shadow: var(--shadow-sm); }
.about-text h2 { margin-top: 0; color: var(--color-navy); }
.about-highlights { padding-left: 18px; color: var(--color-muted); }

/* Skills */
.skills-content { padding: 24px 0 72px; }
.skills-tabs { display: inline-flex; gap: 8px; background: #fff; padding: 8px; border-radius: 12px; box-shadow: var(--shadow-sm); margin-bottom: 16px; }
.tab-button { padding: 10px 14px; border-radius: 10px; border: 1px solid transparent; background: transparent; font-weight: 700; color: var(--color-navy); cursor: pointer; }
.tab-button:hover { background: rgba(108,99,255,0.08); }
.tab-button.active { background: var(--color-primary); color: #fff; box-shadow: var(--shadow-sm); }
.tab-panel { display: none; }
.tab-panel.show { display: block; animation: fadeIn .3s ease; }

.skills-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 18px; }
.skills-grid.rich .rich-card { display: grid; gap: 10px; }
.skill-card { background: #fff; padding: 18px; border-radius: var(--radius); box-shadow: var(--shadow-sm); transition: transform .2s ease, box-shadow .2s ease; }
.skill-card:hover { transform: translateY(-4px); box-shadow: var(--shadow-md); }
.skill-head { display: flex; align-items: center; justify-content: space-between; gap: 12px; }
.badge { background: rgba(108,99,255,0.12); color: var(--color-primary); border: 1px solid rgba(108,99,255,0.3); padding: 4px 8px; border-radius: 999px; font-size: 12px; font-weight: 700; }
.skill-desc { margin: 0; color: var(--color-muted); }
.tags { display: flex; flex-wrap: wrap; gap: 8px; padding: 0; margin: 0; list-style: none; }
.tags li { background: #f0f3fb; color: #3c3f55; padding: 4px 8px; border-radius: 999px; font-size: 12px; }
.progress { background: #eef1f7; border-radius: 999px; height: 10px; overflow: hidden; position: relative; }
.progress span { display: block; height: 100%; width: 0; background: linear-gradient(90deg, var(--color-primary), var(--color-accent)); border-radius: inherit; box-shadow: inset 0 0 10px rgba(0,0,0,0.06); transition: width 1s ease; }

.skill-metrics { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; margin-top: 20px; }
.metric { background: #fff; padding: 16px; border-radius: var(--radius); box-shadow: var(--shadow-sm); text-align: center; }
.metric-number { display: block; font-size: 28px; font-weight: 800; color: var(--color-navy); }
.metric-label { color: var(--color-muted); font-weight: 600; }

@keyframes fadeIn { from { opacity: 0; transform: translateY(6px); } to { opacity: 1; transform: none; } }

/* Services */
.services-content { padding: 24px 0 72px; }
.service-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 18px; }
.service-grid.rich { grid-template-columns: repeat(3, 1fr); }
.service-card { background: #fff; padding: 20px; border-radius: var(--radius); box-shadow: var(--shadow-sm); transition: transform .2s ease, box-shadow .2s ease; display: grid; gap: 10px; }
.service-card:hover { transform: translateY(-6px); box-shadow: var(--shadow-md); }
.service-icon { font-size: 28px; }

/* Contact */
.contact-content { padding: 24px 0 72px; }
.contact-grid { display: grid; grid-template-columns: 0.9fr 1.1fr; gap: 24px; align-items: start; }
.contact-info h2 { margin-top: 0; color: var(--color-navy); }
.contact-list { color: var(--color-muted); padding-left: 18px; }
.info-cards { display: grid; grid-template-columns: 1fr; gap: 10px; margin: 10px 0 14px; }
.info-card { display: grid; grid-template-columns: auto 1fr; align-items: center; gap: 10px; background: #fff; padding: 12px; border-radius: var(--radius); box-shadow: var(--shadow-sm); }
.faq { background: #fff; border-radius: var(--radius); padding: 10px 12px; box-shadow: var(--shadow-sm); margin: 8px 0; }
.faq summary { cursor: pointer; font-weight: 700; color: var(--color-navy); }
.faq p { color: var(--color-muted); margin: 8px 0 0; }
.contact-form { background: #fff; padding: 20px; border-radius: var(--radius); box-shadow: var(--shadow-sm); }
.form-field { display: grid; gap: 8px; margin-bottom: 14px; }
label { font-weight: 600; color: var(--color-navy); }
input, textarea {
  width: 100%; padding: 12px 14px; border: 1px solid #e5e7eb; border-radius: var(--radius-sm);
  font: inherit; background: #fff; transition: border-color .2s ease, box-shadow .2s ease;
}
input:focus, textarea:focus { outline: none; border-color: var(--color-primary); box-shadow: 0 0 0 4px rgba(108, 99, 255, 0.15); }
.error { color: #b00020; min-height: 16px; }
.form-success { color: var(--color-accent); font-weight: 600; min-height: 20px; }

/* Footer */
.site-footer { border-top: 1px solid rgba(44, 44, 84, 0.06); padding: 20px 0; color: var(--color-muted); background: #fff; }

/* Buttons */
.btn { display: inline-flex; align-items: center; justify-content: center; gap: 8px; padding: 12px 16px; border-radius: 12px; font-weight: 700; border: 1px solid transparent; transition: transform .2s ease, box-shadow .2s ease, background .2s ease, color .2s ease; }
.btn-primary { background: var(--color-primary); color: #fff; box-shadow: var(--shadow-sm); }
.btn-primary:hover { transform: translateY(-2px); box-shadow: var(--shadow-md); }
.btn-outline { background: transparent; color: var(--color-primary); border-color: rgba(108,99,255,0.4); }
.btn-outline:hover { background: rgba(108,99,255,0.08); }

/* Responsive */
@media (max-width: 980px) {
  .hero-grid, .about-grid, .contact-grid { grid-template-columns: 1fr; }
  .service-grid { grid-template-columns: repeat(2, 1fr); }
  .skills-grid { grid-template-columns: repeat(2, 1fr); }
}

@media (max-width: 720px) {
  .site-nav { display: none; position: absolute; top: 64px; left: 0; right: 0; background: #fff; padding: 12px; box-shadow: var(--shadow-md); border-top: 1px solid rgba(0,0,0,0.06); }
  .site-nav.open { display: grid; gap: 8px; }
  .nav-toggle { display: inline-flex; }
  .service-grid { grid-template-columns: 1fr; }
  .skills-grid { grid-template-columns: 1fr; }
  .features { grid-template-columns: 1fr; }
}




