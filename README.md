# 🔖 My Favorite Sites — Personal Productivity & AI Hub

A lightweight, single-file interactive web directory and personal start page built with vanilla HTML, CSS, and JavaScript. Designed for instant access to curated AI tools, developer resources, freelancing platforms, and daily utilities—hosted live via GitHub Pages.

🔗 **Live Demo:** [https://myhifi.github.io/my-favorites/](https://myhifi.github.io/my-favorites/)

---

## ✨ Key Features

- **Curated Resource Directory:** Organized into 17+ structured categories covering AI Chatbots & Agents, Web Development, UI/UX Design, Video & Audio Production, Freelance Marketplaces, Language Learning, and Travel Hubs.
- **Instant Live Search & Category Filtering:** Filter resources dynamically by category dropdown or real-time keyword search across titles and descriptions[cite: 13].
- **Live Digital Clock:** Real-time date and 12-hour clock display with a toggle to pause or resume per-second updates[cite: 13].
- **Automated Prayer Times & Countdown:** Integrates the [AlAdhan API](https://aladhan.com/prayer-times-api) and browser geolocation (via BigDataCloud reverse geocoding) to display the next prayer time, a live countdown timer (with visual alerts within 15 minutes), and an embedded prayer timetable widget[cite: 13].
- **Zero-Dependency Architecture:** Everything runs out of a single `index.html` file with no build steps, frameworks, or external package installations required[cite: 13].

---

## 📂 Categories Included

- 🤖 **AI Chatbots & Answer Engines** (Gemini, DeepSeek, Claude, ChatGPT, Kimi, Perplexity, etc.)[cite: 13]
- 🛠️ **AI Tools & Learning Helpers**[cite: 13]
- 🎓 **Online Learning Platforms & Developer Resources**[cite: 13]
- 🎨 **Free Web Templates, UI Components & Design Tools**[cite: 13]
- 🎬 **Video Editing, Text-to-Speech & Media Production**[cite: 13]
- 💼 **Freelancing Marketplaces, Remote Work & Volunteer Platforms**[cite: 13]
- 🌍 **Language Learning & Travel Booking Hubs**[cite: 13]

---

## 🚀 How to Use or Customize

1. **Access Online:** Visit [https://myhifi.github.io/my-favorites/](https://myhifi.github.io/my-favorites/) from any desktop or mobile browser.
2. **Add or Edit Links:** Open `index.html` and update the `siteData` JavaScript object[cite: 13]:
   ```javascript
   "Category Name": [
     {
       title: "Site Title",
       link: "[https://example.com/](https://example.com/)",
       description: "Brief description of the tool or resource"
     }
   ]
