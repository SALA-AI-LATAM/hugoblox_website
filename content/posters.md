---
title: "SALA 2026 — Posters"
date: 2025-06-23
type: landing

design:
  spacing: "6rem"
  background:
    image:
      filename: iridiscenceDark.jpg

sections:
  - block: markdown
    id: posters
    content:
      title: SALA '26 Poster Session
      text: |
        <p style="text-align: center; font-size: 1.1rem; color: #e5e7eb; margin-bottom: 2rem; font-weight: 500;">
          57 posters across 6 research tracks.
        </p>

        <style>
        /* Reset prose constraints */
        #posters .prose,
        #posters .max-w-prose,
        #posters > div {
          max-width: none !important;
        }

        /* ── Filter bar ── */
        .posters-controls {
          display: flex;
          flex-wrap: wrap;
          gap: 0.75rem;
          align-items: center;
          margin: 0 auto 1.5rem;
          max-width: calc(100% - 4rem);
        }

        .posters-search {
          flex: 1;
          min-width: 200px;
          padding: 0.65rem 1rem;
          border: 1px solid #d1d5db;
          border-radius: 10px;
          font-size: 0.95rem;
          outline: none;
          transition: border-color 0.2s;
          background: white;
          color: #374151;
        }

        .posters-search:focus {
          border-color: #667eea;
          box-shadow: 0 0 0 3px rgba(102,126,234,0.15);
        }

        .filter-btn {
          padding: 0.55rem 1.1rem;
          border-radius: 999px;
          border: 1.5px solid #d1d5db;
          background: white;
          color: #6b7280;
          font-size: 0.88rem;
          font-weight: 500;
          cursor: pointer;
          transition: all 0.2s;
          white-space: nowrap;
        }

        .filter-btn:hover {
          background: #f3f4f6;
          color: #374151;
        }

        .filter-btn.active {
          border-color: #667eea;
          background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
          color: white;
        }

        /* ── Stats bar ── */
        .posters-stats {
          text-align: center;
          font-size: 0.88rem;
          color: #9ca3af;
          margin: 0 auto 1rem;
          max-width: calc(100% - 4rem);
        }

        /* ── Category sections ── */
        .posters-container {
          margin: 0 auto;
          max-width: calc(100% - 4rem);
        }

        .category-section {
          margin-bottom: 2rem;
          background: white;
          border-radius: 16px;
          box-shadow: 0 8px 32px rgba(0,0,0,0.10);
          overflow: hidden;
        }

        .category-header {
          display: flex;
          align-items: center;
          gap: 0.75rem;
          padding: 1rem 1.5rem;
          font-weight: 700;
          font-size: 1rem;
          color: white;
        }

        .category-badge {
          background: rgba(255,255,255,0.25);
          border-radius: 999px;
          padding: 0.15rem 0.65rem;
          font-size: 0.8rem;
          font-weight: 600;
        }

        /* Category colour themes */
        .cat-aa  .category-header { background: linear-gradient(135deg, #f59e0b 0%, #d97706 100%); }
        .cat-dl  .category-header { background: linear-gradient(135deg, #6366f1 0%, #4f46e5 100%); }
        .cat-pe  .category-header { background: linear-gradient(135deg, #10b981 0%, #059669 100%); }
        .cat-ft  .category-header { background: linear-gradient(135deg, #ef4444 0%, #dc2626 100%); }
        .cat-gm  .category-header { background: linear-gradient(135deg, #8b5cf6 0%, #7c3aed 100%); }
        .cat-re  .category-header { background: linear-gradient(135deg, #0ea5e9 0%, #0284c7 100%); }

        /* ── Poster table ── */
        .poster-table {
          width: 100%;
          border-collapse: collapse;
          font-size: 0.93rem;
        }

        .poster-table thead tr {
          background: #f9fafb;
          border-bottom: 2px solid #e5e7eb;
        }

        .poster-table th {
          padding: 0.65rem 1rem;
          text-align: left;
          font-weight: 600;
          color: #6b7280;
          font-size: 0.82rem;
          text-transform: uppercase;
          letter-spacing: 0.04em;
        }

        .poster-table th.col-spot  { width: 60px; text-align: center; }
        .poster-table th.col-code  { width: 90px; }
        .poster-table th.col-presenter { width: 130px; }

        .poster-row {
          border-bottom: 1px solid #f0f0f0;
          transition: background 0.2s;
        }

        .poster-row:last-child {
          border-bottom: none;
        }

        .poster-row:hover {
          background: #f8faff;
        }

        .poster-row.hidden {
          display: none;
        }

        .poster-row td {
          padding: 0.75rem 1rem;
          vertical-align: middle;
          color: #374151;
        }

        .td-spot {
          text-align: center;
          font-weight: 700;
          color: #9ca3af;
          font-size: 0.85rem;
        }

        .td-code {
          font-family: 'Courier New', monospace;
          font-size: 0.82rem;
          font-weight: 700;
          color: #6366f1;
          white-space: nowrap;
        }

        .td-title {
          line-height: 1.45;
        }

        .td-presenter {
          font-weight: 600;
          color: #374151;
          white-space: nowrap;
        }

        /* Mobile */
        @media (max-width: 767px) {
          .posters-controls,
          .posters-stats,
          .posters-container {
            max-width: calc(100% - 2rem);
          }

          .poster-table thead {
            display: none;
          }

          .poster-table,
          .poster-table tbody,
          .poster-row,
          .poster-row td {
            display: block;
            width: 100%;
          }

          .poster-row {
            padding: 0.75rem 1rem;
            border-bottom: 1px solid #f0f0f0;
          }

          .poster-row td {
            padding: 0.1rem 0;
          }

          .td-spot {
            display: inline-block;
            background: #f3f4f6;
            border-radius: 999px;
            padding: 0.1rem 0.5rem;
            font-size: 0.78rem;
            margin-bottom: 0.25rem;
          }

          .td-code {
            display: inline-block;
            margin-left: 0.4rem;
          }
        }

        /* No-results */
        .no-results {
          text-align: center;
          padding: 2rem;
          color: #9ca3af;
          font-style: italic;
          display: none;
        }
        </style>

        <!-- Controls -->
        <div class="posters-controls">
          <input
            class="posters-search"
            type="text"
            id="poster-search"
            placeholder="Search by title, code, or presenter…"
            aria-label="Search posters"
          />
        </div>

        <div class="posters-controls" id="filter-buttons" style="margin-top:0;">
          <!-- category filter buttons injected by JS -->
        </div>

        <div class="posters-stats" id="posters-stats"></div>

        <div class="posters-container" id="posters-container">
          <!-- poster sections injected by JS -->
        </div>

        <div class="no-results" id="no-results">No posters match your search.</div>

        <script>
        (function () {
          /* ── Colour classes per category prefix ── */
          const catClass = {
            'Applied AI & Data Science':          'cat-aa',
            'Deep Learning & Representation Learning': 'cat-dl',
            'Perception (Vision + Language)':          'cat-pe',
            'Foundations & Theory':               'cat-ft',
            'Generative Models':                  'cat-gm',
            'Responsible AI & Ethics':            'cat-re',
          };

          const catEmoji = {
            'Applied AI & Data Science':          '🤖',
            'Deep Learning & Representation Learning': '🧠',
            'Perception (Vision + Language)':          '👁️',
            'Foundations & Theory':               '📐',
            'Generative Models':                  '✨',
            'Responsible AI & Ethics':            '⚖️',
          };

          /* ── Parse CSV (handles quoted fields) ── */
          function parseCSV(text) {
            const rows = [];
            const lines = text.trim().split('\n');
            const headers = splitCSVLine(lines[0]);
            for (let i = 1; i < lines.length; i++) {
              if (!lines[i].trim()) continue;
              const vals = splitCSVLine(lines[i]);
              const obj = {};
              headers.forEach((h, idx) => { obj[h.trim()] = (vals[idx] || '').trim(); });
              rows.push(obj);
            }
            return rows;
          }

          function splitCSVLine(line) {
            const result = [];
            let cur = '';
            let inQuote = false;
            for (let i = 0; i < line.length; i++) {
              const ch = line[i];
              if (ch === '"') { inQuote = !inQuote; }
              else if (ch === ',' && !inQuote) { result.push(cur); cur = ''; }
              else { cur += ch; }
            }
            result.push(cur);
            return result;
          }

          /* ── Build page ── */
          function buildPage(posters) {
            const container = document.getElementById('posters-container');
            const filterDiv = document.getElementById('filter-buttons');
            if (!container || !filterDiv) return;

            /* Group by category (preserve insertion order) */
            const groups = {};
            const catOrder = [];
            posters.forEach(p => {
              if (!groups[p.category]) { groups[p.category] = []; catOrder.push(p.category); }
              groups[p.category].push(p);
            });

            /* "All" filter button */
            filterDiv.innerHTML = '';
            const allBtn = document.createElement('button');
            allBtn.className = 'filter-btn active';
            allBtn.textContent = 'All';
            allBtn.dataset.cat = '';
            allBtn.addEventListener('click', () => applyFilter('', allBtn));
            filterDiv.appendChild(allBtn);

            /* Per-category sections + filter buttons */
            container.innerHTML = '';
            catOrder.forEach(cat => {
              const items = groups[cat];
              const cls = catClass[cat] || 'cat-aa';
              const emoji = catEmoji[cat] || '📄';
              /* Filter button */
              const btn = document.createElement('button');
              btn.className = 'filter-btn';
              btn.dataset.cat = cat;
              btn.textContent = `${emoji} ${cat} (${items.length})`;
              btn.addEventListener('click', () => applyFilter(cat, btn));
              filterDiv.appendChild(btn);

              /* Section */
              const section = document.createElement('div');
              section.className = `category-section ${cls}`;
              section.dataset.cat = cat;

              const header = document.createElement('div');
              header.className = 'category-header';
              header.innerHTML = `${emoji} ${cat} <span class="category-badge">${items.length} posters</span>`;
              section.appendChild(header);

              const table = document.createElement('table');
              table.className = 'poster-table';
              table.innerHTML = `
                <thead>
                  <tr>
                    <th class="col-spot">Spot</th>
                    <th class="col-code">Code</th>
                    <th>Title</th>
                    <th class="col-presenter">Presenter</th>
                  </tr>
                </thead>
              `;
              const tbody = document.createElement('tbody');

              items.forEach(p => {
                const tr = document.createElement('tr');
                tr.className = 'poster-row';
                tr.dataset.search = `${p.code} ${p.title} ${p.presenter} ${p.category}`.toLowerCase();
                tr.innerHTML = `
                  <td class="td-spot">${p.spot}</td>
                  <td class="td-code">${p.code}</td>
                  <td class="td-title">${p.title}</td>
                  <td class="td-presenter">${p.presenter || '<span style="color:#d1d5db">—</span>'}</td>
                `;
                tbody.appendChild(tr);
              });

              table.appendChild(tbody);
              section.appendChild(table);
              container.appendChild(section);
            });

            updateStats();
          }

          /* ── Filter by category ── */
          let activeCategory = '';

          function applyFilter(cat, clickedBtn) {
            activeCategory = cat;
            document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
            clickedBtn.classList.add('active');
            document.querySelectorAll('.category-section').forEach(sec => {
              sec.style.display = (!cat || sec.dataset.cat === cat) ? '' : 'none';
            });
            applySearch(document.getElementById('poster-search').value);
          }

          /* ── Search ── */
          function applySearch(query) {
            const q = query.toLowerCase().trim();
            let visible = 0;

            document.querySelectorAll('.poster-row').forEach(row => {
              const catMatch = !activeCategory || row.closest('.category-section')?.dataset.cat === activeCategory;
              const textMatch = !q || row.dataset.search.includes(q);
              const show = catMatch && textMatch;
              row.classList.toggle('hidden', !show);
              if (show) visible++;
            });

            /* Hide empty sections */
            document.querySelectorAll('.category-section').forEach(sec => {
              if (activeCategory && sec.dataset.cat !== activeCategory) return;
              const anyVisible = Array.from(sec.querySelectorAll('.poster-row')).some(r => !r.classList.contains('hidden'));
              sec.style.display = anyVisible ? '' : 'none';
            });

            document.getElementById('no-results').style.display = visible === 0 ? 'block' : 'none';
            updateStats(visible);
          }

          function updateStats(visible) {
            const total = document.querySelectorAll('.poster-row').length;
            const shown = (visible !== undefined) ? visible : total;
            const el = document.getElementById('posters-stats');
            if (el) el.textContent = shown === total ? `${total} posters` : `Showing ${shown} of ${total} posters`;
          }

          /* ── Wire up search input ── */
          function wireSearch() {
            const input = document.getElementById('poster-search');
            if (!input) return;
            input.addEventListener('input', () => applySearch(input.value));
          }

          /* ── Load CSV and initialise ── */
          document.addEventListener('DOMContentLoaded', async function () {
            try {
              const res = await fetch('/posters.csv');
              if (!res.ok) throw new Error('Failed to load posters.csv');
              const text = await res.text();
              const posters = parseCSV(text);
              buildPage(posters);
              wireSearch();
            } catch (err) {
              console.error(err);
              const c = document.getElementById('posters-container');
              if (c) c.innerHTML = '<p style="text-align:center;padding:2rem;color:#9ca3af;">Poster list is loading — please refresh the page.</p>';
            }
          });
        })();
        </script>
---
