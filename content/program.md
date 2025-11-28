---
title: "SALA 2026"
date: 2025-06-23
type: landing

design:
  # Default section spacing
  spacing: "6rem"
  background:
    image:
      filename: iridiscenceDark.jpg

sections:
  - block: markdown
    id: agenda
    content:
      title: SALA '26 Program
      text: |
        <p style="text-align: center; font-size: 1.1rem; color: #e5e7eb; margin-bottom: 2rem; font-weight: 500;">
          The time zone in Quito, Ecuador is UTC-5.
        </p>
        
        <style>
        .sala-agenda {
          margin: 2rem 0;
          overflow: hidden;
          border-radius: 16px;
          box-shadow: 0 8px 32px rgba(0,0,0,0.12);
          background: white;
          border: 1px solid rgba(255,255,255,0.2);
        }
        
        .agenda-table {
          width: 100%;
          min-width: 800px;
          border-collapse: separate;
          border-spacing: 0;
          font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', sans-serif;
          font-size: 0.95rem;
          overflow-x: auto;
          border: 1px solid #e5e7eb;
          border-radius: 16px;
        }
        
        .agenda-table th {
          background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
          color: white;
          padding: 1.2rem;
          text-align: center;
          font-weight: 600;
          border: none;
          border-bottom: 1px solid rgba(255,255,255,0.1);
          position: sticky;
          top: 0;
          z-index: 10;
        }
        
        .agenda-table th:first-child {
          background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
          width: 120px;
          min-width: 120px;
          border-top-left-radius: 15px;
        }
        
        .agenda-table th:last-child {
          border-top-right-radius: 15px;
        }
        
        .agenda-table td {
          padding: 1rem;
          border-right: 1px solid #f0f0f0;
          border-bottom: 1px solid #f0f0f0;
          text-align: center;
          vertical-align: middle;
          transition: all 0.3s ease;
        }
        
        .agenda-table td:first-child {
          background-color: #f8f9fa;
          font-weight: 600;
          color: #2c3e50;
          white-space: nowrap;
          width: 120px;
          min-width: 120px;
        }
        
        .agenda-table td:last-child {
          border-right: none;
        }
        
        .agenda-table tr:last-child td {
          border-bottom: none;
        }
        
        .agenda-table tr:last-child td:first-child {
          border-bottom-left-radius: 15px;
        }
        
        .agenda-table tr:last-child td:last-child {
          border-bottom-right-radius: 15px;
        }
        
        .agenda-table td[data-type="welcome"] {
          background-color: #ffffff !important;
          color: #374151;
          font-weight: 500;
          border: 1px solid #d1d5db;
        }
        
        .agenda-table td[data-type="foundational"] {
          background-color: #fef3e2 !important;
          color: #9a3412;
          font-weight: 500;
        }
        
        .agenda-table td[data-type="specialized"] {
          background-color: #f0f0ff !important;
          color: #4c1d95;
          font-weight: 500;
        }
        
        .agenda-table td[data-type="break"] {
          background-color: #ffffff !important;
          color: #374151;
          font-weight: 500;
          border: 1px solid #d1d5db;
        }
        
        .agenda-table td[data-type="special"] {
          background-color: #fdf4ff !important;
          color: #7c2d92;
          font-weight: 500;
        }
        
        .agenda-table td[data-type="keynote"] {
          background-color: #fdf4ff !important;
          color: #7c2d92;
          font-weight: 600;
          font-size: 1rem;
        }
        
        .agenda-table td[data-type="hackathon"] {
          background-color: #ecfdf5 !important;
          color: #065f46;
          font-weight: 500;
        }
        
        .agenda-table tr:hover td:not(:first-child) {
          transform: translateY(-1px);
          box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        
        .agenda-table td:empty {
          background-color: #fafafa !important;
          border-color: #f0f0f0;
        }
        
        /* Mobile Card Layout */
        @media (max-width: 767px) {
          .sala-agenda {
            margin: 1rem -1rem;
            border-radius: 0;
            background: transparent;
            box-shadow: none;
            border: none;
          }
          
          /* Hide original table on mobile */
          .agenda-table {
            display: none;
          }
          
          /* Mobile cards container */
          .mobile-schedule {
            display: block;
          }
          
          /* Navigation buttons for mobile */
          .mobile-nav-buttons {
            display: flex;
            background: white;
            border-radius: 12px 12px 0 0;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            overflow-x: auto;
            margin-bottom: 0;
          }
          
          .day-btn {
            flex: 1;
            min-width: 80px;
            padding: 1rem 0.5rem;
            text-align: center;
            background: #f8f9fa;
            color: #6b7280;
            font-weight: 500;
            font-size: 0.9rem;
            cursor: pointer;
            border: none;
            border-bottom: 3px solid transparent;
            transition: all 0.3s ease;
            white-space: nowrap;
            user-select: none;
          }
          
          .day-btn:first-child {
            border-radius: 12px 0 0 0;
          }
          
          .day-btn:last-child {
            border-radius: 0 12px 0 0;
          }
          
          .day-btn.active {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border-bottom-color: #4f46e5;
            font-weight: 600;
          }
          
          .day-btn:hover:not(.active) {
            background: #e5e7eb;
            color: #374151;
          }
          
          /* Screen reader only content */
          .sr-only {
            position: absolute;
            width: 1px;
            height: 1px;
            padding: 0;
            margin: -1px;
            overflow: hidden;
            clip: rect(0, 0, 0, 0);
            white-space: nowrap;
            border: 0;
          }
          
          .day-card {
            background: white;
            margin-bottom: 2rem;
            border-radius: 16px;
            box-shadow: 0 8px 32px rgba(0,0,0,0.12);
            border: 1px solid rgba(255,255,255,0.2);
            overflow: hidden;
          }
          
          .day-header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1.5rem;
            text-align: center;
            font-weight: 600;
            font-size: 1.1rem;
          }
          
          .day-schedule {
            padding: 0;
          }
          
          .time-slot {
            border-bottom: 1px solid #f0f0f0;
            padding: 1rem;
            display: flex;
            align-items: flex-start;
            gap: 1rem;
            transition: all 0.3s ease;
          }
          
          .time-slot:last-child {
            border-bottom: none;
          }
          
          .time-slot:hover {
            background: #fafafa;
            transform: translateY(-1px);
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
          }
          
          .time-badge {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            padding: 0.5rem 0.8rem;
            border-radius: 12px;
            font-size: 0.9rem;
            font-weight: 600;
            white-space: nowrap;
            min-width: 90px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.15);
          }
          
          .session-content {
            flex: 1;
            min-width: 0;
          }
          
          .session-title {
            font-size: 1rem;
            line-height: 1.4;
            margin: 0;
            font-weight: 500;
            color: #374151;
          }
          
          .session-speaker {
            font-style: italic;
            color: #6b7280;
            font-size: 0.9rem;
            margin-top: 0.25rem;
          }
          
          /* Session type styling for mobile cards */
          .time-slot[data-session="welcome"] .session-title {
            color: #374151;
          }
          
          .time-slot[data-session="foundational"] {
            background-color: #fef3e2;
            border-left: 4px solid #f59e0b;
          }
          
          .time-slot[data-session="foundational"] .session-title {
            color: #9a3412;
            font-weight: 600;
          }
          
          .time-slot[data-session="specialized"] {
            background-color: #f0f0ff;
            border-left: 4px solid #6366f1;
          }
          
          .time-slot[data-session="specialized"] .session-title {
            color: #4c1d95;
            font-weight: 600;
          }
          
          .time-slot[data-session="break"] {
            background-color: #ffffff;
            border-left: 4px solid #d1d5db;
          }
          
          .time-slot[data-session="break"] .session-title {
            color: #374151;
          }
          
          .time-slot[data-session="special"] {
            background-color: #fdf4ff;
            border-left: 4px solid #a855f7;
          }
          
          .time-slot[data-session="special"] .session-title {
            color: #7c2d92;
            font-weight: 600;
          }
          
          .time-slot[data-session="keynote"] {
            background-color: #fdf4ff;
            border-left: 4px solid #a855f7;
          }
          
          .time-slot[data-session="keynote"] .session-title {
            color: #7c2d92;
            font-weight: 700;
            font-size: 1.1rem;
          }
          
          .time-slot[data-session="hackathon"] {
            background-color: #ecfdf5;
            border-left: 4px solid #10b981;
          }
          
          .time-slot[data-session="hackathon"] .session-title {
            color: #065f46;
            font-weight: 600;
          }
        }
        
        /* Tablet - optimized table with horizontal scroll */
        @media (min-width: 768px) and (max-width: 1023px) {
          .mobile-schedule {
            display: none;
          }
          
          .sala-agenda {
            overflow-x: auto;
            -webkit-overflow-scrolling: touch;
            border-radius: 16px;
            box-shadow: 0 8px 32px rgba(0,0,0,0.12);
          }
          
          .agenda-table {
            min-width: 700px; /* Reduced from 800px */
            font-size: 0.85rem;
          }
          
          .agenda-table th,
          .agenda-table td {
            padding: 0.7rem 0.5rem;
          }
          
          /* Sticky time column header */
          .agenda-table th:first-child {
            width: 100px;
            min-width: 100px;
            position: sticky;
            left: 0;
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            z-index: 15;
            color: white;
            border-top-left-radius: 15px;
          }
          
          /* Sticky time column cells */
          .agenda-table td:first-child {
            width: 100px;
            min-width: 100px;
            position: sticky;
            left: 0;
            background-color: #f8f9fa !important;
            z-index: 10;
            font-weight: 600;
            color: #2c3e50;
            box-shadow: 2px 0 4px rgba(0,0,0,0.1);
          }
          
          /* Scroll indicator */
          .sala-agenda::after {
            content: "← Swipe to see all days →";
            display: block;
            text-align: center;
            padding: 0.5rem;
            font-size: 0.8rem;
            color: #6b7280;
            font-style: italic;
            background: linear-gradient(90deg, transparent, rgba(0,0,0,0.05), transparent);
          }
          
          /* Hide scroll indicator when not needed */
          @media (min-width: 900px) {
            .agenda-table {
              min-width: 100%;
            }
            
            .sala-agenda::after {
              display: none;
            }
          }
        }
        
        /* Desktop - hide mobile cards, show table */
        @media (min-width: 1024px) {
          .mobile-schedule {
            display: none;
          }
          
          .agenda-table {
            display: table;
          }
        }
        </style>

        <div class="sala-agenda">
          <table class="agenda-table" id="schedule-table">
            <thead>
              <tr>
                <th>Time</th>
                <th>Monday<br>March 9</th>
                <th>Tuesday<br>March 10</th>
                <th>Wednesday<br>March 11</th>
                <th>Thursday<br>March 12</th>
              </tr>
            </thead>
            <tbody id="schedule-tbody">
              <!-- Schedule will be loaded dynamically from CSV -->
            </tbody>
          </table>
        </div>

        <!-- Mobile Card Layout -->
        <div class="mobile-schedule" id="mobile-schedule">
          <!-- Screen reader announcements -->
          <div id="schedule-announcement" class="sr-only" aria-live="polite" aria-atomic="true"></div>
          
          <!-- Day Navigation Buttons -->
          <div class="mobile-nav-buttons" role="tablist" aria-label="Conference days navigation" id="mobile-nav-buttons">
            <!-- Buttons will be loaded dynamically -->
          </div>
          
          <!-- Day cards container -->
          <div id="mobile-days-container">
            <!-- Day cards will be loaded dynamically from CSV -->
          </div>
        </div>

        <script>
        // Mobile day navigation function
        function showDay(day) {
          document.querySelectorAll('.day-card[id^="day-"]').forEach(card => {
            card.style.display = 'none';
            card.setAttribute('aria-hidden', 'true');
          });
          
          document.querySelectorAll('.day-btn').forEach(btn => {
            btn.classList.remove('active');
            btn.setAttribute('aria-selected', 'false');
          });
          
          const selectedCard = document.getElementById('day-' + day);
          if (selectedCard) {
            selectedCard.style.display = 'block';
            selectedCard.setAttribute('aria-hidden', 'false');
          }
          
          event.target.classList.add('active');
          event.target.setAttribute('aria-selected', 'true');
          
          const announcement = `Showing schedule for ${event.target.textContent.replace(/\n/g, ' ')}`;
          const ariaLive = document.getElementById('schedule-announcement');
          if (ariaLive) {
            ariaLive.textContent = announcement;
          }
        }

        // Parse CSV data
        function parseCSV(text) {
          const lines = text.trim().split('\n');
          const headers = lines[0].split(',');
          const data = [];
          
          for (let i = 1; i < lines.length; i++) {
            const values = lines[i].split(',');
            const row = {};
            headers.forEach((header, index) => {
              row[header] = values[index] || '';
            });
            data.push(row);
          }
          
          return data;
        }

        // Extract session title and speaker
        function parseSession(sessionText) {
          const speakerMatch = sessionText.match(/^(.+?)\s*\(([^)]+)\)$/);
          if (speakerMatch) {
            return {
              title: speakerMatch[1].trim(),
              speaker: speakerMatch[2].trim()
            };
          }
          return { title: sessionText.trim(), speaker: null };
        }

        // Generate desktop table with rowspan
        function generateTable(scheduleData) {
          const tbody = document.getElementById('schedule-tbody');
          if (!tbody) return;
          
          tbody.innerHTML = '';
          
          const days = ['Monday March 9', 'Tuesday March 10', 'Wednesday March 11', 'Thursday March 12'];
          const typeKeys = ['Type_Mon', 'Type_Tue', 'Type_Wed', 'Type_Thu'];
          
          // Track which rows are spanned (to create empty rows)
          const spanTracker = new Array(scheduleData.length).fill(0);
          
          for (let i = 0; i < scheduleData.length; i++) {
            // Skip if this row is spanned from above
            if (spanTracker[i] > 0) {
              const tr = document.createElement('tr');
              tr.appendChild(document.createComment(' Cells spanned by rowspan above '));
              tbody.appendChild(tr);
              continue;
            }
            
            const row = scheduleData[i];
            const tr = document.createElement('tr');
            
            // Check for consecutive same sessions for rowspan
            let rowspan = 1;
            for (let j = i + 1; j < scheduleData.length; j++) {
              const nextRow = scheduleData[j];
              let allSame = true;
              
              for (let k = 0; k < days.length; k++) {
                if (nextRow[days[k]] !== row[days[k]] || nextRow[typeKeys[k]] !== row[typeKeys[k]]) {
                  allSame = false;
                  break;
                }
              }
              
              if (allSame) {
                rowspan++;
                spanTracker[j] = 1; // Mark this row as spanned
              } else {
                break;
              }
            }
            
            // Time cell
            const timeCell = document.createElement('td');
            if (rowspan > 1) {
              const startTime = row.Time.split('-')[0];
              const endTime = scheduleData[i + rowspan - 1].Time.split('-')[1];
              timeCell.textContent = `${startTime}-${endTime}`;
              timeCell.rowSpan = rowspan;
            } else {
              timeCell.textContent = row.Time;
            }
            tr.appendChild(timeCell);
            
            // Session cells
            days.forEach((day, idx) => {
              const sessionInfo = parseSession(row[day]);
              const td = document.createElement('td');
              td.setAttribute('data-type', row[typeKeys[idx]]);
              
              if (rowspan > 1) {
                td.rowSpan = rowspan;
              }
              
              if (sessionInfo.speaker) {
                td.innerHTML = `${sessionInfo.title}<br><em>(${sessionInfo.speaker})</em>`;
              } else {
                td.textContent = sessionInfo.title;
              }
              
              tr.appendChild(td);
            });
            
            tbody.appendChild(tr);
          }
        }

        // Generate mobile cards
        function generateMobileCards(scheduleData) {
          const navButtons = document.getElementById('mobile-nav-buttons');
          const container = document.getElementById('mobile-days-container');
          
          if (!navButtons || !container) return;
          
          const days = [
            { key: 'Monday March 9', typeKey: 'Type_Mon', id: 'monday', label: 'Mon<br>Mar 9' },
            { key: 'Tuesday March 10', typeKey: 'Type_Tue', id: 'tuesday', label: 'Tue<br>Mar 10' },
            { key: 'Wednesday March 11', typeKey: 'Type_Wed', id: 'wednesday', label: 'Wed<br>Mar 11' },
            { key: 'Thursday March 12', typeKey: 'Type_Thu', id: 'thursday', label: 'Thu<br>Mar 12' }
          ];
          
          // Generate navigation buttons
          navButtons.innerHTML = '';
          days.forEach((day, index) => {
            const btn = document.createElement('button');
            btn.className = 'day-btn' + (index === 0 ? ' active' : '');
            btn.innerHTML = day.label;
            btn.onclick = function() { showDay(day.id); };
            btn.setAttribute('role', 'tab');
            btn.setAttribute('aria-selected', index === 0 ? 'true' : 'false');
            btn.setAttribute('aria-controls', `day-${day.id}`);
            btn.setAttribute('tabindex', index === 0 ? '0' : '-1');
            navButtons.appendChild(btn);
          });
          
          // Generate day cards
          container.innerHTML = '';
          days.forEach((day, dayIndex) => {
            const card = document.createElement('div');
            card.className = 'day-card';
            card.id = `day-${day.id}`;
            card.setAttribute('role', 'tabpanel');
            card.setAttribute('aria-labelledby', `${day.id}-tab`);
            card.setAttribute('aria-hidden', dayIndex === 0 ? 'false' : 'true');
            if (dayIndex > 0) {
              card.style.display = 'none';
            }
            
            const schedule = document.createElement('div');
            schedule.className = 'day-schedule';
            
            // Group consecutive same sessions
            let i = 0;
            while (i < scheduleData.length) {
              const row = scheduleData[i];
              const sessionText = row[day.key];
              const sessionType = row[day.typeKey];
              
              // Look ahead for same session
              let endIdx = i;
              while (endIdx + 1 < scheduleData.length &&
                     scheduleData[endIdx + 1][day.key] === sessionText &&
                     scheduleData[endIdx + 1][day.typeKey] === sessionType) {
                endIdx++;
              }
              
              const timeSlot = document.createElement('div');
              timeSlot.className = 'time-slot';
              timeSlot.setAttribute('data-session', sessionType);
              
              const timeBadge = document.createElement('div');
              timeBadge.className = 'time-badge';
              if (i === endIdx) {
                timeBadge.textContent = row.Time;
              } else {
                const startTime = row.Time.split('-')[0];
                const endTime = scheduleData[endIdx].Time.split('-')[1];
                timeBadge.textContent = `${startTime}-${endTime}`;
              }
              
              const sessionContent = document.createElement('div');
              sessionContent.className = 'session-content';
              
              const sessionInfo = parseSession(sessionText);
              const sessionTitle = document.createElement('div');
              sessionTitle.className = 'session-title';
              sessionTitle.textContent = sessionInfo.title;
              sessionContent.appendChild(sessionTitle);
              
              if (sessionInfo.speaker) {
                const sessionSpeaker = document.createElement('div');
                sessionSpeaker.className = 'session-speaker';
                sessionSpeaker.textContent = `(${sessionInfo.speaker})`;
                sessionContent.appendChild(sessionSpeaker);
              }
              
              timeSlot.appendChild(timeBadge);
              timeSlot.appendChild(sessionContent);
              schedule.appendChild(timeSlot);
              
              i = endIdx + 1;
            }
            
            card.appendChild(schedule);
            container.appendChild(card);
          });
          
          // Setup keyboard navigation
          setupKeyboardNavigation();
        }

        // Setup keyboard navigation for mobile buttons
        function setupKeyboardNavigation() {
          const buttons = document.querySelectorAll('.day-btn');
          buttons.forEach((btn, index) => {
            btn.addEventListener('keydown', function(e) {
              let nextIndex;
              switch(e.key) {
                case 'ArrowLeft':
                  e.preventDefault();
                  nextIndex = index > 0 ? index - 1 : buttons.length - 1;
                  buttons[nextIndex].focus();
                  break;
                case 'ArrowRight':
                  e.preventDefault();
                  nextIndex = index < buttons.length - 1 ? index + 1 : 0;
                  buttons[nextIndex].focus();
                  break;
                case 'Home':
                  e.preventDefault();
                  buttons[0].focus();
                  break;
                case 'End':
                  e.preventDefault();
                  buttons[buttons.length - 1].focus();
                  break;
              }
            });
          });
        }

        // Load and process schedule
        document.addEventListener('DOMContentLoaded', async function() {
          try {
            const response = await fetch('/schedule.csv');
            if (!response.ok) {
              throw new Error('Failed to load schedule');
            }
            
            const csvText = await response.text();
            const scheduleData = parseCSV(csvText);
            
            generateTable(scheduleData);
            generateMobileCards(scheduleData);
          } catch (error) {
            console.error('Error loading schedule:', error);
            // Fallback message
            const tbody = document.getElementById('schedule-tbody');
            if (tbody) {
              tbody.innerHTML = '<tr><td colspan="5" style="text-align: center; padding: 2rem;">Schedule loading error. Please refresh the page.</td></tr>';
            }
          }
        });
        </script>

        <div class="agenda-legend" style="margin-top: 1.5rem; padding: 2rem; background: white; border-radius: 16px; box-shadow: 0 8px 32px rgba(0,0,0,0.12); border: 1px solid rgba(255,255,255,0.2);">
          <h4 style="margin-bottom: 1.5rem; color: #2c3e50; font-weight: 600; font-size: 1.1rem;">Session Types:</h4>
          <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1rem; font-size: 0.95rem;">
            <div style="padding: 1rem; background: #fef3e2; color: #9a3412; border-radius: 12px; border: 1px solid #fed7aa; font-weight: 500; transition: all 0.3s ease; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">📚 Foundational Sessions</div>
            <div style="padding: 1rem; background: #f0f0ff; color: #4c1d95; border-radius: 12px; border: 1px solid #d8d5ff; font-weight: 500; transition: all 0.3s ease; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">🚀 Specialized Sessions</div>
            <div style="padding: 1rem; background: #ecfdf5; color: #065f46; border-radius: 12px; border: 1px solid #bbf7d0; font-weight: 500; transition: all 0.3s ease; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">🔧 Hackathon Activities</div>
            <div style="padding: 1rem; background: #fdf4ff; color: #7c2d92; border-radius: 12px; border: 1px solid #f3d4f7; font-weight: 500; transition: all 0.3s ease; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">✨ Special Events</div>
          </div>
        </div>
---
