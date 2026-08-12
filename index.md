---
layout: null
title: Shuhan Zhang | Research
---
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Shuhan Zhang is an incoming Ph.D. student in Machine Learning (CSE) at Georgia Tech working on agent evolution, AI for decision-making, and optimization.">
  <title>Shuhan Zhang | Research</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Newsreader:opsz,wght@6..72,500;6..72,600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="./styles.css">
</head>
<body>
  <header class="site-header">
    <div class="header-inner">
      <a class="site-name" href="#top">Shuhan Zhang</a>
      <nav aria-label="Primary navigation">
        <a href="#research">Research</a>
        <a href="#publications">Publications</a>
        <a href="#experience">Experience</a>
        <a href="./CV-Shuhan.pdf">CV</a>
      </nav>
    </div>
  </header>

  <main id="top" class="page-shell">
    <section class="profile" aria-labelledby="profile-name">
      <div class="profile-copy">
        <p class="position">Incoming Ph.D. student in Machine Learning (CSE)</p>
        <h1 id="profile-name">Shuhan Zhang</h1>
        <p class="affiliation">Georgia Institute of Technology</p>

        <div class="bio">
          <p>I am an incoming Ph.D. student in Machine Learning (CSE) at Georgia Tech, advised by <a href="https://guaguakai.com/">Prof. Kai Wang</a>. My research lies at the intersection of <strong>agent evolution</strong>, <strong>decision-making</strong>, and <strong>optimization</strong>.</p>
          <p>I study how intelligent systems can improve not only a solution, but also the process that produces it: the algorithms they search, the feedback they use, and the evaluation mechanisms that guide them. I am also interested in interpretable choice models and reinforcement learning through the lens of optimization.</p>
          <p>Previously, I completed my B.S. at CUHK-Shenzhen, visited the University of Pennsylvania, conducted research at UT Austin, and worked as a research intern at Microsoft Research Asia.</p>
        </div>

        <div class="profile-links" aria-label="Profile links">
          <a href="https://scholar.google.com/citations?user=taugnTAAAAAJ&hl=en">Google Scholar ↗</a>
          <a href="https://github.com/Asimov-Chuang">GitHub ↗</a>
          <a href="./CV-Shuhan.pdf">CV ↗</a>
          <a href="mailto:szhang3007@gatech.edu">Email ↗</a>
        </div>
      </div>

      <figure class="profile-photo">
        <img src="./avatar.JPG" alt="Shuhan Zhang">
      </figure>
    </section>

    <section class="content-section news-section" aria-labelledby="news-heading">
      <h2 id="news-heading">News</h2>
      <div class="news-list">
        <div class="news-item"><time>Aug 2026</time><p>I will join Georgia Tech as an incoming Ph.D. student in Machine Learning (CSE).</p></div>
        <div class="news-item"><time>2026</time><p>I joined Microsoft Research Asia as a research intern, studying feedback in agentic algorithm discovery.</p></div>
        <div class="news-item"><time>Dec 2025</time><p>DeepHalo was presented as a Spotlight at NeurIPS 2025.</p></div>
        <div class="news-item"><time>Jan 2025</time><p>Logic-Logit was accepted to ICLR 2025.</p></div>
      </div>
    </section>

    <section class="content-section" id="research" aria-labelledby="research-heading">
      <h2 id="research-heading">Research interests</h2>
      <div class="research-columns">
        <article><h3>Agent evolution</h3><p>Algorithm discovery, recursive self-improvement, harness evolution, and feedback-system design.</p></article>
        <article><h3>AI for decision-making</h3><p>Choice modeling, decision-focused learning, preference learning, and human–AI interaction.</p></article>
        <article><h3>Optimization & learning</h3><p>Reinforcement learning, Wasserstein geometry, differentiable optimization, and online learning.</p></article>
      </div>
    </section>

    <section class="content-section" id="publications" aria-labelledby="publications-heading">
      <div class="section-title-row">
        <h2 id="publications-heading">Selected publications &amp; projects</h2>
        <a href="https://scholar.google.com/citations?user=taugnTAAAAAJ&hl=en">Full list on Google Scholar ↗</a>
      </div>
      <div class="publication-list">
        <article class="publication">
          <div class="publication-year">2026</div>
          <div class="publication-body">
            <h3>Is Auxiliary Feedback a Free Lunch for Agentic Algorithm Discovery?</h3>
            <p class="authors"><strong>Shuhan Zhang*</strong>, Lu Wang†, Shuang Li, Qingwei Lin, Dongmei Zhang, Hongyuan Zha, Saravan Rajmohan, Qi Zhang</p>
            <p class="venue"><strong>Working paper</strong><span> · Agentic AI · Algorithm discovery</span></p>
            <p class="publication-description">A mechanism-driven study of when richer feedback helps—or misleads—coding agents searching for better algorithms.</p>
          </div>
        </article>

        <article class="publication">
          <div class="publication-year">2025</div>
          <div class="publication-body">
            <h3>DeepHalo: A Neural Choice Model with Controllable Context Effects</h3>
            <p class="authors"><strong>Shuhan Zhang</strong>, Zhi Wang, Rui Gao, Shuang Li</p>
            <p class="venue"><strong>NeurIPS 2025 · Spotlight</strong><span> · Choice modeling · Interpretable ML</span></p>
            <p class="publication-description">A neural choice model that captures high-order context effects while allowing explicit control over interaction order.</p>
            <div class="publication-links"><a href="https://papers.neurips.cc/paper_files/paper/2025/hash/c717858997b6b999e58557ef7ff23da6-Abstract-Conference.html">Paper</a><a href="https://github.com/Asimov-Chuang/DeepHalo">Code</a></div>
          </div>
        </article>

        <article class="publication">
          <div class="publication-year">2025</div>
          <div class="publication-body">
            <h3>Logic-Logit: A Logic-Based Approach to Choice Modeling</h3>
            <p class="authors"><strong>Shuhan Zhang</strong>, Wendi Ren, Shuang Li</p>
            <p class="venue"><strong>ICLR 2025 · Poster</strong><span> · Interpretable ML · Discrete choice</span></p>
            <p class="publication-description">An interpretable choice model built from sparse logical rules and trained through column generation and Frank–Wolfe optimization.</p>
            <div class="publication-links"><a href="https://proceedings.iclr.cc/paper_files/paper/2025/hash/eb08c521d8db3c4acc6b4bc4f6e14173-Abstract-Conference.html">Paper</a></div>
          </div>
        </article>

        <article class="publication">
          <div class="publication-year">2026</div>
          <div class="publication-body">
            <h3>Wasserstein Proximal Policy Gradient</h3>
            <p class="authors"><strong>Shuhan Zhang</strong> et al.</p>
            <p class="venue"><strong>Under review</strong><span> · Reinforcement learning · Wasserstein geometry</span></p>
            <p class="publication-description">Policy optimization through Wasserstein geometry, with expressive implicit policy classes and distributional updates.</p>
            <div class="publication-links"><a href="https://github.com/Asimov-Chuang/wasserstein-proximal-policy-gradient">Code</a></div>
          </div>
        </article>
      </div>
    </section>

    <section class="content-section" id="experience" aria-labelledby="experience-heading">
      <h2 id="experience-heading">Education &amp; experience</h2>
      <div class="experience-list">
        <article class="experience-item"><time>Fall 2026 —</time><div><h3>Ph.D. in Machine Learning (CSE)</h3><p class="place">Georgia Institute of Technology</p><p class="detail">Incoming student; advised by Prof. Kai Wang</p></div></article>
        <article class="experience-item"><time>2026</time><div><h3>Research Intern</h3><p class="place">Microsoft Research Asia</p><p class="detail">Agentic algorithm discovery and feedback systems</p></div></article>
        <article class="experience-item"><time>Summer 2025</time><div><h3>Summer Researcher</h3><p class="place">The University of Texas at Austin</p><p class="detail">Reinforcement learning and policy optimization</p></div></article>
        <article class="experience-item"><time>Spring 2025</time><div><h3>Visiting Student</h3><p class="place">University of Pennsylvania</p><p class="detail">Optimization, Bayesian analysis, and game theory</p></div></article>
        <article class="experience-item"><time>2022 — 2026</time><div><h3>B.S. in Data Science</h3><p class="place">The Chinese University of Hong Kong, Shenzhen</p><p class="detail">GPA 3.9/4.0 · Dean’s List</p></div></article>
      </div>
    </section>
  </main>

  <footer id="contact">
    <div class="footer-inner">
      <div><strong>Shuhan Zhang</strong><p>Incoming Ph.D. student in Machine Learning (CSE) · Georgia Tech</p></div>
      <div class="footer-links"><a href="mailto:szhang3007@gatech.edu">szhang3007@gatech.edu</a><a href="#top">Back to top ↑</a></div>
    </div>
  </footer>
</body>
</html>
