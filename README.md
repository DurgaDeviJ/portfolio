# about page

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

# Contact page

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Durga | Contact</title>
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
        <a href="services.html">Services</a>
        <a href="contact.html" class="active">Contact</a>
      </nav>
      <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation" aria-expanded="false">
        <span></span><span></span><span></span>
      </button>
    </div>
  </header>

  <main>
    <section class="page-hero small">
      <div class="container">
        <h1>Contact</h1>
        <p>Have a project in mind? Let's talk.</p>
      </div>
    </section>

    <section class="contact-content">
      <div class="container contact-grid">
        <div class="contact-info">
          <h2>Get in touch</h2>
          <p>Fill out the form and I’ll get back to you within 24–48 hours.</p>
          <div class="info-cards">
            <div class="info-card">
              <div class="service-icon">✉️</div>
              <div>
                <h3>Email</h3>
                <p><a href="mailto:hello@example.com">hello@example.com</a></p>
              </div>
            </div>
            <div class="info-card">
              <div class="service-icon">📱</div>
              <div>
                <h3>Social</h3>
                <p>
                  <a href="#">LinkedIn</a> · <a href="#">GitHub</a>
                </p>
              </div>
            </div>
            <div class="info-card">
              <div class="service-icon">📍</div>
              <div>
                <h3>Location</h3>
                <p>Remote · Open to relocate</p>
              </div>
            </div>
          </div>
          <details class="faq">
            <summary>Do you take freelance work?</summary>
            <p>Yes. I’m available for select freelance and contract projects.</p>
          </details>
          <details class="faq">
            <summary>What is your typical response time?</summary>
            <p>Within 24–48 hours on weekdays.</p>
          </details>
        </div>
        <form class="contact-form" id="contactForm" novalidate>
          <div class="form-field">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" placeholder="Your name" required>
            <small class="error" id="nameError"></small>
          </div>
          <div class="form-field">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="you@example.com" required>
            <small class="error" id="emailError"></small>
          </div>
          <div class="form-field">
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" placeholder="How can I help?" required></textarea>
            <small class="error" id="messageError"></small>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
          <p class="form-success" id="formSuccess" role="status" aria-live="polite"></p>
        </form>
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

# Home page

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

# Services page

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






