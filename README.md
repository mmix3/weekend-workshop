# weekend-workshop
Weekend Project Planner
# 🔧 Weekend Workshop

A weather-aware weekend project planner. Add your home projects, get suggestions based on the forecast, and track your progress.

## Features
- Add projects with category (indoor/outdoor), priority, time estimates, and materials lists
- Real weather integration via OpenWeatherMap (with manual fallback)
- Configurable weather thresholds for outdoor/indoor decisions
- YouTube how-to video links for every project
- Progress notes and photo tracking
- Google Calendar integration for weekly reminders
- Works on desktop and mobile (Android PWA installable)

---

## 🌤️ Weather API Setup
Your API key is **not stored in the source code**. The first time you open the app's Weekend Plan tab in Live mode, it will prompt you to paste your OpenWeatherMap API key. The key is saved in your browser's localStorage on each device — you only need to enter it once per device.

To get a free key:
1. Sign up at [openweathermap.org](https://openweathermap.org/api)
2. Go to your API keys page
3. Copy your key and paste it into the app

The free tier gives you 1,000 API calls per day, which is plenty for personal use.

---

## 📱 Tips
- **Data is stored in your browser's localStorage** — it stays on each device separately
- If you want to sync between devices, you'd need a backend (a future enhancement)
- The app works offline once loaded (service worker caches it)
- Photos are stored as base64 in localStorage — very large photos may use up storage, so keep photo usage reasonable

Enjoy your weekends! 🔧
