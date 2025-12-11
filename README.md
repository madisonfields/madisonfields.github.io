<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Madison Fields – SEO & AEO (GEO) Consultant</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta
    name="description"
    content="Portfolio of Madison Fields, SEO & AEO (GEO) Consultant and SEO & Content Manager with a background in cultural anthropology, specializing in organic growth, AI Overviews, and mission-driven organizations."
  />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap"
    rel="stylesheet"
  />
  <style>
    :root {
      --bg: #f6f4f0;
      --bg-alt: #ffffff;
      --text: #1f2933;
      --muted: #6b7280;
      --accent: #136f63;
      --accent-soft: #d3ebe5;
      --border: #e5e7eb;
      --shadow-soft: 0 18px 40px rgba(15, 23, 42, 0.08);
      --radius-xl: 18px;
      --radius-pill: 999px;
      --max-width: 1040px;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "Inter", system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
      background: radial-gradient(circle at top left, #f0f5f3 0, var(--bg) 45%);
      color: var(--text);
      line-height: 1.6;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    img {
      max-width: 100%;
      display: block;
    }

    .page {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 24px 16px 40px;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 24px;
      gap: 12px;
    }

    .logo {
      font-weight: 700;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      font-size: 0.9rem;
      padding: 6px 14px;
      border-radius: var(--radius-pill);
      background: rgba(255, 255, 255, 0.9);
      border: 1px solid rgba(148, 163, 184, 0.4);
      box-shadow: 0 10px 30px rgba(15, 23, 42, 0.06);
    }

    nav {
      display: flex;
      gap: 16px;
      font-size: 0.9rem;
    }

    nav a {
      padding: 6px 10px;
      border-radius: var(--radius-pill);
      color: var(--muted);
      transition: background 0.2s ease, color 0.2s ease;
    }

    nav a:hover {
      background: rgba(255, 255, 255, 0.9);
      color: var(--text);
    }

    .hero {
      display: grid;
      gap: 32px;
      grid-template-columns: minmax(0, 1.3fr) minmax(0, 1fr);
      align-items: center;
      margin: 10px 0 40px;
    }

    .hero-text {
      padding: 22px 22px 24px;
      border-radius: 26px;
      background: rgba(255, 255, 255, 0.9);
      border: 1px solid rgba(209, 213, 219, 0.7);
      box-shadow: var(--shadow-soft);
    }

    .hero-tag {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 4px 12px;
      border-radius: var(--radius-pill);
      background: var(--accent-soft);
      color: var(--accent);
      font-size: 0.75rem;
      font-weight: 500;
      margin-bottom: 10px;
    }

    .hero-tag span.dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background: #2dd4bf;
      box-shadow: 0 0 0 4px rgba(45, 212, 191, 0.2);
    }

    .hero h1 {
      font-size: 2rem;
      line-height: 1.2;
      margin-bottom: 10px;
    }

    .hero-subtitle {
      font-size: 0.98rem;
      color: var(--muted);
      margin-bottom: 18px;
    }

    .hero-highlight {
      font-size: 0.95rem;
      padding: 10px 12px;
      border-radius: 14px;
      background: #f3f4ff;
      border: 1px dashed #c7cffd;
      margin-bottom: 18px;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      align-items: center;
    }

    .btn-primary {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      padding: 9px 16px;
      border-radius: var(--radius-pill);
      background: linear-gradient(135deg, #0f766e, #14b8a6);
      color: #ffffff;
      font-size: 0.92rem;
      font-weight: 600;
      border: none;
      cursor: pointer;
      box-shadow: 0 15px 30px rgba(15, 118, 110, 0.35);
      transition: transform 0.12s ease, box-shadow 0.12s ease, opacity 0.15s ease;
    }

    .btn-primary:hover {
      transform: translateY(-1px);
      box-shadow: 0 20px 40px rgba(15, 118, 110, 0.4);
      opacity: 0.95;
    }

    .btn-secondary {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      padding: 9px 14px;
      border-radius: var(--radius-pill);
      background: transparent;
      border: 1px solid var(--border);
      font-size: 0.9rem;
      color: var(--muted);
      cursor: pointer;
      transition: background 0.15s ease, color 0.15s ease, border-color 0.15s ease;
    }

    .btn-secondary:hover {
      background: #ffffff;
      border-color: #cbd5f5;
      color: var(--text);
    }

    .hero-badges {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
      margin-top: 10px;
      font-size: 0.75rem;
      color: var(--muted);
    }

    .hero-badges span {
      padding: 4px 10px;
      border-radius: var(--radius-pill);
      border: 1px solid rgba(209, 213, 219, 0.9);
      background: #f9fafb;
    }

    .hero-aside {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .profile-card {
      border-radius: 24px;
      padding: 20px;
      background: linear-gradient(145deg, #0f172a, #064e3b);
      color: #e5e7eb;
      box-shadow: var(--shadow-soft);
      position: relative;
      overflow: hidden;
    }

    .profile-card::after {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at top right, rgba(248, 250, 252, 0.12), transparent 55%);
      mix-blend-mode: screen;
      pointer-events: none;
    }

    /* Headshot styles */
    .avatar-photo {
      width: 88px;
      height: 88px;
      border-radius: 24px;
      overflow: hidden;
      border: 2px solid rgba(248, 250, 252, 0.8);
      box-shadow: 0 6px 16px rgba(15, 23, 42, 0.35);
      margin-bottom: 10px;
    }

    .avatar-photo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .profile-name {
      font-weight: 600;
      margin-bottom: 2px;
    }

    .profile-role {
      font-size: 0.8rem;
      color: #cbd5f5;
      margin-bottom: 14px;
    }

    .profile-meta {
      display: grid;
      gap: 10px;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      font-size: 0.8rem;
    }

    .profile-meta div {
      padding: 8px 10px;
      border-radius: 12px;
      background: rgba(15, 23, 42, 0.55);
      border: 1px solid rgba(148, 163, 184, 0.4);
    }

    .profile-meta span.label {
      display: block;
      font-size: 0.7rem;
      text-transform: uppercase;
      letter-spacing: 0.06em;
      color: #a5b4fc;
      margin-bottom: 3px;
    }

    .availability-tag {
      margin-top: 12px;
      padding: 7px 10px;
      border-radius: 999px;
      background: rgba(22, 163, 74, 0.1);
      border: 1px solid rgba(22, 163, 74, 0.5);
      color: #bbf7d0;
      font-size: 0.75rem;
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }

    .availability-tag-dot {
      width: 8px;
      height: 8px;
      border-radius: 999px;
      background: #22c55e;
      box-shadow: 0 0 0 4px rgba(34, 197, 94, 0.3);
    }

    .note-card {
      border-radius: 18px;
      padding: 14px 14px 14px;
      background: rgba(255, 255, 255, 0.92);
      border: 1px solid rgba(209, 213, 219, 0.8);
      font-size: 0.82rem;
      color: var(--muted);
    }

    section {
      margin-bottom: 36px;
    }

    .section-header {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      gap: 10px;
      margin-bottom: 16px;
    }

    .section-title {
      font-size: 1.15rem;
      font-weight: 600;
    }

    .section-kicker {
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--muted);
    }

    .section-subtitle {
      font-size: 0.85rem;
      color: var(--muted);
    }

    .about-grid {
      display: grid;
      gap: 18px;
      grid-template-columns: minmax(0, 1.3fr) minmax(0, 1fr);
    }

    .card {
      background: var(--bg-alt);
      border-radius: var(--radius-xl);
      border: 1px solid var(--border);
      padding: 18px 18px 20px;
      box-shadow: 0 16px 30px rgba(15, 23, 42, 0.02);
      font-size: 0.92rem;
    }

    .card p + p {
      margin-top: 10px;
    }

    .pill-row {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 10px;
      font-size: 0.8rem;
    }

    .pill-row span {
      padding: 5px 10px;
      border-radius: 999px;
      background: #f3f4f6;
      border: 1px solid #e5e7eb;
    }

    .skills-grid {
      display: grid;
      gap: 14px;
      grid-template-columns: repeat(3, minmax(0, 1fr));
    }

    .skills-card h3 {
      font-size: 0.95rem;
      margin-bottom: 6px;
    }

    .skills-card ul {
      list-style: none;
      font-size: 0.8rem;
      color: var(--muted);
      padding-left: 0;
    }

    .skills-card li {
      margin-bottom: 4px;
    }

    .portfolio-grid {
      display: grid;
      gap: 16px;
      grid-template-columns: repeat(3, minmax(0, 1fr));
    }

    .portfolio-item h3 {
      font-size: 0.92rem;
      margin-bottom: 4px;
    }

    .portfolio-meta {
      font-size: 0.78rem;
      color: var(--muted);
      margin-bottom: 8px;
    }

    .portfolio-item p {
      font-size: 0.8rem;
      color: var(--muted);
    }

    .services-grid {
      display: grid;
      gap: 14px;
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }

    .services-card h3 {
      font-size: 0.95rem;
      margin-bottom: 4px;
    }

    .services-card p {
      font-size: 0.83rem;
      color: var(--muted);
    }

    .contact {
      display: grid;
      gap: 18px;
      grid-template-columns: minmax(0, 1.1fr) minmax(0, 1fr);
      align-items: flex-start;
    }

    form {
      display: grid;
      gap: 10px;
      font-size: 0.88rem;
    }

    label {
      font-size: 0.8rem;
      font-weight: 500;
    }

    input,
    textarea {
      width: 100%;
      padding: 8px 10px;
      border-radius: 10px;
      border: 1px solid #d1d5db;
      background: #ffffff;
      font-family: inherit;
      font-size: 0.88rem;
      resize: vertical;
      min-height: 42px;
    }

    textarea {
      min-height: 90px;
    }

    input:focus,
    textarea:focus {
      outline: 2px solid rgba(56, 189, 248, 0.6);
      border-color: #38bdf8;
      background: #ffffff;
    }

    footer {
      margin-top: 26px;
      padding-top: 18px;
      border-top: 1px solid #e5e7eb;
      font-size: 0.78rem;
      color: var(--muted);
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 8px;
    }

    footer a {
      text-decoration: underline;
      text-decoration-thickness: 1px;
    }

    @media (max-width: 880px) {
      .hero {
        grid-template-columns: 1fr;
      }
      .hero-aside {
        order: -1;
      }
      .about-grid,
      .skills-grid,
      .portfolio-grid,
      .services-grid,
      .contact {
        grid-template-columns: 1fr;
      }
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      nav {
        flex-wrap: wrap;
      }
    }

    @media (max-width: 520px) {
      .hero h1 {
        font-size: 1.6rem;
      }
      .page {
        padding-inline: 14px;
      }
      .hero-text {
        padding: 18px 16px 18px;
      }
    }
  </style>
</head>
<body>
  <div class="page">
    <header>
      <div class="logo">MADISON FIELDS</div>
      <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#work">Work</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <!-- HERO -->
    <main>
      <section class="hero" aria-labelledby="hero-heading">
        <div class="hero-text">
          <div class="hero-tag">
            <span class="dot"></span>
            <span>SEO · AEO (GEO) · Content Strategy</span>
          </div>
          <h1 id="hero-heading">
            SEO &amp; AEO (GEO) Consultant<br />
            for human-centered, discoverable content
          </h1>
          <p class="hero-subtitle">
            I help brands and mission-driven teams grow organically across search and emerging answer engines, blending
            technical SEO, AEO, and content strategy with a background in cultural anthropology.
          </p>
          <div class="hero-highlight">
            With 5+ years in digital and content marketing, I’ve led SEO strategy across 70+ clients, from global software
            companies to local service brands—improving visibility, engagement, and revenue through data-driven, people-first
            experiences.
          </div>
          <div class="hero-actions">
            <a href="#contact" class="btn-primary">
              Let’s work together
              <span aria-hidden="true">↗</span>
            </a>
            <a href="#work" class="btn-secondary">View selected work</a>
          </div>
          <div class="hero-badges">
            <span>SEO &amp; AEO (GEO) consulting</span>
            <span>Content &amp; information architecture</span>
            <span>AI Overviews &amp; SERP research</span>
            <span>Anthropology-informed insight</span>
          </div>
        </div>

        <aside class="hero-aside" aria-label="Profile summary">
          <div class="profile-card">
            <div class="avatar-photo">
              <img src="Headshot.jpeg" alt="Madison Fields smiling and holding a coffee mug" />
            </div>
            <div class="profile-name">Madison Fields</div>
            <div class="profile-role">
              SEO &amp; AEO (GEO) Consultant · SEO &amp; Content Manager
            </div>
            <div class="profile-meta">
              <div>
                <span class="label">Based in</span>
                <div>The Netherlands · working remotely worldwide</div>
              </div>
              <div>
                <span class="label">Background</span>
                <div>BA in Cultural Anthropology (Honors), Louisiana State University</div>
              </div>
            </div>
            <div class="availability-tag">
              <span class="availability-tag-dot"></span>
              <span>Open to consulting, remote roles &amp; nonprofit collaborations</span>
            </div>
          </div>

          <div class="note-card">
            I specialize in translating complex SEO and AEO signals into clear, prioritized actions for teams. My experience
            spans large client portfolios, technical audits, BOFU content, and emerging AI-driven SERP changes—always with a
            focus on thoughtful, accessible communication.
          </div>
        </aside>
      </section>

      <!-- ABOUT -->
      <section id="about">
        <div class="section-header">
          <div>
            <div class="section-kicker">About</div>
            <h2 class="section-title">Strategic SEO rooted in research &amp; real people</h2>
          </div>
          <p class="section-subtitle">
            Bringing together anthropology, SEO, AEO, and content strategy to build sustainable organic growth.
          </p>
        </div>

        <div class="about-grid">
          <article class="card">
            <p>
              I’m an SEO &amp; AEO (GEO) Consultant and SEO &amp; Content Manager with 5+ years of experience driving organic
              growth for agencies, SaaS, and service-based brands. I’ve managed portfolios of up to 60 clients at once,
              balancing technical optimization, strategic content, and stakeholder communication.
            </p>
            <p>
              My academic background is in cultural anthropology, which means I’m trained to look beyond keywords and think
              about context: how people search, what they value, and how they actually move through digital experiences.
              That lens helps me design strategies that work for both algorithms and humans.
            </p>
            <p>
              I’m especially interested in supporting nonprofits, social enterprises, and globally minded organizations that
              care about inclusion, accessibility, and long-term impact—not just quick wins.
            </p>
          </article>

          <aside class="card">
            <p><strong>My experience in numbers</strong></p>
            <ul style="margin-top: 6px; padding-left: 18px; font-size: 0.85rem; color: var(--muted);">
              <li>5+ years in digital and content marketing</li>
              <li>3 years leading SEO strategy as an SEO Manager</li>
              <li>200+ high-intent service pages written and optimized</li>
              <li>200+ SEO audits delivered for growth and performance</li>
              <li>Average 25% MoM organic traffic growth across key projects</li>
              <li>10+ tools mastered, including GA4, GSC, Ahrefs, SEMrush, Moz &amp; Screaming Frog</li>
            </ul>
            <div class="pill-row">
              <span>Evidence-based</span>
              <span>Inclusive</span>
              <span>Collaborative</span>
              <span>Systems thinker</span>
            </div>
          </aside>
        </div>
      </section>

      <!-- SKILLS -->
      <section id="skills">
        <div class="section-header">
          <div>
            <div class="section-kicker">Skills</div>
            <h2 class="section-title">How I create value</h2>
          </div>
        </div>

        <div class="skills-grid">
          <article class="card skills-card">
            <h3>SEO &amp; AEO (GEO)</h3>
            <ul>
              <li>End-to-end SEO strategy for multi-client portfolios</li>
              <li>Technical audits &amp; site health monitoring</li>
              <li>Keyword &amp; SERP analysis, including AI Overviews &amp; LLM-generated content impact</li>
              <li>On-page optimization &amp; internal linking</li>
              <li>Local &amp; GEO-focused visibility improvements</li>
            </ul>
          </article>

          <article class="card skills-card">
            <h3>Content &amp; Experience</h3>
            <ul>
              <li>BOFU service page creation and optimization at scale</li>
              <li>Content roadmaps aligned with business goals</li>
              <li>UX collaboration for IA, navigation &amp; readability</li>
              <li>A/B testing mindset &amp; experimentation</li>
              <li>Inclusive, brand-aligned messaging frameworks</li>
            </ul>
          </article>

          <article class="card skills-card">
            <h3>Analytics, Tools &amp; Communication</h3>
            <ul>
              <li>Google Analytics 4 (GA4) &amp; Google Search Console</li>
              <li>Ahrefs, SEMrush, Moz, Screaming Frog &amp; Looker Studio</li>
              <li>Excel for performance tracking &amp; reporting</li>
              <li>Clear stakeholder reporting &amp; education</li>
              <li>Cross-functional collaboration with dev, product &amp; content teams</li>
            </ul>
          </article>
        </div>

        <div class="card" style="margin-top:14px;">
          <p><strong>Professional certifications</strong></p>
          <div class="pill-row">
            <span>Google Analytics 4 (GA4)</span>
            <span>Moz SEO Essentials</span>
            <span>SEMrush SEO Fundamentals &amp; International SEO</span>
            <span>Ahrefs SEO Training Course</span>
            <span>Excel Skills for Business</span>
          </div>
        </div>
      </section>

      <!-- WORK / PORTFOLIO -->
      <section id="work">
        <div class="section-header">
          <div>
            <div class="section-kicker">Selected work</div>
            <h2 class="section-title">Sample projects &amp; impact</h2>
          </div>
          <p class="section-subtitle">
            A few representative roles and outcomes. More detail available on request.
          </p>
        </div>

        <div class="portfolio-grid">
          <article class="card portfolio-item">
            <h3>Senior SEO Consultant – Global industrial software (PTC)</h3>
            <div class="portfolio-meta">2025 · Boston, MA (Remote) · Contractor</div>
            <p>
              Partnered with a global provider of industrial and digital transformation software to evaluate how AI
              Overviews, LLM-driven results, and changing SERPs affect core product and solution pages. Led SERP and keyword
              research, then collaborated with product and content teams to create future-proof SEO strategies for high-value
              pages.
            </p>
          </article>

          <article class="card portfolio-item">
            <h3>SEO Manager – Franchise marketing (Scorpion)</h3>
            <div class="portfolio-meta">2021–2025 · Remote</div>
            <p>
              Managed a 60-client portfolio generating $90K+ in monthly revenue for a leading franchise-focused digital
              marketing company. Built and executed data-driven SEO strategies, conducted market and competitor analysis, and
              aligned organic efforts with client positioning and growth goals, with a focus on inclusive and differentiated
              content.
            </p>
          </article>

          <article class="card portfolio-item">
            <h3>SEO Analyst – Automotive &amp; legal (Click Here Digital)</h3>
            <div class="portfolio-meta">2020–2021 · Baton Rouge, LA</div>
            <p>
              Led SEO for a 17-client portfolio in automotive and legal verticals at a long-standing digital agency. Campaigns
              generated over $28,883 in monthly revenue by improving organic visibility, rankings, and lead generation through
              targeted technical and content optimizations.
            </p>
          </article>
        </div>
      </section>

      <!-- SERVICES -->
      <section id="services">
        <div class="section-header">
          <div>
            <div class="section-kicker">How we can work together</div>
            <h2 class="section-title">Consulting &amp; collaboration</h2>
          </div>
        </div>

        <div class="services-grid">
          <article class="card services-card">
            <h3>SEO &amp; AEO (GEO) Audits</h3>
            <p>
              Holistic audits that look at technical health, content performance, site architecture, and how your brand shows
              up in both traditional search and AI-generated answer experiences. Delivered as a clear, actionable roadmap.
            </p>
          </article>

          <article class="card services-card">
            <h3>Content &amp; Conversion Strategy</h3>
            <p>
              Development of BOFU service pages, resource hubs, and content plans that meet user intent, support sales or
              fundraising goals, and reflect your brand’s voice and values.
            </p>
          </article>

          <article class="card services-card">
            <h3>Ongoing SEO Management</h3>
            <p>
              Retainer-style support for brands that need consistent optimization, reporting, and experimentation—ideal for
              marketing teams that want a dedicated organic growth partner.
            </p>
          </article>

          <article class="card services-card">
            <h3>Support for nonprofits &amp; social impact teams</h3>
            <p>
              Consulting for nonprofits, NGOs, and community-focused organizations looking to clarify their information
              architecture, improve discoverability, and make their digital presence more accessible. I’m open to scoped
              projects and flexible engagement models.
            </p>
          </article>
        </div>
      </section>

      <!-- CONTACT -->
      <section id="contact">
        <div class="section-header">
          <div>
            <div class="section-kicker">Contact</div>
            <h2 class="section-title">Let’s start a conversation</h2>
          </div>
          <p class="section-subtitle">
            Share a bit about your organization, goals, or challenges. I’ll follow up with ways we can work together.
          </p>
        </div>

        <div class="contact">
          <div class="card">
            <form action="mailto:fieldsmadisone@gmail.com" method="post" enctype="text/plain">
              <div>
                <label for="name">Name</label>
                <input id="name" name="name" type="text" placeholder="Your name" required />
              </div>
              <div>
                <label for="email">Email</label>
                <input id="email" name="email" type="email" placeholder="you@example.org" required />
              </div>
              <div>
                <label for="org">Organization (optional)</label>
                <input id="org" name="organization" type="text" placeholder="Organization / team / project" />
              </div>
              <div>
                <label for="message">How can I help?</label>
                <textarea
                  id="message"
                  name="message"
                  placeholder="Tell me a bit about your goals, challenges, or project idea."
                  required
                ></textarea>
              </div>
              <button type="submit" class="btn-primary" style="margin-top: 6px; width: fit-content;">
                Send message
              </button>
            </form>
          </div>

          <aside class="card" style="font-size: 0.85rem;">
            <p><strong>Other ways to reach me</strong></p>
            <p style="margin-top: 6px;">
              Email: <a href="mailto:fieldsmadisone@gmail.com">fieldsmadisone@gmail.com</a><br />
              Phone: <a href="tel:+12256208501">+1 225 620 8501</a><br />
              LinkedIn:
              <a href="https://www.linkedin.com/in/madison-fields-/" target="_blank" rel="noreferrer">
                linkedin.com/in/madison-fields-/
              </a>
            </p>
            <p style="margin-top: 10px;">
              I’m especially glad to hear from:
            </p>
            <ul style="margin-top: 6px; padding-left: 18px;">
              <li>Nonprofits, NGOs &amp; cultural institutions</li>
              <li>SaaS &amp; B2B brands navigating AI-driven search changes</li>
              <li>Agencies seeking senior SEO &amp; AEO support</li>
              <li>Collaborators on research-based or community projects</li>
            </ul>
          </aside>
        </div>
      </section>
    </main>

    <footer>
      <div>© <span id="year"></span> Madison Fields. All rights reserved.</div>
      <div>Built with care for people, search, and the next wave of answer engines.</div>
    </footer>
  </div>

  <script>
    // Set current year automatically
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
