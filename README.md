# 🕒 Analog Clock

A modern and responsive **Analog Clock** built using **HTML, CSS, and JavaScript**. The clock displays the current system time by rotating the hour, minute, and second hands in real time, providing a smooth and visually appealing user experience.

## 🚀 Live Demo

🔗 https://deepak-thakur2004.github.io/Analog-clock/

## ✨ Features

- 🕒 Real-time analog clock
- ⏱️ Automatic hour, minute, and second hand movement
- 🎨 Clean and modern UI
- 📱 Responsive design
- ⚡ Lightweight and fast performance
- 🔄 Updates every second using JavaScript

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## 📂 Project Structure

```text
Analog-clock/
│── index.html
│── style.css
│── script.js
└── README.md
```

## 🎯 How It Works

1. The application retrieves the current system time using JavaScript's `Date` object.
2. The hour, minute, and second values are extracted.
3. Each clock hand is rotated based on the calculated angle:
   - Hour Hand → `30° × hours + 0.5° × minutes`
   - Minute Hand → `6° × minutes`
   - Second Hand → `6° × seconds`
4. The clock updates every second using `setInterval()`.

## 🧠 Concepts Practiced

This project helped me strengthen my understanding of:

- DOM Manipulation
- JavaScript Date Object
- CSS Transforms (`rotate`)
- CSS Variables
- Flexbox
- Responsive Web Design
- JavaScript Functions
- `setInterval()`
- Real-Time UI Updates

## 🔮 Future Improvements

- 🌙 Dark/Light Mode
- 📅 Display Current Date
- 🌍 Multiple Time Zones
- ⏰ Digital Clock Integration
- 🎨 Custom Clock Themes
- ✨ Smooth Hand Animation

## 👨‍💻 Author

**Deepak**

GitHub: https://github.com/Deepak-thakur2004

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
