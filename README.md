
# Statistics Dashboard Website

This website template dynamically loads multiple sheets from Google Sheets and displays:

- Searchable tables for each sheet
- Responsive charts using Chart.js

## Instructions

1. Publish each sheet in your Google Sheets as CSV:
   - File → Publish to web → Select sheet → CSV → Copy link
2. Replace placeholders in `index.html` with your CSV links:
   ```javascript
   const sheets = [
     { name: 'Sheet1', csv: 'YOUR_CSV_LINK' },
     { name: 'Sheet2', csv: 'YOUR_CSV_LINK' }
   ];
   ```
3. Host the folder on GitHub Pages, Vercel, or Netlify.
