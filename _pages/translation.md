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
  --text-main: #222;
  --text-soft: #666;
  --line: #e6d9dd;
  --line-strong: #d9bcc5;
  --shadow: 0 10px 24px rgba(111, 29, 47, 0.10);
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
  grid-template-columns: 112px minmax(0, 1fr) 126px;
  gap: 1.15rem;
  align-items: center;
  padding: 1.1rem 0.95rem;
  margin-bottom: 1rem;
  border: 1px solid var(--line);
  border-left: 4px solid var(--burgundy);
  border-radius: 12px;
  background: transparent;
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.translation-item:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow);
  border-color: var(--line-strong);
}

.translation-cover {
  width: 112px;
  aspect-ratio: 2 / 3;
  overflow: hidden;
  border-radius: 7px;
  border: 1px solid var(--line);
  background: transparent;
}

.translation-cover img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

/* Main content */
.translation-content {
  min-width: 0;
}

.translation-years {
  margin-bottom: 0.42rem;
}

.translation-year {
  display: inline-block;
  font-size: 0.74rem;
  font-weight: 700;
  color: var(--burgundy);
  background: transparent;
  border: 1px solid var(--line-strong);
  border-radius: 999px;
  padding: 0.12rem 0.55rem;
  margin-right: 0.28rem;
  margin-bottom: 0.25rem;
}

.translation-year:first-child {
  color: #fff;
  background: var(--burgundy);
  border-color: var(--burgundy);
}

.translation-title {
  font-size: 1.15rem;
  font-weight: 600;
  color: #000;
  line-height: 1.35;
  margin-bottom: 0.25rem;
}

.translation-author {
  font-size: 0.91rem;
  color: var(--text-soft);
  line-height: 1.45;
  margin-bottom: 0.4rem;
}

.translation-collaboration {
  font-size: 0.86rem;
  line-height: 1.5;
  color: var(--text-main);
  margin-bottom: 0.48rem;
}

.translation-collaboration strong {
  color: var(--burgundy-dark);
  font-weight: 650;
}

.translation-publisher-text {
  font-size: 0.86rem;
  line-height: 1.5;
  color: var(--text-soft);
  margin-bottom: 0.55rem;
}

.translation-citation-text {
  border-left: 3px solid var(--burgundy);
  padding: 0.38rem 0 0.38rem 0.65rem;
  font-size: 0.82rem;
  line-height: 1.45;
  color: var(--text-main);
}

/* Right-side buttons */
.translation-actions {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-end;
  gap: 0.45rem;
  height: 100%;
}

.translation-actions a,
.copy-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 104px;
  text-decoration: none;
  font-size: 0.78rem;
  font-weight: 700;
  border-radius: 999px;
  padding: 0.24rem 0.75rem;
  transition: all 0.18s ease;
}

.translation-actions a {
  color: var(--burgundy);
  border: 1px solid var(--line-strong);
  background: transparent;
}

.translation-actions a:hover {
  background: var(--burgundy);
  color: #fff;
  border-color: var(--burgundy);
}

.copy-btn {
  color: #fff;
  background: var(--burgundy);
  border: 1px solid var(--burgundy);
  cursor: pointer;
}

.copy-btn:hover {
  background: var(--burgundy-dark);
  border-color: var(--burgundy-dark);
}

.copy-status {
  min-height: 1em;
  font-size: 0.74rem;
  color: var(--text-soft);
  text-align: right;
}

/* Mobile */
@media (max-width: 760px) {
  .translation-item {
    grid-template-columns: 88px 1fr;
    gap: 0.9rem;
    align-items: start;
  }

  .translation-cover {
    width: 88px;
  }

  .translation-actions {
    grid-column: 2;
    align-items: flex-start;
    height: auto;
    margin-top: 0.45rem;
  }

  .translation-actions a,
  .copy-btn {
    min-width: auto;
  }

  .copy-status {
    text-align: left;
  }
}
</style>

<div class="translations-intro" markdown="1">

This page presents my translated books. These works reflect my engagement with **history**, **political thought**, and the circulation of ideas across languages and intellectual traditions.

</div>

