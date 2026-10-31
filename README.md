# Fullscreen Timer ⏱️

A modern, distraction-free fullscreen countdown timer web app with ambient visual feedback, keyboard shortcuts, synthesized audio cues, and quick presets.

---

## ✨ Features

- **📺 Fullscreen Presentation Mode**: Perfect for presentations, exams, workouts, Pomodoro sessions, or public speaking.
- **⚡ Quick Presets**: Instant setup for popular time intervals: 1m, 3m, 5m, 10m, 15m, 25m (Pomodoro), 30m, 45m, and 60m.
- **⚙️ Custom Time Input**: Easily configure any duration (hours, minutes, seconds) through an intuitive modal.
- **🌈 Dynamic Visual States**:
  - **Idle**: Calm dark neon aesthetic with ambient glow.
  - **Active / Running**: Subtle green breathing ambient aura.
  - **Finished**: Pulsing red alert notification with completion banner.
- **🔊 Built-in Web Audio API**: Crisp countdown beeps and completion chime generated natively in the browser without external audio assets.
- **⌨️ Keyboard Shortcuts**: Fully operable via keyboard for quick and seamless control.
- **📱 Responsive & Lightweight**: Pure HTML, CSS, and vanilla JavaScript with zero external frameworks or dependencies.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>Space</kbd> | Start / Pause timer |
| <kbd>R</kbd> | Reset timer |
| <kbd>F</kbd> | Toggle Fullscreen mode |
| <kbd>E</kbd> | Open Custom Time editor |
| <kbd>Enter</kbd> | Save time (while modal is open) |
| <kbd>Esc</kbd> | Close modal |

---

## 🚀 Getting Started

No build process or installation required! Simply open the app in any modern web browser.

### Option 1: Open Directly
Double-click [`index.html`](file:///home/adnan/Untitled%20Folder%2012/index.html) or open it with your browser:
```bash
xdg-open index.html
```

### Option 2: Run a Local Static Server
You can also serve it using Python or any static file server:

```bash
# Using Python 3
python3 -m http.server 8080
```
Then visit `http://localhost:8080` in your web browser.

---

## 🛠️ Built With

- **HTML5** & **CSS3** (Custom properties, Flexbox, Animations)
- **Vanilla JavaScript** (ES6+)
- **Web Audio API** (Oscillator & Gain nodes for audio alerts)
- **Google Fonts** ([JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono), [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans))
