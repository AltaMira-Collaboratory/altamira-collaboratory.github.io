---
layout: default
title: Members
permalink: /members/
---

<div class="center-card">
  <div class="back-button">
    <a href="/">← Back to Home</a>
  </div>
  <h1>Members</h1>
  <div class="members-grid">
    <div class="member-card">
      <h3>Andre Souza</h3>
      <p class="affiliation">MIT</p>
      <div class="member-links">
        <a href="https://scholar.google.com/citations?user=FoK_ufEAAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a> |
        <a href="https://www.linkedin.com/in/andre-souza-8363144b" target="_blank" rel="noopener noreferrer">LinkedIn</a> |
        <a href="https://sandreza.github.io/" target="_blank" rel="noopener noreferrer">Personal Website</a>
      </div>
    </div>
    <div class="member-card">
      <h3>Tobias Bischoff</h3>
      <p class="affiliation">Aeolus Labs</p>
      <div class="member-links">
        <a href="https://scholar.google.com/citations?user=90o1ec0AAAAJ&hl=en&oi=sra" target="_blank" rel="noopener noreferrer">Google Scholar</a> |
        <a href="https://www.linkedin.com/in/bischtob/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      </div>
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
.members-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}
.member-card {
  background: #f8f9fa;
  border-radius: 8px;
  padding: 1.5rem;
  box-shadow: 0 2px 8px rgba(186, 106, 60, 0.08);
  border: 1.5px solid var(--accent);
  transition: transform 0.2s ease, box-shadow 0.2s;
}
.member-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 16px rgba(186, 106, 60, 0.15);
}
.member-card h3 {
  margin: 0 0 0.5rem 0;
  color: var(--accent-dark);
}
.affiliation {
  color: #8a4a22;
  margin: 0 0 1rem 0;
  font-style: italic;
}
.member-links {
  font-size: 0.95rem;
}
.member-links a {
  color: var(--accent);
  text-decoration: none;
  font-weight: 500;
}
.member-links a:hover {
  text-decoration: underline;
  color: var(--accent-dark);
}
</style> 