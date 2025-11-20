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
          <table class="agenda-table">
            <thead>
              <tr>
                <th>Time</th>
                <th>Monday<br>March 9</th>
                <th>Tuesday<br>March 10</th>
                <th>Wednesday<br>March 11</th>
                <th>Thursday<br>March 12</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>9:00-9:30</td>
                <td data-type="welcome">Welcome remarks</td>
                <td data-type="welcome">Welcome remarks</td>
                <td data-type="welcome">Welcome remarks</td>
                <td data-type="welcome">Welcome remarks</td>
              </tr>
              <tr>
                <td rowspan="2">9:30-10:30</td>
                <td data-type="foundational" rowspan="2">ML basics</td>
                <td data-type="foundational" rowspan="2">RL</td>
                <td data-type="foundational" rowspan="2">NLP<br><em>(Thamar Solorio)</em></td>
                <td data-type="hackathon" rowspan="2">Hackathon presentations</td>
              </tr>
              <tr>
                <!-- Cells spanned by rowspan above -->
              </tr>
              <tr>
                <td>10:30-11:00</td>
                <td data-type="break">Break / Posters</td>
                <td data-type="break">Break / Posters</td>
                <td data-type="break">Break / Posters</td>
                <td data-type="break">Break / Posters</td>
              </tr>
              <tr>
                <td rowspan="2">11:00-12:00</td>
                <td data-type="foundational" rowspan="2">Applied ML</td>
                <td data-type="foundational" rowspan="2">Optimization<br><em>(Jose Cordova-Garcia)</em></td>
                <td data-type="foundational" rowspan="2">LLMs</td>
                <td data-type="specialized" rowspan="2">AI for Climate<br><em>(Peter Battaglia)</em></td>
              </tr>
              <tr>
                <!-- Cells spanned by rowspan above -->
              </tr>
              <tr>
                <td rowspan="3">12:00-13:30</td>
                <td data-type="break" rowspan="3">Lunch</td>
                <td data-type="break" rowspan="3">Lunch</td>
                <td data-type="break" rowspan="3">Lunch</td>
                <td data-type="break" rowspan="3">Lunch</td>
              </tr>
              <tr>
                <!-- Cells spanned by rowspan above -->
              </tr>
              <tr>
                <!-- Cells spanned by rowspan above -->
              </tr>
              <tr>
                <td rowspan="2">13:30-14:30</td>
                <td data-type="specialized" rowspan="2">Vibe coding</td>
                <td data-type="foundational" rowspan="2">Computer Vision</td>
                <td data-type="specialized" rowspan="2">Post-training / RLHF (Nathan Lambert)</td>
                <td data-type="specialized" rowspan="2">AI & Climate<br><em>(Sasha Luccioni)</em></td>
              </tr>
              <tr>
                <!-- Cells spanned by rowspan above -->
              </tr>
              <tr>
                <td>14:30-15:00</td>
                <td data-type="break">Break / Posters</td>
                <td data-type="break">Break / Posters</td>
                <td data-type="break">Break / Posters</td>
                <td data-type="break">Break / Posters</td>
              </tr>
              <tr>
                <td rowspan="2">15:00-16:00</td>
                <td data-type="hackathon" rowspan="2">Colabs/Hackathon intro</td>
                <td data-type="specialized" rowspan="2">TBA</td>
                <td data-type="special" rowspan="2">LatamGPT<br><em>(Luciana Benotti)</em></td>
                <td data-type="keynote" rowspan="2">Samy Bengio Keynote</td>
              </tr>
              <tr>
                <!-- Cells spanned by rowspan above -->
              </tr>
              <tr>
                <td rowspan="2">16:00-17:00</td>
                <td data-type="hackathon" rowspan="4">Colabs/Hackathon</td>
                <td data-type="hackathon" rowspan="2">Colabs/Hackathon</td>
                <td data-type="hackathon" rowspan="2">Colabs/Hackathon</td>
                <td data-type="hackathon" rowspan="2">Hackathon awards</td>
              </tr>
              <tr>
                <!-- Cells spanned by rowspan above -->
              </tr>
              <tr>
                <td rowspan="2">17:00-18:00</td>
                <!-- Colabs/Hackathon continues with rowspan="4" from above -->
                <td data-type="special" rowspan="2">Parallel panels</td>
                <td data-type="special" rowspan="2">Parallel panels</td>
                <td data-type="special" rowspan="2">End of event reception</td>
              </tr>
              <tr>
                <!-- Cells spanned by rowspan above -->
              </tr>
            </tbody>
          </table>
        </div>

        <!-- Mobile Card Layout - Simple approach for Hugo compatibility -->
        <div class="mobile-schedule">
          <!-- Screen reader announcements -->
          <div id="schedule-announcement" class="sr-only" aria-live="polite" aria-atomic="true"></div>
          
          <!-- Day Navigation Buttons -->
          <div class="mobile-nav-buttons" role="tablist" aria-label="Conference days navigation">
            <button class="day-btn active" onclick="showDay('monday')" role="tab" aria-selected="true" aria-controls="day-monday" tabindex="0">Mon<br>Mar 9</button>
            <button class="day-btn" onclick="showDay('tuesday')" role="tab" aria-selected="false" aria-controls="day-tuesday" tabindex="-1">Tue<br>Mar 10</button>
            <button class="day-btn" onclick="showDay('wednesday')" role="tab" aria-selected="false" aria-controls="day-wednesday" tabindex="-1">Wed<br>Mar 11</button>
            <button class="day-btn" onclick="showDay('thursday')" role="tab" aria-selected="false" aria-controls="day-thursday" tabindex="-1">Thu<br>Mar 12</button>
          </div>
          
          <!-- Monday -->
          <div class="day-card" id="day-monday" role="tabpanel" aria-labelledby="monday-tab" aria-hidden="false">
            <div class="day-schedule">
              <div class="time-slot" data-session="welcome">
                <div class="time-badge">9:00-9:30</div>
                <div class="session-content">
                  <div class="session-title">Welcome remarks</div>
                </div>
              </div>
              <div class="time-slot" data-session="foundational">
                <div class="time-badge">9:30-10:30</div>
                <div class="session-content">
                  <div class="session-title">ML basics</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">10:30-11:00</div>
                <div class="session-content">
                  <div class="session-title">Break / Posters</div>
                </div>
              </div>
              <div class="time-slot" data-session="foundational">
                <div class="time-badge">11:00-12:00</div>
                <div class="session-content">
                  <div class="session-title">Applied ML</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">12:00-13:30</div>
                <div class="session-content">
                  <div class="session-title">Lunch</div>
                </div>
              </div>
              <div class="time-slot" data-session="specialized">
                <div class="time-badge">13:30-14:30</div>
                <div class="session-content">
                  <div class="session-title">Vibe coding</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">14:30-15:00</div>
                <div class="session-content">
                  <div class="session-title">Break / Posters</div>
                </div>
              </div>
              <div class="time-slot" data-session="hackathon">
                <div class="time-badge">15:00-16:00</div>
                <div class="session-content">
                  <div class="session-title">Colabs/Hackathon intro</div>
                </div>
              </div>
              <div class="time-slot" data-session="hackathon">
                <div class="time-badge">16:00-18:00</div>
                <div class="session-content">
                  <div class="session-title">Colabs/Hackathon</div>
                </div>
              </div>
            </div>
          </div>

          <!-- Tuesday -->
          <div class="day-card" id="day-tuesday" role="tabpanel" aria-labelledby="tuesday-tab" aria-hidden="true" style="display: none;">
            <div class="day-schedule">
              <div class="time-slot" data-session="welcome">
                <div class="time-badge">9:00-9:30</div>
                <div class="session-content">
                  <div class="session-title">Welcome remarks</div>
                </div>
              </div>
              <div class="time-slot" data-session="foundational">
                <div class="time-badge">9:30-10:30</div>
                <div class="session-content">
                  <div class="session-title">RL</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">10:30-11:00</div>
                <div class="session-content">
                  <div class="session-title">Break / Posters</div>
                </div>
              </div>
              <div class="time-slot" data-session="foundational">
                <div class="time-badge">11:00-12:00</div>
                <div class="session-content">
                  <div class="session-title">TBA</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">12:00-13:30</div>
                <div class="session-content">
                  <div class="session-title">Lunch</div>
                </div>
              </div>
              <div class="time-slot" data-session="foundational">
                <div class="time-badge">13:30-14:30</div>
                <div class="session-content">
                  <div class="session-title">Computer Vision</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">14:30-15:00</div>
                <div class="session-content">
                  <div class="session-title">Break / Posters</div>
                </div>
              </div>
              <div class="time-slot" data-session="specialized">
                <div class="time-badge">15:00-16:00</div>
                <div class="session-content">
                  <div class="session-title">TBA</div>
                </div>
              </div>
              <div class="time-slot" data-session="hackathon">
                <div class="time-badge">16:00-17:00</div>
                <div class="session-content">
                  <div class="session-title">Colabs/Hackathon</div>
                </div>
              </div>
              <div class="time-slot" data-session="special">
                <div class="time-badge">17:00-18:00</div>
                <div class="session-content">
                  <div class="session-title">Parallel panels</div>
                </div>
              </div>
            </div>
          </div>

          <!-- Wednesday -->
          <div class="day-card" id="day-wednesday" style="display: none;">
            <div class="day-schedule">
              <div class="time-slot" data-session="welcome">
                <div class="time-badge">9:00-9:30</div>
                <div class="session-content">
                  <div class="session-title">Welcome remarks</div>
                </div>
              </div>
              <div class="time-slot" data-session="foundational">
                <div class="time-badge">9:30-10:30</div>
                <div class="session-content">
                  <div class="session-title">NLP</div>
                  <div class="session-speaker">(Thamar Solorio)</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">10:30-11:00</div>
                <div class="session-content">
                  <div class="session-title">Break / Posters</div>
                </div>
              </div>
              <div class="time-slot" data-session="foundational">
                <div class="time-badge">11:00-12:00</div>
                <div class="session-content">
                  <div class="session-title">LLMs</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">12:00-13:30</div>
                <div class="session-content">
                  <div class="session-title">Lunch</div>
                </div>
              </div>
              <div class="time-slot" data-session="specialized">
                <div class="time-badge">13:30-14:30</div>
                <div class="session-content">
                  <div class="session-title">Post-training / RLHF</div>
                  <div class="session-speaker">(Nathan Lambert)</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">14:30-15:00</div>
                <div class="session-content">
                  <div class="session-title">Break / Posters</div>
                </div>
              </div>
              <div class="time-slot" data-session="special">
                <div class="time-badge">15:00-16:00</div>
                <div class="session-content">
                  <div class="session-title">LatamGPT</div>
                  <div class="session-speaker">(Luciana Benotti)</div>
                </div>
              </div>
              <div class="time-slot" data-session="hackathon">
                <div class="time-badge">16:00-18:00</div>
                <div class="session-content">
                  <div class="session-title">Colabs/Hackathon</div>
                </div>
              </div>
            </div>
          </div>

          <!-- Thursday -->
          <div class="day-card" id="day-thursday" style="display: none;">
            <div class="day-schedule">
              <div class="time-slot" data-session="welcome">
                <div class="time-badge">9:00-9:30</div>
                <div class="session-content">
                  <div class="session-title">Welcome remarks</div>
                </div>
              </div>
              <div class="time-slot" data-session="hackathon">
                <div class="time-badge">9:30-10:30</div>
                <div class="session-content">
                  <div class="session-title">Hackathon presentations</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">10:30-11:00</div>
                <div class="session-content">
                  <div class="session-title">Break / Posters</div>
                </div>
              </div>
              <div class="time-slot" data-session="specialized">
                <div class="time-badge">11:00-12:00</div>
                <div class="session-content">
                  <div class="session-title">AI for Climate</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">12:00-13:30</div>
                <div class="session-content">
                  <div class="session-title">Lunch</div>
                </div>
              </div>
              <div class="time-slot" data-session="specialized">
                <div class="time-badge">13:30-14:30</div>
                <div class="session-content">
                  <div class="session-title">AI & Climate</div>
                  <div class="session-speaker">(Sasha Luccioni)</div>
                </div>
              </div>
              <div class="time-slot" data-session="break">
                <div class="time-badge">14:30-15:00</div>
                <div class="session-content">
                  <div class="session-title">Break / Posters</div>
                </div>
              </div>
              <div class="time-slot" data-session="keynote">
                <div class="time-badge">15:00-16:00</div>
                <div class="session-content">
                  <div class="session-title">Samy Bengio Keynote</div>
                </div>
              </div>
              <div class="time-slot" data-session="hackathon">
                <div class="time-badge">16:00-17:00</div>
                <div class="session-content">
                  <div class="session-title">Hackathon awards</div>
                </div>
              </div>
              <div class="time-slot" data-session="special">
                <div class="time-badge">17:00-18:00</div>
                <div class="session-content">
                  <div class="session-title">End of event reception</div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <script>
        function showDay(day) {
          // Hide all day cards with smooth transition
          document.querySelectorAll('.day-card[id^="day-"]').forEach(card => {
            card.style.display = 'none';
            card.setAttribute('aria-hidden', 'true');
          });
          
          // Remove active class and aria-selected from all buttons
          document.querySelectorAll('.day-btn').forEach(btn => {
            btn.classList.remove('active');
            btn.setAttribute('aria-selected', 'false');
          });
          
          // Show selected day
          const selectedCard = document.getElementById('day-' + day);
          selectedCard.style.display = 'block';
          selectedCard.setAttribute('aria-hidden', 'false');
          
          // Add active class and aria-selected to clicked button
          event.target.classList.add('active');
          event.target.setAttribute('aria-selected', 'true');
          
          // Announce change for screen readers
          const announcement = `Showing schedule for ${event.target.textContent.replace('\n', ' ')}`;
          const ariaLive = document.getElementById('schedule-announcement');
          if (ariaLive) {
            ariaLive.textContent = announcement;
          }
        }
        
        // Keyboard navigation support
        document.addEventListener('DOMContentLoaded', function() {
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
