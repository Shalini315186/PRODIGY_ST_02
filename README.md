# PRODIGY_ST_02
Task-02: Compatibility Testing Report - Prodigy Infotech Software Testing Internship
Task-02: Compatibility Testing Report
Project: E-com Website – Demo Website
Organization: ProDigy Infotech
Objective
Conduct compatibility testing for a basic web page across multiple browsers and devices.
Focus:
- Gradient backgrounds
- Circle shapes with gradients
- Typography (e.g., Comillas Negras)
- Basic layout and navigation
Test Environments
•	Browsers:
•	Google Chrome (v115+)
•	Mozilla Firefox (v115+)
•	Microsoft Edge (v115+)
•	Safari (macOS/iOS)
•	Devices:
•	Windows 10 Desktop (Chrome, Firefox, Edge)
•	macOS (Safari)
•	Android (Chrome Mobile)
•	iPhone (Safari)
•	iPad / Samsung Galaxy Tab (Tablet view)
Key UI Elements Tested
- Circle with Gradient
- Blue Gradient Background
- Text: 'Conduct Compatibility Testing', 'Comillas Negras', 'ProDigy Infotech'
- Basic navigation and links
Issues Found
#	Issue	Affected Browsers/Devices	Type	Suggested Fix
1	Gradient background not showing properly	Safari (iOS), Firefox (Mobile)	UI	Add solid color fallback in CSS (background: #000 before gradient)
2	Circle overlaps text on small screens	Android Phones, iPhone	Responsive Design	Use @media queries to reposition or scale circles
3	Font 'Comillas Negras' not displaying	Firefox	Font Loading	Ensure font is web-safe or hosted properly with correct MIME type
4	Layout breaks on screen resize	Edge Desktop	CSS Layout	Switch to Flexbox or Grid for smoother layout adjustments
5	Broken link (e.g., #)	All Browsers	Functionality	Replace # with actual URL or remove until live
Passed Scenarios
- Page loads correctly on Chrome (all devices)
- Gradient circles render fine on desktop browsers
- Main text is visible and aligned in large screen sizes
- No console errors or 404s except dummy links
Recommendations
- Improve mobile responsiveness with proper scaling
- Add font fallbacks in CSS: font-family: 'Comillas Negras', Arial, sans-serif;
- Replace all placeholder links (#) with working URLs
- Optimize layout using flex or grid to prevent overlap
- Use tools like BrowserStack or Responsively App for further testing
Date Tested
July 6, 2025
Tester
Shalini – Intern at ProDigy Infotech
