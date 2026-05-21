---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

<style>
.cv-page {
  max-width: 980px;
  margin: 0 auto;
}

.cv-intro {
  margin-bottom: 1.5rem;
  font-size: 1rem;
  line-height: 1.65;
  color: #444;
}

.cv-actions {
  display: flex;
  gap: 0.75rem;
  flex-wrap: wrap;
  margin: 1.5rem 0 2rem;
}

.cv-button {
  display: inline-block;
  padding: 0.7rem 1rem;
  border: 1px solid #222;
  border-radius: 6px;
  text-decoration: none;
  font-size: 0.9rem;
  transition: all 0.2s ease;
}

.cv-button:hover {
  background: #222;
  color: #fff;
  text-decoration: none;
}

.cv-button-secondary {
  border-color: #777;
  color: #555;
}

.cv-button-secondary:hover {
  background: #555;
  color: #fff;
}

.cv-viewer {
  width: 100%;
  height: 1100px;
  border: 1px solid #ddd;
  border-radius: 6px;
  background: #f8f8f8;
}

.cv-fallback {
  margin-top: 1rem;
  font-size: 0.9rem;
  color: #666;
}

@media (max-width: 768px) {
  .cv-viewer {
    height: 700px;
  }
}
</style>

<div class="cv-page">

<div class="cv-actions">
  <a href="/assets/files/cv.pdf" class="cv-button" target="_blank" rel="noopener noreferrer">
    View CV in New Tab
  </a>

  <a href="/assets/files/cv.pdf" class="cv-button cv-button-secondary" download="CV - KICIROGLU Nuri Fudayl.pdf">
    Download CV
  </a>
</div>

<iframe 
  src="/assets/files/cv.pdf"
  class="cv-viewer"
  title="Curriculum Vitae">
</iframe>

<p class="cv-fallback">
If the PDF does not display properly in your browser, you can open it in a new tab or download it using the buttons above.
</p>

</div>
