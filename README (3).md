# 🚌 CampusBus Pro

> A smart campus mobility platform — real-time bus tracking, attendance management, and alert system for students, drivers, and faculty.

![HTML](https://img.shields.io/badge/HTML-Single%20File-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

---

## 📱 Live Demo

🔗 **[View Live →](https://YOUR_USERNAME.github.io/campusbus-pro/)**

> Replace the link above with your actual GitHub Pages URL after deployment.

---

## ✨ Features

### 🎓 Student View
- Live bus tracking with AI-powered ETA prediction
- Real-time route progress visualization
- Crowd reporting — mark buses as Empty / Medium / Full
- Personalized stop selection
- Leave-Now popup alerts

### 🚗 Driver View
- Trip start/end controls
- QR code boarding scanner (with attendance auto-sync)
- Crowd status updates
- Delay and emergency reporting
- Stop-by-stop route progress with arrival marking

### 👨‍🏫 Faculty View
- Full fleet overview dashboard
- On-time rate and delay statistics
- Access to full attendance reports
- Broadcast alerts to students

### 📋 Attendance System
- Full student roster per bus (B01–B04)
- Real-time boarding status: Boarded / Waiting / Absent
- Search by name or roll number
- Filter by stop or status
- Stop-wise boarding chart
- Tap to cycle student status with auto-timestamp
- Mark All Boarded with confirmation
- Export attendance records

### 🚨 Alert Center
- Live alert dashboard with severity stats
- Alert types: Critical, Warning, Info, Success
- Snooze, Dismiss, and Action buttons per alert
- Broadcast tool for drivers and faculty
- Emergency alert with confirmation modal
- Auto-alerts on delay reports, arrivals, and trip events
- Color-coded toast notifications

---

## 🚀 Getting Started

This is a **zero-dependency, single-file** web app. No npm, no build step, no server required.

### Run Locally

Just open the file in any browser:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/campusbus-pro.git

# Open in browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### Deploy on GitHub Pages

1. Push `index.html` to your repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your app will be live at `https://YOUR_USERNAME.github.io/campusbus-pro/`

---

## 🗂️ Project Structure

```
campusbus-pro/
├── index.html       # Entire app — HTML + CSS + JS in one file
├── README.md        # Project documentation
└── LICENSE          # MIT License
```

---

## 🛣️ Roadmap

- [ ] Backend integration (Node.js / Firebase)
- [ ] Real GPS tracking via browser Geolocation API
- [ ] Push notifications (Web Push API)
- [ ] Parent portal view
- [ ] Monthly attendance reports with CSV export
- [ ] PWA support (installable on phone)
- [ ] Multi-campus support

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Outfit + JetBrains Mono |
| Map | HTML5 Canvas API |
| Hosting | GitHub Pages |

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch — `git checkout -b feature/your-feature`
3. Commit your changes — `git commit -m "Add your feature"`
4. Push to the branch — `git push origin feature/your-feature`
5. Open a Pull Request

Please make sure your code follows the existing style and is well-commented.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Your Name**
- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)

---

> Made with ❤️ for smarter campus mobility.
