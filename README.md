<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>[Your Name] – SEO Analyst & Project Manager</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta
    name="description"
    content="Portfolio of [Your Name], an SEO analyst and project manager with an anthropology background, supporting purpose-driven and nonprofit organizations."
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

    .avatar-placeholder {
      width: 56px;
      height: 56px;
      border-radius: 18px;
      border: 1px solid rgba(148, 163, 184, 0.5);
      background: linear-gradient(145deg, rgba(15, 23, 42, 0.2), rgba(148, 163, 184, 0.2));
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 600;
      font-size: 1.4rem;
      margin-bottom: 10px;
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
      <div class="logo">[YOUR NAME]</div>
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
            <span>SEO · Project Management · Anthropology</span>
          </div>
          <h1 id="hero-heading">
            SEO Analyst &amp; Project Manager<br />
            with a Human-Centered Lens
          </h1>
          <p class="hero-subtitle">
            I help organizations understand how people search, think, and navigate online—then turn those insights into clear,
            sustainable growth strategies.
          </p>
          <div class="hero-highlight">
            Currently open to collaborations with <strong>nonprofits, mission-driven teams, and value-led businesses</strong>
            looking to improve their digital visibility and communication.
          </div>
          <div class="hero-actions">
            <a href="#contact" class="btn-primary">
              Let’s work together
              <span aria-hidden="true">↗</span>
            </a>
            <a href="#work" class="btn-secondary">View selected work</a>
          </div>
          <div class="hero-badges">
            <span>Technical &amp; on-page SEO</span>
            <span>Research-driven content strategy</span>
            <span>Stakeholder communication</span>
            <span>Anthropology-informed insight</span>
          </div>
        </div>

        <aside class="hero-aside" aria-label="Profile summary">
          <div class="profile-card">
            <div class="avatar-placeholder">
              <!-- Replace with your initials or an actual photo if coded later -->
              <span>[Y]</span>
            </div>
            <div class="profile-name">[Your Name]</div>
            <div class="profile-role">SEO Analyst · Project Manager · Anthropologist by training</div>
            <div class="profile-meta">
              <div>
                <span class="label">Focus</span>
                <div>SEO audits, website optimization, content strategy</div>
              </div>
              <div>
                <span class="label">I work with</span>
                <div>Nonprofits, social enterprises, and purposeful teams</div>
              </div>
            </div>
            <div class="availability-tag">
              <span class="availability-tag-dot"></span>
              <span>Open to remote &amp; hybrid opportunities</span>
            </div>
          </div>

          <div class="note-card">
            With a background in anthropology, I bring qualitative research skills and cultural awareness into SEO and
            project work—helping teams design strategies that respect real people’s contexts, needs, and constraints.
          </div>
        </aside>
      </section>

      <!-- ABOUT -->
      <section id="about">
        <div class="section-header">
          <div>
            <div class="section-kicker">About</div>
            <h2 class="section-title">A bridge between data, people, and strategy</h2>
          </div>
          <p class="section-subtitle">
            Combining analytical SEO work with project management and human-centered research.
          </p>
        </div>

        <div class="about-grid">
          <article class="card">
            <p>
              I’m an SEO analyst and project manager with a background in <strong>anthropology</strong>. That means I care
              deeply about how people actually search, read, and make decisions online—not just what the numbers say.
            </p>
            <p>
              I’ve worked on projects that range from <strong>SEO audits and content optimizations</strong> to coordinating
              multi-stakeholder website improvements. My approach is collaborative, structured, and grounded in clear
              communication.
            </p>
            <p>
              I’m especially interested in supporting <strong>nonprofits, cultural institutions, and impact-driven
              organizations</strong> who want to use digital channels more thoughtfully and effectively.
            </p>
          </article>

          <aside class="card">
            <p><strong>What you can expect from me</strong></p>
            <ul style="margin-top: 6px; padding-left: 18px; font-size: 0.85rem; color: var(--muted);">
              <li>Clear, jargon-free explanations of SEO recommendations</li>
              <li>Structured project plans and realistic timelines</li>
              <li>Stakeholder-friendly documentation and reporting</li>
              <li>Empathy for users, audiences, and internal teams</li>
            </ul>
            <div class="pill-row">
              <span>Evidence-based</span>
              <span>Collaborative</span>
              <span>Curious</span>
              <span>Ethical</span>
            </div>
          </aside>
        </div>
      </section>

      <!-- SKILLS -->
      <section id="skills">
        <div class="section-header">
          <div>
            <div class="section-kicker">Skills</div>
            <h2 class="section-title">How I can contribute</h2>
          </div>
        </div>

        <div class="skills-grid">
          <article class="card skills-card">
            <h3>SEO &amp; Digital Strategy</h3>
            <ul>
              <li>Technical SEO audits &amp; site health reviews</li>
              <li>Keyword research &amp; search intent analysis</li>
              <li>On-page optimization &amp; information architecture</li>
              <li>Content performance analysis (GA4, GSC, etc.)</li>
              <li>Recommendations tailored to internal capacity</li>
            </ul>
          </article>

          <article class="card skills-card">
            <h3>Project &amp; Stakeholder Management</h3>
            <ul>
              <li>Defining scope, milestones, and priorities</li>
              <li>Coordinating between content, dev, and leadership</li>
              <li>Creating documentation &amp; repeatable workflows</li>
              <li>Risk management and expectation setting</li>
              <li>Facilitating workshops and check-ins</li>
            </ul>
          </article>

          <article class="card skills-card">
            <h3>Research &amp; Anthropology</h3>
            <ul>
              <li>Qualitative user research and interviews</li>
              <li>Audience personas grounded in real behavior</li>
              <li>Cultural/contextual analysis for content</li>
              <li>Accessibility-minded communication</li>
              <li>Ethical &amp; inclusive approach to data use</li>
            </ul>
          </article>
        </div>
      </section>

      <!-- WORK / PORTFOLIO -->
      <section id="work">
        <div class="section-header">
          <div>
            <div class="section-kicker">Selected work</div>
            <h2 class="section-title">Examples of what I do</h2>
          </div>
          <p class="section-subtitle">
            A few representative projects. I’m happy to discuss details in conversation.
          </p>
        </div>

        <div class="portfolio-grid">
          <article class="card portfolio-item">
            <h3>SEO audit &amp; roadmap for nonprofit website</h3>
            <div class="portfolio-meta">SEO · Nonprofit · Audit &amp; strategy</div>
            <p>
              Conducted a full technical and on-page audit for a nonprofit website. Prioritized issues by impact and effort,
              resulting in a clear, phased roadmap that internal teams could realistically implement.
            </p>
          </article>

          <article class="card portfolio-item">
            <h3>Content strategy for information-heavy organization</h3>
            <div class="portfolio-meta">Content strategy · UX · Research</div>
            <p>
              Used search data, user feedback, and qualitative research to reorganize key content areas, making it easier for
              audiences to find essential information and resources.
            </p>
          </article>

          <article class="card portfolio-item">
            <h3>Project coordination for website improvements</h3>
            <div class="portfolio-meta">Project management · Cross-team collaboration</div>
            <p>
              Coordinated designers, developers, and content specialists to deliver a set of SEO-driven improvements on time.
              Ensured everyone had the context they needed and kept stakeholders aligned.
            </p>
          </article>
        </div>
      </section>

      <!-- SERVICES -->
      <section id="services">
        <div class="section-header">
          <div>
            <div class="section-kicker">How we can work together</div>
            <h2 class="section-title">Support for teams &amp; organizations</h2>
          </div>
        </div>

        <div class="services-grid">
          <article class="card services-card">
            <h3>SEO audits &amp; recommendations</h3>
            <p>
              A structured review of your website’s technical setup, content, and search visibility—translated into a clear
              action plan your team can actually implement.
            </p>
          </article>

          <article class="card services-card">
            <h3>Project &amp; implementation support</h3>
            <p>
              From prioritizing tasks to coordinating with developers and content creators, I help keep SEO and web projects
              organized, realistic, and aligned with your goals.
            </p>
          </article>

          <article class="card services-card">
            <h3>Content &amp; communication strategy</h3>
            <p>
              Align your content with audience needs and search behavior. I combine SEO data with user insight to shape
              messaging, structure, and editorial priorities.
            </p>
          </article>

          <article class="card services-card">
            <h3>Support for nonprofits &amp; mission-driven teams</h3>
            <p>
              I’m particularly interested in collaborations with nonprofits and social impact organizations. If budget is a
              concern, I’m open to exploring flexible arrangements and scoped projects.
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
            Share a bit about your organization, your challenges, or your idea. I’ll get back to you as soon as I can.
          </p>
        </div>

        <div class="contact">
          <div class="card">
            <form action="mailto:your.email@example.com" method="post" enctype="text/plain">
              <!-- Replace the mailto: address above with your real email -->
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
            <p><strong>Prefer a different way to connect?</strong></p>
            <p style="margin-top: 6px;">
              You can also reach me at:
            </p>
            <p style="margin-top: 6px;">
              Email: <a href="mailto:your.email@example.com">your.email@example.com</a><br />
              LinkedIn: <a href="https://www.linkedin.com/in/your-profile" target="_blank" rel="noreferrer">linkedin.com/in/your-profile</a>
            </p>
            <p style="margin-top: 10px;">
              I’m especially happy to hear from:
            </p>
            <ul style="margin-top: 6px; padding-left: 18px;">
              <li>Nonprofits and NGOs</li>
              <li>Cultural and educational institutions</li>
              <li>Social enterprises and mission-driven teams</li>
              <li>Collaborators on research-based or community projects</li>
            </ul>
          </aside>
        </div>
      </section>
    </main>

    <footer>
      <div>© <span id="year"></span> [Your Name]. All rights reserved.</div>
      <div>Built with care for people, not just algorithms.</div>
    </footer>
  </div>

  <script>
    // Set current year automatically
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>

