<div align="center">

# Typing Test

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://soumendrak.github.io/typing-test/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=flat-square)](https://www.w3.org/TR/html52/)

<!-- Inline SVG logo -->
<svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
<rect width="140" height="140" rx="24" fill="#0a0a14"/>
  <rect x="16" y="30" width="108" height="36" rx="4" fill="#0d0d1a"/>
  <text x="22" y="44" font-family="monospace" font-size="7" fill="#4caf7d">The</text>
  <text x="40" y="44" font-family="monospace" font-size="7" fill="#4caf7d"> quick</text>
  <text x="66" y="44" font-family="monospace" font-size="7" fill="#e74c3c">brown</text>
  <text x="94" y="44" font-family="monospace" font-size="7" fill="#f0ece4"> fox</text>
  <text x="22" y="56" font-family="monospace" font-size="7" fill="#f0ece4">jumps</text>
  <text x="52" y="72" font-family="monospace" font-size="18" font-weight="bold" fill="#ff6b35">42</text>
  <text x="68" y="72" font-family="sans-serif" font-size="9" fill="#8a8a9a">WPM</text>
</svg>

**Test your typing speed and accuracy with real-time WPM, live highlighting.**

**Live:** [https://soumendrak.github.io/typing-test/](https://soumendrak.github.io/typing-test/)

</div>

---

## Features

- 50 built-in quotes across various topics and lengths
- Character-level highlighting: green for correct, red for mistakes
- Real-time WPM (words per minute) and accuracy tracking
- Timer counts up as you type
- Results dialog on completion: WPM, accuracy, time, mistakes
- 'New Test' randomises to a fresh quote
- Dark theme with orange accent (#ff6b35)

## How It Works

The target quote is displayed with each character inside a `<span>`. As the user types, each keystroke is compared to the corresponding target character: green if correct, red if incorrect, with a blinking cursor span tracking position. WPM = (correct chars / 5) / (elapsed minutes). Accuracy = correct keystrokes / total keystrokes.

## Usage

1. Open `https://soumendrak.github.io/typing-test/` in any browser.
2. No build step, no installation, no server required.
3. Deploy anywhere — GitHub Pages, Netlify, or any static host.

```bash
git clone https://github.com/soumendrak/typing-test.git
# Open index.html directly
```

## License

Licensed under the [MIT License](LICENSE).

---

<p align="center"><sub>Built with ❤️ and zero dependencies</sub></p>
