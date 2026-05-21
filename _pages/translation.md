---
layout: archive
title: "Translations"
permalink: /translations/
author_profile: true
---

<style>
:root {
  --burgundy: #6f1d2f;
  --burgundy-dark: #571624;
  --burgundy-soft: #8b4358;
  --rose-mist: #f6eef1;
  --rose-light: #fbf7f8;
  --text-main: #2f2a2b;
  --text-soft: #6b6265;
  --line: #eadde2;
  --shadow: 0 10px 24px rgba(111, 29, 47, 0.08);
}

.translations-intro {
  font-size: 0.98rem;
  line-height: 1.7;
  color: var(--text-soft);
  margin-bottom: 2rem;
}

.translation-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(420px, 1fr));
  gap: 1.25rem;
  margin-top: 2rem;
}

.translation-card {
  display: grid;
  grid-template-columns: 160px 1fr;
  gap: 1rem;
  background: linear-gradient(180deg, #fff 0%, #fcf9fa 100%);
  border: 1px solid var(--line);
  border-left: 5px solid var(--burgundy);
  border-radius: 14px;
  padding: 1rem;
  box-shadow: 0 3px 10px rgba(0,0,0,0.02);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
  align-items: start;
}

.translation-card:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow);
  border-color: #dcc6ce;
}

.translation-cover img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  display: block;
  border: 1px solid #e6dde0;
  box-shadow: 0 6px 14px rgba(0,0,0,0.08);
}

.translation-type {
  display: inline-block;
  font-size: 0.75rem;
  font-weight: 700;
  color: white;
  background: var(--burgundy);
  border-radius: 999px;
  padding: 0.15rem 0.6rem;
  margin-bottom: 0.55rem;
}

.translation-title {
  font-size: 1.08rem;
  font-weight: 700;
  color: var(--burgundy-dark);
  line-height: 1.4;
  margin-bottom: 0.55rem;
}

.translation-meta {
  font-size: 0.92rem;
  line-height: 1.6;
  color: var(--text-main);
  margin-bottom: 0.75rem;
}

.translation-meta strong {
  color: var(--burgundy-dark);
}

.translation-publisher {
  margin-bottom: 0.85rem;
}

.translation-publisher a {
  display: inline-block;
  text-decoration: none;
  font-size: 0.84rem;
  font-weight: 600;
  color: var(--burgundy);
  border: 1px solid #d9bcc5;
  background: white;
  border-radius: 999px;
  padding: 0.22rem 0.72rem;
  transition: all 0.18s ease;
}

.translation-publisher a:hover {
  background: var(--burgundy);
  color: white;
  border-color: var(--burgundy);
}

.translation-citation-label {
  font-size: 0.82rem;
  font-weight: 700;
  color: var(--burgundy-dark);
  margin-bottom: 0.35rem;
}

.translation-citation-box {
  background: var(--rose-light);
  border: 1px solid var(--line);
  border-radius: 10px;
  padding: 0.75rem 0.85rem;
  font-size: 0.88rem;
  line-height: 1.55;
  color: var(--text-main);
  margin-bottom: 0.55rem;
  white-space: normal;
}

.copy-btn {
  display: inline-block;
  font-size: 0.8rem;
  font-weight: 600;
  color: var(--burgundy);
  background: white;
  border: 1px solid #d9bcc5;
  border-radius: 999px;
  padding: 0.22rem 0.72rem;
  cursor: pointer;
  transition: all 0.18s ease;
}

.copy-btn:hover {
  background: var(--burgundy);
  color: white;
  border-color: var(--burgundy);
}

.copy-status {
  display: inline-block;
  margin-left: 0.45rem;
  font-size: 0.78rem;
  color: var(--text-soft);
}

@media (max-width: 700px) {
  .translation-grid {
    grid-template-columns: 1fr;
  }

  .translation-card {
    grid-template-columns: 1fr;
  }

  .translation-cover {
    max-width: 180px;
  }
}
</style>

<div class="translations-intro" markdown="1">

This page presents my translated books. It reflects my engagement with **history**, **political thought**, and the broader world of publishing and intellectual circulation.

</div>

