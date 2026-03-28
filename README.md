# 🍅 Pomodoro Planner

A lightweight, single-file web application designed to help you plan your productivity sessions. Unlike a standard timer, this tool calculates exactly how many Pomodoro cycles you can fit into a specific window of time.

## ✨ Features

- **Time Range Calculation:** Enter your start and end times to see how many sessions fit.
- **Smart Scheduling:** Automatically accounts for work blocks, short breaks, and long breaks.
- **Overnight Support:** Correctlly handles time ranges that cross midnight (e.g., 11:00 PM to 2:00 AM).
- **Detailed Breakdown:** Shows total duration, total work time, total break time, and any remaining "free time" at the end of your window.
- **Advanced Customization:** Adjust work duration, break lengths, and the frequency of long breaks.
- **No Installation Required:** A standalone HTML file that runs in any modern web browser.

## 🚀 How to Use

1. **Open `pomodoro.html`** in your preferred web browser.
2. **Set your Start and End times.** The tool defaults to the current time and a 2-hour window.
3. **Click "Calculate"** to see your results.
4. (Optional) Click **"Advanced Settings"** to customize:
   - **Work Duration:** Default is 25 minutes.
   - **Short Break:** Default is 5 minutes.
   - **Long Break:** Default is 15 minutes.
   - **Long Break Interval:** How many Pomodoros to complete before a long break (Default is 4).

## 🛠️ Technical Details

- **Language:** HTML5, CSS3, and Vanilla JavaScript.
- **Styling:** Responsive CSS with a modern, clean interface using CSS variables for easy theme adjustments.
- **Logic:** Uses a simulation loop to accurately predict the sequence of work and breaks within the allotted time.

## 📝 License

This project is open-source and free to use.

---

Created by [Sarah86](https://github.com/Sarah86)
