---
layout: default
title: Members
permalink: /members/
---

<div class="back-button">
  <a href="/">← Back to Home</a>
</div>

# Members

<div class="members-grid">
  <div class="member-card">
    <h3>Andre Souza</h3>
    <p class="affiliation">MIT</p>
    <div class="member-links">
      <a href="https://scholar.google.com/citations?user=FoK_ufEAAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a> |
      <a href="www.linkedin.com/in/andre-souza-8363144b" target="_blank" rel="noopener noreferrer">LinkedIn</a> |
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

<style>
.back-button {
  margin-bottom: 2rem;
}

.back-button a {
  color: #0366d6;
  text-decoration: none;
  font-size: 1.1rem;
  display: inline-block;
  padding: 0.5rem 1rem;
  border-radius: 4px;
  transition: background-color 0.2s ease;
}

.back-button a:hover {
  background-color: #f0f0f0;
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
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: transform 0.2s ease;
}

.member-card:hover {
  transform: translateY(-2px);
}

.member-card h3 {
  margin: 0 0 0.5rem 0;
  color: #2c3e50;
}

.affiliation {
  color: #666;
  margin: 0 0 1rem 0;
  font-style: italic;
}

.member-links {
  font-size: 0.9rem;
}

.member-links a {
  color: #0366d6;
  text-decoration: none;
}

.member-links a:hover {
  text-decoration: underline;
}
</style> 