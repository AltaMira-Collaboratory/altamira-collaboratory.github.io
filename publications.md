---
layout: default
title: Publications
permalink: /publications/
---

<div class="back-button">
  <a href="/">← Back to Home</a>
</div>

# Publications

<div class="publications-list">
  <div class="publication-card">
    <h3><a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.133.267302" target="_blank" rel="noopener noreferrer">Title of the PRL Paper</a></h3>
    <div class="citation">
      <strong>Cite as:</strong><br>
      Author(s). <em>Title of the PRL Paper</em>. <strong>Phys. Rev. Lett.</strong> 133, 267302 (2024). <a href="https://doi.org/10.1103/PhysRevLett.133.267302" target="_blank">https://doi.org/10.1103/PhysRevLett.133.267302</a>
    </div>
    <div class="pub-description">
      <em>Why it matters:</em> Briefly describe the significance or impact of this work here.
    </div>
  </div>
</div>

<style>
:root {
  --primary-bg: #f8f5f0;
  --accent: #b86a3c;
  --accent-dark: #8a4a22;
  --text-main: #2c1a0e;
  --card-bg: #fffaf6;
}
body {
  background: var(--primary-bg);
  color: var(--text-main);
}
.publications-list {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin: 2rem 0;
}
.publication-card {
  background: var(--card-bg);
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(186, 106, 60, 0.08);
  border: 1.5px solid var(--accent);
  padding: 1.5rem;
}
.publication-card h3 {
  margin: 0 0 0.5rem 0;
  color: var(--accent-dark);
  font-size: 1.2rem;
}
.publication-card a {
  color: var(--accent);
  text-decoration: none;
}
.publication-card a:hover {
  text-decoration: underline;
  color: var(--accent-dark);
}
.citation {
  font-size: 0.95rem;
  background: #f3e5d8;
  padding: 0.7rem 1rem;
  border-radius: 6px;
  margin: 0.7rem 0 0.7rem 0;
  color: var(--text-main);
}
.pub-description {
  font-size: 0.95rem;
  color: #8a4a22;
}
.back-button {
  margin-bottom: 2rem;
}
.back-button a {
  color: var(--accent);
  text-decoration: none;
  font-size: 1.1rem;
  display: inline-block;
  padding: 0.5rem 1rem;
  border-radius: 4px;
  transition: background-color 0.2s ease;
}
.back-button a:hover {
  background-color: #f3e5d8;
  text-decoration: none;
}
</style> 