<div class="translation-list">

  <!-- En güncel eser en üstte yer almalı. Yıl rozetlerini en güncelden eskiye doğru dizin. -->

  <div class="translation-item">
    <div class="translation-cover">
      <img src="/images/translations/anadoludaki-turk-anitlari.jpg" alt="Anadolu'daki Türk Anıtları cover">
    </div>

    <div class="translation-content">
      <div class="translation-years">
        <span class="translation-year">YEAR</span>
      </div>

      <div class="translation-title">Anadolu'daki Türk Anıtları II: Amasya - Tokat - Sivas</div>
      <div class="translation-author">Albert-Louis Gabriel</div>

      <div class="translation-publisher-text">Türk Arkeoloji ve Kültürel Miras Enstitüsü</div>

      <div class="translation-citation-text" id="citation-1">Gabriel, Albert-Louis. <em>Anadolu'daki Türk Anıtları II: Amasya - Tokat - Sivas</em>. Translated by Nuri Fudayl Kıcıroğlu. İstanbul: Türk Arkeoloji ve Kültürel Miras Enstitüsü, YEAR.</div>
    </div>

    <div class="translation-actions">
      <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      <button class="copy-btn" onclick="copyCitation('citation-1', 'status-1')">Copy citation</button>
      <span class="copy-status" id="status-1"></span>
    </div>
  </div>

  <div class="translation-item">
    <div class="translation-cover">
      <img src="/images/translations/kral.jpg" alt="Kral: Mitler ve Simgeler cover">
    </div>

    <div class="translation-content">
      <div class="translation-years">
        <span class="translation-year">YEAR</span>
      </div>

      <div class="translation-title">Kral: Mitler ve Simgeler</div>
      <div class="translation-author">Jean-Paul Roux</div>

      <div class="translation-publisher-text">Dergâh Yayınları</div>

      <div class="translation-citation-text" id="citation-2">Roux, Jean-Paul. <em>Kral: Mitler ve Simgeler</em>. Translated by Nuri Fudayl Kıcıroğlu. İstanbul: Dergâh Yayınları, YEAR.</div>
    </div>

    <div class="translation-actions">
      <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      <button class="copy-btn" onclick="copyCitation('citation-2', 'status-2')">Copy citation</button>
      <span class="copy-status" id="status-2"></span>
    </div>
  </div>

  <div class="translation-item">
    <div class="translation-cover">
      <img src="/images/translations/somurge-ve-kolelik.jpg" alt="Sömürge ve Kölelik cover">
    </div>

    <div class="translation-content">
      <div class="translation-years">
        <span class="translation-year">YEAR</span>
      </div>

      <div class="translation-title">Sömürge ve Kölelik</div>
      <div class="translation-author">Alexis de Tocqueville</div>

      <div class="translation-collaboration">
        <strong>Collaborated with:</strong> Lütfi Sunar, Burak M. N. Gücin, and Hasan Turunçkapı
      </div>

      <div class="translation-publisher-text">Ayrıntı Yayınları</div>

      <div class="translation-citation-text" id="citation-3">Tocqueville, Alexis de. <em>Sömürge ve Kölelik</em>. Edited by Lütfi Sunar. Translated by Burak M. N. Gücin, Hasan Turunçkapı, and Nuri Fudayl Kıcıroğlu. İstanbul: Ayrıntı Yayınları, YEAR.</div>
    </div>

    <div class="translation-actions">
      <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
      <button class="copy-btn" onclick="copyCitation('citation-3', 'status-3')">Copy citation</button>
      <span class="copy-status" id="status-3"></span>
    </div>
  </div>

  <div class="translation-item">
    <div class="translation-cover">
      <img src="/images/translations/bir-yenicerinin-hatiralari.jpg" alt="Bir Yeniçerinin Hatıraları cover">
    </div>

    <div class="translation-content">
      <div class="translation-years">
        <span class="translation-year">YEAR</span>
        <span class="translation-year">YEAR</span>
        <span class="translation-year">YEAR</span>
      </div>

      <div class="translation-title">Bir Yeniçerinin Hatıraları</div>
      <div class="translation-author">Konstantin Mihailović</div>

      <div class="translation-collaboration">
        <strong>Collaborated with:</strong> Behiç Anıl Ekim
      </div>

      <div class="translation-publisher-text">Ayrıntı Yayınları</div>

      <div class="translation-citation-text" id="citation-4">Mihailović, Konstantin. <em>Bir Yeniçerinin Hatıraları</em>. Translated by Nuri Fudayl Kıcıroğlu and Behiç Anıl Ekim. İstanbul: Ayrıntı Yayınları, YEAR.</div>
    </div>

    <div class="translation-actions">
      <a href="#" target="_blank" rel="noopener noreferrer">Publisher</a>
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
