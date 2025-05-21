---
layout: default
title: Publications
permalink: /publications/
---

<div class="center-card">
  <div class="back-button">
    <a href="/">← Back to Home</a>
  </div>
  <h1>Publications</h1>
  <div class="publications-list">
    <div class="publication-card">
      <h3><a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.133.267302" target="_blank" rel="noopener noreferrer">Response Theory via Generative Score Modeling</a></h3>
      <div class="citation">
        <strong>Cite as:</strong><br>
        Giorgini, Ludovico Theo and Deck, Katherine and Bischoff, Tobias and Souza, Andre. <em>Response Theory via Generative Score Modeling</em>. <strong>Phys. Rev. Lett.</strong> 133, 267302 (2024). <a href="https://doi.org/10.1103/PhysRevLett.133.267302" target="_blank">https://doi.org/10.1103/PhysRevLett.133.267302</a>
      </div>
      <div class="pub-description">
        <em>TLDR;</em> Combines score-based generative models from AI with linear response theory from statistical mechanics. 
      </div>
      <div class="bibtex-section">
        <button class="copy-btn" onclick="copyBibtex(this)">Copy BibTeX</button>
        <pre class="bibtex-entry" id="prl-bibtex">
@article{PhysRevLett.133.267302,
  title = {Response Theory via Generative Score Modeling},
  author = {Giorgini, Ludovico Theo and Deck, Katherine and Bischoff, Tobias and Souza, Andre},
  journal = {Phys. Rev. Lett.},
  volume = {133},
  issue = {26},
  pages = {267302},
  numpages = {7},
  year = {2024},
  month = {Dec},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevLett.133.267302},
  url = {https://link.aps.org/doi/10.1103/PhysRevLett.133.267302}
}
        </pre>
      </div>
    </div>
  </div>
</div>

<script>
function copyBibtex(btn) {
  const bib = btn.nextElementSibling.innerText;
  navigator.clipboard.writeText(bib);
  btn.innerText = 'Copied!';
  setTimeout(() => { btn.innerText = 'Copy BibTeX'; }, 1500);
}
</script>

<style>
:root {
  --primary-bg: #f8f5f0;
  --accent: #b86a3c;
  --accent-dark: #8a4a22;
  --text-main: #2c1a0e;
  --card-bg: #fffaf6;
}
body {
  background: var(--primary-bg) !important;
  color: var(--text-main) !important;
}
.center-card {
  max-width: 700px;
  margin: 2.5rem auto;
  background: var(--card-bg);
  border-radius: 12px;
  box-shadow: 0 4px 24px rgba(120, 60, 20, 0.10);
  padding: 2.5rem 2rem 2rem 2rem;
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
.bibtex-section {
  margin-top: 1rem;
  margin-bottom: 1rem;
  position: relative;
}
.copy-btn {
  background: var(--accent);
  color: #fff;
  border: none;
  border-radius: 4px;
  padding: 0.3rem 1rem;
  font-size: 0.95rem;
  font-weight: 500;
  cursor: pointer;
  margin-bottom: 0.5rem;
  transition: background 0.2s;
}
.copy-btn:hover {
  background: var(--accent-dark);
}
.bibtex-entry {
  background: #f3e5d8;
  color: var(--text-main);
  border-radius: 6px;
  padding: 1rem;
  font-size: 0.95rem;
  overflow-x: auto;
  display: none;
}
.bibtex-section:hover .bibtex-entry,
.bibtex-section:focus-within .bibtex-entry {
  display: block;
}
.pub-description {
  font-size: 0.95rem;
  color: #8a4a22;
}
</style> 