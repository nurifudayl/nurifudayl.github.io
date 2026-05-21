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
  --text-main: #2f2a2b;
  --text-soft: #6b6265;
  --line: #eadde2;
}

.translations-intro {
  font-size: 0.98rem;
  line-height: 1.7;
  color: var(--text-soft);
  margin-bottom: 2rem;
}

.translation-list {
  margin-top: 1.5rem;
}

.translation-item {
  display: grid;
  grid-template-columns: 120px 1fr;
  gap: 1.2rem;
  padding: 1.35rem 0;
  border-bottom: 1px solid var(--line);
}

.translation-item:first-child {
  border-top: 1px solid var(--line);
}

.translation-cover {
  width: 120px;
  aspect-ratio: 2 / 3;
  overflow: hidden;
  border-radius: 6px;
  border: 1px solid var(--line);
  background: transparent;
}

.translation-cover img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.translation-title {
  font-size: 1.08rem;
  font-weight: 700;
  color: var(--burgundy-dark);
  line-height: 1.4;
  margin-bottom: 0.45rem;
}

.translation-years {
  margin-bottom: 0.65rem;
}

.translation-year {
  display: inline-block;
  font-size: 0.76rem;
  font-weight: 700;
  color: var(--burgundy);
  background: transparent;
  border: 1px solid #d9bcc5;
  border-radius: 999px;
  padding: 0.12rem 0.55rem;
  margin-right: 0.3rem;
  margin-bottom: 0.25rem;
}

.translation-meta {
  font-size: 0.9rem;
  line-height: 1.55;
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
  font-size: 0.82rem;
  font-weight: 600;
  color: var(--burgundy);
  border: 1px solid #d9bcc5;
  background: transparent;
  border-radius: 999px;
  padding: 0.2rem 0.68rem;
  transition: all 0.18s ease;
}

.translation-publisher a:hover {
  background: var(--burgundy);
  color: #fff;
  border-color: var(--burgundy);
}

.translation-citation-label {
  font-size: 0.82rem;
  font-weight: 700;
  color: var(--burgundy-dark);
  margin-bottom: 0.35rem;
}

.translation-citation-box {
  border-left: 3px solid var(--burgundy);
  padding: 0.55rem 0 0.55rem 0.75rem;
  font-size: 0.86rem;
  line-height: 1.55;
  color: var(--text-main);
  margin-bottom: 0.55rem;
  background: transparent;
}

.copy-btn {
  display: inline-block;
  font-size: 0.78rem;
  font-weight: 600;
  color: var(--burgundy);
  background: transparent;
  border: 1px solid #d9bcc5;
  border-radius: 999px;
  padding: 0.18rem 0.65rem;
  cursor: pointer;
  transition: all 0.18s ease;
}

.copy-btn:hover {
  background: var(--burgundy);
  color: #fff;
  border-color: var(--burgundy);
}

.copy-status {
  display: inline-block;
  margin-left: 0.45rem;
  font-size: 0.78rem;
  color: var(--text-soft);
}

@media (max-width: 700px) {
  .translation-item {
    grid-template-columns: 90px 1fr;
    gap: 0.9rem;
  }

  .translation-cover {
    width: 90px;
  }
}
</style>

<div class="translations-intro" markdown="1">

This page presents my translated books. These works reflect my engagement with **history**, **political thought**, and the circulation of ideas across languages and intellectual traditions.

</div>