<div class="translation-grid">

  <!-- CARD 1 -->
  <div class="translation-card">
    <div class="translation-cover">
      <img src="/images/translations/kral.jpg" alt="Kral: Mitler ve Simgeler cover">
    </div>
    <div class="translation-content">
      <div class="translation-type">Book Translation</div>
      <div class="translation-title">Kral: Mitler ve Simgeler</div>

      <div class="translation-meta">
        <div><strong>Original author:</strong> Jean-Paul Roux</div>
        <div><strong>Translated by:</strong> Nuri Fudayl Kıcıroğlu</div>
        <div><strong>Publisher:</strong> Dergâh Yayınları</div>
      </div>

      <div class="translation-publisher">
        <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      </div>

      <div class="translation-citation-label">Citation</div>
      <div class="translation-citation-box" id="citation-1">Roux, Jean-Paul. <em>Kral: Mitler ve Simgeler</em>. Translated by Nuri Fudayl Kıcıroğlu. İstanbul: Dergâh Yayınları.</div>
      <button class="copy-btn" onclick="copyCitation('citation-1', 'status-1')">Copy citation</button>
      <span class="copy-status" id="status-1"></span>
    </div>
  </div>

  <!-- CARD 2 -->
  <div class="translation-card">
    <div class="translation-cover">
      <img src="/images/translations/bir-yenicerinin-hatiralari.jpg" alt="Bir Yeniçerinin Hatıraları cover">
    </div>
    <div class="translation-content">
      <div class="translation-type">Collaborative Translation</div>
      <div class="translation-title">Bir Yeniçerinin Hatıraları</div>

      <div class="translation-meta">
        <div><strong>Original author:</strong> Konstantin Mihailović</div>
        <div><strong>Translated by:</strong> Nuri Fudayl Kıcıroğlu and Behiç Anıl Ekim</div>
        <div><strong>Publisher:</strong> Ayrıntı Yayınları</div>
      </div>

      <div class="translation-publisher">
        <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      </div>

      <div class="translation-citation-label">Citation</div>
      <div class="translation-citation-box" id="citation-2">Mihailović, Konstantin. <em>Bir Yeniçerinin Hatıraları</em>. Translated by Nuri Fudayl Kıcıroğlu and Behiç Anıl Ekim. İstanbul: Ayrıntı Yayınları.</div>
      <button class="copy-btn" onclick="copyCitation('citation-2', 'status-2')">Copy citation</button>
      <span class="copy-status" id="status-2"></span>
    </div>
  </div>

  <!-- CARD 3 -->
  <div class="translation-card">
    <div class="translation-cover">
      <img src="/images/translations/somurge-ve-kolelik.jpg" alt="Sömürge ve Kölelik cover">
    </div>
    <div class="translation-content">
      <div class="translation-type">Book Translation</div>
      <div class="translation-title">[Title of Translation]</div>

      <div class="translation-meta">
        <div><strong>Original author:</strong> [Alexis de Tocqueville]</div>
        <div><strong>Translated by:</strong> Nuri Fudayl Kıcıroğlu</div>
        <div><strong>Publisher:</strong> [Ayrıntı Yayınları]</div>
      </div>

      <div class="translation-publisher">
        <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      </div>

      <div class="translation-citation-label">Citation</div>
      <div class="translation-citation-box" id="citation-3">[de Tocqueville], [Alexis]. <em>[Sömürge ve Kölelik]</em>. Edited by Lütfi Sunar, Translated by Burak M.N. Gücin, Hasan Turunçkapı, and Nuri Fudayl Kıcıroğlu. İstanbul: [Ayrıntı Yayınları].</div>
      <button class="copy-btn" onclick="copyCitation('citation-3', 'status-3')">Copy citation</button>
      <span class="copy-status" id="status-3"></span>
    </div>
  </div>

  <!-- CARD 4 -->
  <div class="translation-card">
    <div class="translation-cover">
      <img src="/images/translations/anadoludaki-turk-anitlari.jpg" alt="Anadolu'daki Türk Anıtları cover">
    </div>
    <div class="translation-content">
      <div class="translation-type">Collaborative Translation</div>
      <div class="translation-title">[Anadolu'daki Türk Anıtları]</div>

      <div class="translation-meta">
        <div><strong>Original author:</strong> [Albert-Louis Gabriel]</div>
        <div><strong>Translated by:</strong> Nuri Fudayl Kıcıroğlu</div>
        <div><strong>Publisher:</strong> [Türk Arkeoloji ve Kültürel Miras Enstitüsü]</div>
      </div>

      <div class="translation-publisher">
        <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      </div>

      <div class="translation-citation-label">Citation</div>
      <div class="translation-citation-box" id="citation-4">[Gabriel], [Albert-Louis]. <em>[Anadolu'daki Türk Anıtları II: Amasya - Tokat - Sivas]</em>. Translated by Nuri Fudayl Kıcıroğlu. İstanbul: [Türk Arkeoloji ve Kültürel Miras Enstitüsü].</div>
      <button class="copy-btn" onclick="copyCitation('citation-4', 'status-4')">Copy citation</button>
      <span class="copy-status" id="status-4"></span>
    </div>
  </div>

</div>

<script>
function copyCitation(citationId, statusId) {
  const citationText = document.getElementById(citationId).innerText;
  navigator.clipboard.writeText(citationText).then(function() {
    const status = document.getElementById(statusId);
    status.textContent = "Copied";
    setTimeout(function() {
      status.textContent = "";
    }, 1600);
  });
}
</script>
