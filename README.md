# 🕒 Digital Clock

A simple, clean digital clock built with HTML, CSS, and JavaScript. This project displays the current time in **HH:MM:SS** format and updates every second. It features a modern, blurred-glass UI with overlapping shapes for visual flair.

---

## 🚀 Features

- Real-time clock that updates every second
- Stylish glassmorphism effect using `backdrop-filter`
- Colorful overlapping circle and square for decoration
- Responsive and centered layout

---

## 🛠️ Technologies Used

- **HTML** – Structure of the digital clock
- **CSS** – Styling, layout, and backdrop blur effects
- **JavaScript** – Time calculation and live updates

---

## 📁 File Structure
digital-clock/
│
├── index.html # Main HTML file
├── style.css # Styling and layout
└── main.js # JavaScript for live time updates




---

## 📷 Preview

![Clock Preview]
![Screenshot (473)](https://github.com/user-attachments/assets/6eba18ae-8aaf-4bfe-9fa2-7a06a7ccdb94)



---

## 📌 How It Works

1. `main.js` uses `setInterval` to update the time every second.
2. The current hours, minutes, and seconds are fetched using JavaScript’s `Date` object.
3. Values are padded with a leading zero if they're less than 10 (e.g., 08 instead of 8).
4. The `.clock` element uses `backdrop-filter: blur(40px)` to blur background shapes partially visible behind it.

---

## ✅ How to Run

1. Clone this repository:
   ```bash
   https://github.com/Edgahkipkemoi/Digital-Clock.git
2.Open index.html in your browser.

📦 Future Improvements
Add AM/PM support or 24-hour toggle

Add date display

Improve responsiveness on smaller devices