<div class="translation-list">

  <div class="translation-item">
    <div class="translation-cover">
      <img src="/images/translations/kral.jpg" alt="Kral: Mitler ve Simgeler cover">
    </div>

    <div class="translation-content">
      <div class="translation-title">Kral: Mitler ve Simgeler</div>

      <div class="translation-years">
        <span class="translation-year">YEAR</span>
      </div>

      <div class="translation-meta">
        <div><strong>Original author:</strong> Jean-Paul Roux</div>
        <div><strong>Translated by:</strong> Nuri Fudayl Kıcıroğlu</div>
        <div><strong>Publisher:</strong> Dergâh Yayınları</div>
      </div>

      <div class="translation-publisher">
        <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      </div>

      <div class="translation-citation-label">Citation</div>
      <div class="translation-citation-box" id="citation-1">Roux, Jean-Paul. <em>Kral: Mitler ve Simgeler</em>. Translated by Nuri Fudayl Kıcıroğlu. İstanbul: Dergâh Yayınları, YEAR.</div>
      <button class="copy-btn" onclick="copyCitation('citation-1', 'status-1')">Copy citation</button>
      <span class="copy-status" id="status-1"></span>
    </div>
  </div>

  <div class="translation-item">
    <div class="translation-cover">
      <img src="/images/translations/bir-yenicerinin-hatiralari.jpg" alt="Bir Yeniçerinin Hatıraları cover">
    </div>

    <div class="translation-content">
      <div class="translation-title">Bir Yeniçerinin Hatıraları</div>

      <div class="translation-years">
        <span class="translation-year">YEAR</span>
        <span class="translation-year">YEAR</span>
        <span class="translation-year">YEAR</span>
      </div>

      <div class="translation-meta">
        <div><strong>Original author:</strong> Konstantin Mihailović</div>
        <div><strong>Translated by:</strong> Nuri Fudayl Kıcıroğlu and Behiç Anıl Ekim</div>
        <div><strong>Publisher:</strong> Ayrıntı Yayınları</div>
      </div>

      <div class="translation-publisher">
        <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      </div>

      <div class="translation-citation-label">Citation</div>
      <div class="translation-citation-box" id="citation-2">Mihailović, Konstantin. <em>Bir Yeniçerinin Hatıraları</em>. Translated by Nuri Fudayl Kıcıroğlu and Behiç Anıl Ekim. İstanbul: Ayrıntı Yayınları, YEAR.</div>
      <button class="copy-btn" onclick="copyCitation('citation-2', 'status-2')">Copy citation</button>
      <span class="copy-status" id="status-2"></span>
    </div>
  </div>

  <div class="translation-item">
    <div class="translation-cover">
      <img src="/images/translations/somurge-ve-kolelik.jpg" alt="Sömürge ve Kölelik cover">
    </div>

    <div class="translation-content">
      <div class="translation-title">Sömürge ve Kölelik</div>

      <div class="translation-years">
        <span class="translation-year">YEAR</span>
      </div>

      <div class="translation-meta">
        <div><strong>Original author:</strong> Alexis de Tocqueville</div>
        <div><strong>Edited by:</strong> Lütfi Sunar</div>
        <div><strong>Translated by:</strong> Burak M. N. Gücin, Hasan Turunçkapı, and Nuri Fudayl Kıcıroğlu</div>
        <div><strong>Publisher:</strong> Ayrıntı Yayınları</div>
      </div>

      <div class="translation-publisher">
        <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      </div>

      <div class="translation-citation-label">Citation</div>
      <div class="translation-citation-box" id="citation-3">Tocqueville, Alexis de. <em>Sömürge ve Kölelik</em>. Edited by Lütfi Sunar. Translated by Burak M. N. Gücin, Hasan Turunçkapı, and Nuri Fudayl Kıcıroğlu. İstanbul: Ayrıntı Yayınları, YEAR.</div>
      <button class="copy-btn" onclick="copyCitation('citation-3', 'status-3')">Copy citation</button>
      <span class="copy-status" id="status-3"></span>
    </div>
  </div>

  <div class="translation-item">
    <div class="translation-cover">
      <img src="/images/translations/anadoludaki-turk-anitlari.jpg" alt="Anadolu'daki Türk Anıtları cover">
    </div>

    <div class="translation-content">
      <div class="translation-title">Anadolu'daki Türk Anıtları II: Amasya - Tokat - Sivas</div>

      <div class="translation-years">
        <span class="translation-year">YEAR</span>
      </div>

      <div class="translation-meta">
        <div><strong>Original author:</strong> Albert-Louis Gabriel</div>
        <div><strong>Translated by:</strong> Nuri Fudayl Kıcıroğlu</div>
        <div><strong>Publisher:</strong> Türk Arkeoloji ve Kültürel Miras Enstitüsü</div>
      </div>

      <div class="translation-publisher">
        <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      </div>

      <div class="translation-citation-label">Citation</div>
      <div class="translation-citation-box" id="citation-4">Gabriel, Albert-Louis. <em>Anadolu'daki Türk Anıtları II: Amasya - Tokat - Sivas</em>. Translated by Nuri Fudayl Kıcıroğlu. İstanbul: Türk Arkeoloji ve Kültürel Miras Enstitüsü, YEAR.</div>
      <button class="copy-btn" onclick="copyCitation('citation-4', 'status-4')">Copy citation</button>
      <span class="copy-status" id="status-4"></span>
    </div>
  </div>

</div>

<script>
function copyCitation(citationId, statusId) {
  const citationElement = document.getElementById(citationId);
  const statusElement = document.getElementById(statusId);

  if (!citationElement || !statusElement) return;

  const citationText = citationElement.innerText;

  if (navigator.clipboard) {
    navigator.clipboard.writeText(citationText).then(function() {
      statusElement.textContent = "Copied";
      setTimeout(function() {
        statusElement.textContent = "";
      }, 1600);
    });
  } else {
    const textarea = document.createElement("textarea");
    textarea.value = citationText;
    document.body.appendChild(textarea);
    textarea.select();
    document.execCommand("copy");
    document.body.removeChild(textarea);

    statusElement.textContent = "Copied";
    setTimeout(function() {
      statusElement.textContent = "";
    }, 1600);
  }
}
</script>
