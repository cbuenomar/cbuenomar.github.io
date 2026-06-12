---
title: Research
cms_exclude: true
---

<style>
.pub-controls { margin-bottom: 2rem; }
.filter-group {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-bottom: 0.85rem;
}
.filter-btn {
  border: 1px solid light-dark(#d0d0d0, #3a4150);
  background: transparent;
  border-radius: 2rem;
  padding: 0.22rem 0.9rem;
  font-size: 0.78rem;
  font-weight: 500;
  cursor: pointer;
  color: light-dark(#666, #b8c0cc);
  transition: border-color 0.15s, color 0.15s, background 0.15s;
  letter-spacing: 0.02em;
}
.filter-btn:hover:not(.active) {
  border-color: light-dark(#333, #ffffff);
  color: light-dark(#333, #ffffff);
}
.filter-btn.active {
  background: light-dark(#1a1a1a, #ffffff);
  color: light-dark(#ffffff, #0a0a0a);
  border-color: light-dark(#1a1a1a, #ffffff);
}
.pub-search {
  width: 100%;
  max-width: 440px;
  padding: 0.4rem 0.85rem;
  border: 1px solid light-dark(#ddd, #3a4150);
  border-radius: 0.3rem;
  font-size: 0.875rem;
  outline: none;
  background: transparent;
  color: light-dark(#0a0a0a, #ffffff);
  transition: border-color 0.15s;
}
.pub-search:focus { border-color: light-dark(#333, #ffffff); }
.pub-count {
  font-size: 0.78rem;
  color: light-dark(#bbb, #6b7480);
  margin-top: 0.45rem;
  letter-spacing: 0.03em;
}
.pub-list { list-style: none; padding: 0; margin: 0; }
.pub-item {
  padding: 1rem 0.75rem 1rem 1.1rem;
  border-left: 2px solid transparent;
  border-bottom: 1px solid light-dark(#f0f0f0, #1f2533);
  transition: background 0.12s, border-left-color 0.12s;
}
.pub-item:last-child { border-bottom: none; }
.pub-item:hover {
  background: light-dark(#fafafa, #161c29);
  border-left-color: light-dark(#1a1a1a, #ffffff);
}
.pub-meta-top {
  display: flex;
  align-items: center;
  gap: 0.35rem;
  margin-bottom: 0.3rem;
}
.pub-badge {
  font-size: 0.62rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  color: light-dark(#888, #8b95a5);
}
.pub-sep { font-size: 0.62rem; color: light-dark(#ccc, #4a5263); user-select: none; }
.pub-year { font-size: 0.75rem; color: light-dark(#888, #8b95a5); font-weight: 500; }
.pub-status {
  font-size: 0.6rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  padding: 0.1rem 0.45rem;
  border-radius: 2rem;
  margin-left: 0.25rem;
}
.status-review { background: #fff3cd; color: #856404; }
.status-unpublished { background: #e2e3e5; color: #555; }

/* Titles: black in light mode, white in dark mode */
.pub-title-text {
  font-weight: 600;
  font-size: 0.95rem;
  line-height: 1.45;
  color: light-dark(#0a0a0a, #ffffff);
}

/* Linked titles: purple-ish in light mode, blue in dark mode */
.pub-title-link {
  font-weight: 600;
  font-size: 0.95rem;
  line-height: 1.45;
  color: light-dark(#6d4ce0, #60a5fa);
  text-decoration: none;
}
.pub-title-link:hover { text-decoration: underline; }

.pub-authors {
  font-size: 0.85rem;
  color: light-dark(#555, #b8c0cc);
  margin-top: 0.2rem;
}
.pub-authors strong { color: light-dark(#222, #e2e6ec); }
.pub-venue {
  font-size: 0.85rem;
  color: light-dark(#666, #8b95a5);
  font-style: italic;
  margin-top: 0.05rem;
}
.pub-hidden { display: none; }
</style>

<div class="pub-controls">
  <div class="filter-group">
    <button class="filter-btn active" data-value="all">All</button>
    <button class="filter-btn" data-value="article">Journal Articles</button>
    <button class="filter-btn" data-value="chapter">Book Chapters</button>
    <button class="filter-btn" data-value="report">Reports &amp; Working Papers</button>
  </div>
  <input class="pub-search" type="text" id="pubSearch" placeholder="Search by title, author, or journal…" autocomplete="off">
  <p class="pub-count" id="pubCount"></p>
</div>

<ul class="pub-list" id="pubList">

  <!-- 2026 -->
  <li class="pub-item" data-type="report" data-year="2026">
    <div>
      <div class="pub-meta-top">
        <span class="pub-badge">Report</span>
        <span class="pub-sep">·</span>
        <span class="pub-year">2026</span>
      </div>
      <a class="pub-title-link" href="https://www.equitat.org/publicacions/labandonament-escolar-a-secundaria-radiografia-dun-estancament" target="_blank" rel="noopener">L'abandonament escolar a Catalunya: Radiografia d'un estacament [School Dropout in Catalonia: A Radiography of stagnation]</a>
      <div class="pub-authors">Zancajo, A., &amp; <strong>Bueno, C.</strong></div>
      <div class="pub-venue">Fundació Jaume Bofill</div>
    </div>
  </li>

  <!-- 2025 -->
  <li class="pub-item" data-type="article" data-year="2025">
    <div>
      <div class="pub-meta-top">
        <span class="pub-badge">Article</span>
        <span class="pub-sep">·</span>
        <span class="pub-year">2025</span>
        <span class="pub-status status-review">Under Review</span>
      </div>
      <span class="pub-title-text">Do gentrifiers fly from local schools? The case of Barcelona</span>
      <div class="pub-authors">Bonal, X., González, S., &amp; <strong>Bueno, C.</strong></div>
    </div>
  </li>

  <!-- 2024 -->
  <li class="pub-item" data-type="report" data-year="2024">
    <div>
      <div class="pub-meta-top">
        <span class="pub-badge">Report</span>
        <span class="pub-sep">·</span>
        <span class="pub-year">2024</span>
      </div>
      <a class="pub-title-link" href="https://www.equitat.org/publicacions/abandonament-al-batxillerat-i-als-cicles-formatius-de-grau-mitja" target="_blank" rel="noopener">L'abandonament al batxillerat i als cicles formatius de grau mitjà [School Dropout in Upper Secondary Education in Catalonia]</a>
      <div class="pub-authors">Zancajo, A., &amp; <strong>Bueno, C.</strong></div>
      <div class="pub-venue">Fundació Jaume Bofill</div>
    </div>
  </li>

  <li class="pub-item" data-type="report" data-year="2024">
    <div>
      <div class="pub-meta-top">
        <span class="pub-badge">Report</span>
        <span class="pub-sep">·</span>
        <span class="pub-year">2024</span>
        <span class="pub-status status-unpublished">Unpublished</span>
      </div>
      <span class="pub-title-text">Strengthening the instructional leadership role of school leaders in Zambia</span>
      <div class="pub-authors"><strong>Bueno, C.</strong>, &amp; Bergmann, J.</div>
      <div class="pub-venue">UNICEF-Innocenti Technical Brief</div>
    </div>
  </li>

  <!-- 2023 -->
  <li class="pub-item" data-type="report" data-year="2023">
    <div>
      <div class="pub-meta-top">
        <span class="pub-badge">Report</span>
        <span class="pub-sep">·</span>
        <span class="pub-year">2023</span>
      </div>
      <a class="pub-title-link" href="https://www.equitat.org/publicacions/l-abandonament-a-4t-d-eso-les-desigualtats-en-la-transicio-a-l-educacio-postobligatoria" target="_blank" rel="noopener">L'abandonament a 4t d'ESO: les desigualtats en la transició a l'educació postobligatòria [School dropout in the transition from lower to upper secondary education in Catalonia]</a>
      <div class="pub-authors">Zancajo, A., &amp; <strong>Bueno, C.</strong></div>
      <div class="pub-venue">Fundació Jaume Bofill</div>
    </div>
  </li>

  <li class="pub-item" data-type="article" data-year="2023">
    <div>
      <div class="pub-meta-top">
        <span class="pub-badge">Article</span>
        <span class="pub-sep">·</span>
        <span class="pub-year">2023</span>
      </div>
      <a class="pub-title-link" href="https://bera-journals.onlinelibrary.wiley.com/doi/full/10.1002/berj.3889" target="_blank" rel="noopener">Fragmented spaces in the urban landscape: A socio-spatial analysis of educational supply in the city of Madrid</a>
      <div class="pub-authors"><strong>Bueno, C.</strong>, &amp; Bonal, X.</div>
      <div class="pub-venue">British Educational Research Journal, 49(5), 1108–1132</div>
    </div>
  </li>

  <!-- 2021 -->
  <li class="pub-item" data-type="chapter" data-year="2021">
    <div>
      <div class="pub-meta-top">
        <span class="pub-badge">Chapter</span>
        <span class="pub-sep">·</span>
        <span class="pub-year">2021</span>
      </div>
      <a class="pub-title-link" href="https://unesdoc.unesco.org/ark:/48223/pf0000379386?posInSet=1&queryId=a873a85e-ed46-49e7-a120-a689068cee3b" target="_blank" rel="noopener">Curriculum as the Spirit and Subject Matter of Education</a>
      <div class="pub-authors"><strong>Bueno, C.</strong>, Opertti, R., &amp; Arsendeau, P.</div>
      <div class="pub-venue">In <em>Curriculum On The Move</em>. UNESCO-IBE: Geneva</div>
    </div>
  </li>

  <li class="pub-item" data-type="chapter" data-year="2021">
    <div>
      <div class="pub-meta-top">
        <span class="pub-badge">Chapter</span>
        <span class="pub-sep">·</span>
        <span class="pub-year">2021</span>
      </div>
      <a class="pub-title-link" href="https://unesdoc.unesco.org/ark:/48223/pf0000378427?posInSet=6&queryId=ba585d3a-a33b-42cb-aaad-56e66c1af505" target="_blank" rel="noopener">Inclusion in Education</a>
      <div class="pub-authors">Opertti, R., <strong>Bueno, C.</strong>, &amp; Arsendeau, P.</div>
      <div class="pub-venue">In <em>Curriculum On The Move</em>. UNESCO-IBE: Geneva</div>
    </div>
  </li>

  <!-- 2020 -->
  <li class="pub-item" data-type="chapter" data-year="2020">
    <div>
      <div class="pub-meta-top">
        <span class="pub-badge">Chapter</span>
        <span class="pub-sep">·</span>
        <span class="pub-year">2020</span>
      </div>
      <a class="pub-title-link" href="https://www.taylorfrancis.com/chapters/edit/10.4324/9780367815325-4/discrit-sujay-sabnis-carlos-bueno-martinez" target="_blank" rel="noopener">Disability Critical Race Theory</a>
      <div class="pub-authors">Sabnis, S., &amp; <strong>Bueno, C.</strong></div>
      <div class="pub-venue">In Proctor, S. L., &amp; Rivera, D. P. (Eds.), <em>Critical Theories for School-Based Practice: A Foundation for Equity and Inclusion in Practice and Supervision</em></div>
    </div>
  </li>

</ul>

<script>
(function () {
  const buttons = document.querySelectorAll('.filter-btn');
  const searchInput = document.getElementById('pubSearch');
  const items = document.querySelectorAll('.pub-item');
  const countEl = document.getElementById('pubCount');
  let activeType = 'all';

  function update() {
    const q = searchInput.value.toLowerCase().trim();
    let n = 0;
    items.forEach(function (item) {
      const typeMatch = activeType === 'all' || item.dataset.type === activeType;
      const textMatch = !q || item.textContent.toLowerCase().includes(q);
      if (typeMatch && textMatch) {
        item.classList.remove('pub-hidden');
        n++;
      } else {
        item.classList.add('pub-hidden');
      }
    });
    countEl.textContent = n + ' of ' + items.length + ' publications';
  }

  buttons.forEach(function (btn) {
    btn.addEventListener('click', function () {
      buttons.forEach(function (b) { b.classList.remove('active'); });
      btn.classList.add('active');
      activeType = btn.dataset.value;
      update();
    });
  });

  searchInput.addEventListener('input', update);
  update();
})();
</script>
