# kiType ⌨️

**Minimal Aesthetic Typing Practice Website**

kiType is a modern, lightweight typing practice web app designed to help users improve their typing speed and accuracy in a calm, distraction-free environment. It features a clean UI, real-time statistics, keyboard visualization, and a local leaderboard — all running in a single HTML file.

---

## ✨ Features

* ⚡ **Real-time typing statistics**

  * Words Per Minute (WPM)
  * Accuracy percentage
  * Time elapsed

* ⏱ **Multiple timer modes**

  * 30 seconds
  * 60 seconds
  * 120 seconds

* ⌨ **Interactive typing interface**

  * Character-by-character highlighting
  * Correct / incorrect feedback
  * Animated typing cursor

* 📊 **Progress bar**

  * Visual indicator of remaining time

* 🏆 **Local leaderboard**

  * Saves top scores using `localStorage`
  * Shows best WPM and accuracy

* 🎨 **Minimal aesthetic UI**

  * Modern typography
  * Smooth animations
  * Clean layout

* 🔁 **Restart support**

  * Restart button
  * `ESC` keyboard shortcut

* 🔤 **Dynamic sentence generator**

  * Infinite typing sentences

---

## 🖥 Demo

Open the project in a browser to start practicing typing instantly.

Example interface components:

* Header with controls
* Timer selection
* Stats panel
* Typing area
* Progress bar
* Leaderboard

---

## 📂 Project Structure

```
ZenType/
│
├── index.html     # Main application (HTML + CSS + JS)
└── README.md      # Project documentation
```

The entire application runs in **one file** for simplicity.

---

## 🚀 Getting Started

### 1. Clone or Download the Project

```bash
git clone https://github.com/yourusername/zentype.git
```

or download the ZIP file.

---

### 2. Open the App

Simply open the file:

```
index.html
```

in any modern browser.

Supported browsers:

* Chrome
* Edge
* Firefox
* Safari

No installation or dependencies required.

---

## 🎮 How to Use

1. Select a **timer mode** (30s / 60s / 120s).
2. Click the typing box.
3. Start typing the displayed sentence.
4. The timer begins on the **first keystroke**.
5. When time ends or sentence finishes:

   * Your **WPM and accuracy** are calculated.
   * Score is saved to the leaderboard.

Press **ESC** or **Restart** to try again.

---

## 🧠 How WPM is Calculated

```
WPM = (Correct Characters ÷ 5) ÷ Minutes
```

Accuracy is calculated using:

```
Accuracy = (Correct Keystrokes ÷ Total Keystrokes) × 100
```

---

## 🛠 Technologies Used

* **HTML5**
* **CSS3**
* **Vanilla JavaScript**
* **Google Fonts**

  * DM Mono
  * Outfit

No frameworks or libraries required.

---

## 💾 Data Storage

ZenType stores leaderboard scores locally using:

```
localStorage
```

This means scores are saved in the browser but **not uploaded anywhere**.

---

## 📈 Possible Improvements

Future versions could include:

* 👤 User accounts
* 🌐 Global leaderboard
* 🎮 Multiplayer typing races
* 📊 Typing analytics & heatmaps
* 🧠 AI-generated sentences
* 📱 Mobile-optimized keyboard layout
* 📦 Progressive Web App (PWA)

---

## 🤝 Contributing

Contributions are welcome!

If you would like to improve ZenType:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

---

## 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute it.

---

## 👨‍💻 Author

Created by **Abhishek Tiwari**

Built as a practice project for learning web development and UI design.

---

## ⭐ Support

If you like this project, consider giving it a **star ⭐ on GitHub**.

It helps others discover the project!
