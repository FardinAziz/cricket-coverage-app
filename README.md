# 📊 Criclytics — Live Cricket Scores & ICC Rankings

**Criclytics** is a modern web app that brings together **live cricket scores**, **upcoming fixtures**, **ICC team & player rankings**, and **latest cricket news** — all in a clean, responsive, and engaging interface.

---

## 🚀 Features

✅ **Live Matches**  
- Displays real-time match scores with team flags, scores, and match status (Live, Upcoming, Completed).  
- Uses mocked data with clear layout ready for integration with a live cricket API.

✅ **Upcoming Fixtures**  
- Shows upcoming matches with dates, venues, and competing teams.

✅ **ICC Rankings**  
- Dynamic ICC rankings for Teams, Batting, Bowling, and All-Rounders.  
- Supports Men’s and Women’s cricket across Test, ODI, and T20I formats.  
- Rankings are displayed from a structured JSON data source.

✅ **Latest News**  
- Static news cards section for cricket headlines and match reports.

✅ **Responsive Design**  
- Fully responsive layout that adapts to desktop, tablet, and mobile screens.  
- Smooth animations and clean UI using modern CSS.

---

## 📁 Project Structure

\`\`\`
├── index.html         # Main HTML file
├── style.css          # CSS styles for layout and responsiveness
├── icc_rankings.json  # Structured ICC rankings data
├── mock-live.json     # Mock live matches data
├── mock-upcoming.json # Mock upcoming fixtures data
├── flags/             # Country flag images (expected in the flags folder)
\`\`\`

---

## ⚙️ How It Works

- **HTML & CSS:** Structured semantic HTML with organized sections for hero, matches, fixtures, rankings, and news.
- **JavaScript:** Fetches and renders live matches, upcoming fixtures, and rankings using JSON data (mocked for development).  
- **API Ready:** The app includes configuration for integrating with the [CricAPI](https://cricapi.com/) for live data — simply replace mock data with real API calls.

---

## 🖌️ Styling

- Uses CSS custom properties for easy theming.
- Includes animations for card fade-in.
- Navigation bar with smooth scroll and active link highlighting.
- Fully responsive with CSS grid and flexbox layouts.

---

## 📦 Requirements

- Just open `index.html` in any modern web browser.
- Make sure your flag images are placed inside a `flags/` directory with proper country codes (e.g., `ind.png`, `aus.png`).

---

## 🔑 API Integration

The project is set up with placeholder configurations for the CricAPI. To go live:
1. Get your API key from [cricapi.com](https://cricapi.com/).
2. Replace `useMockData = true` with `false` in your script.
3. Ensure CORS and deployment environment are properly configured.

---

## ✨ Future Enhancements

- Live match integration with backend.
- Admin panel for news updates.
- Player profiles and stats.
- Dark mode toggle.

---

## 📄 License

This project is for educational/demo purposes.
