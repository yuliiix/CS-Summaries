# 📚 CS Summaries

> An interactive, mobile-first study tool for Computer Science students — built with vanilla JavaScript, full Hebrew RTL support.

🔗 **[Live Site → yuliiix.github.io/CS-Summaries](https://yuliiix.github.io/CS-Summaries)**

-----

## ✨ Features

- 🗂 **Definition Cards** — structured summaries with formulas, principles, and complexity analysis
- 🔁 **Flashcards** — flip-to-reveal mode for active recall studying
- 📄 **PDF Viewer** — embedded course summaries (desktop) / direct open (mobile)
- 🔍 **Live Search** — instant filtering across all courses and cards
- 📱 **Mobile-first** — bottom navigation bar, optimized for iPhone/Android
- 🕐 **Live Clock** — date and time display in Hebrew
- 🌐 **Hebrew RTL** — full right-to-left layout with proper formula rendering

-----

## 📖 Courses

|Course                       |Cards|PDFs|
|-----------------------------|-----|----|
|📐 Linear Algebra 1           |10   |2   |
|∞ Calculus 1                 |12   |1   |
|🌳 Data Structures            |13   |1   |
|☕ Object-Oriented Programming|13   |1   |
|🔢 Discrete Mathematics       |22   |1   |

-----

## 🛠Tech Stack

|                 |                                                           |
|-----------------|-----------------------------------------------------------|
|**Frontend**     |Vanilla JavaScript (ES6+), HTML5, CSS3                     |
|**Fonts**        |Google Fonts — Assistant, JetBrains Mono, Noto Serif Hebrew|
|**Hosting**      |GitHub Pages                                               |
|**No frameworks**|Zero dependencies, zero build tools                        |

-----

## 🚀 Run Locally

```bash
git clone https://github.com/yuliiix/CS-Summaries.git
cd CS-Summaries
# Open index.html in your browser — no server needed
open index.html
```

-----

## 📁 Project Structure

```
CS-Summaries/
├── index.html          # Entire app — single file SPA
├── bdida-summary.pdf   # Discrete math summary
├── infi-1.pdf          # Calculus summary
├── linear-note1.pdf    # Linear algebra pt. 1
└── linear-note2.pdf    # Linear algebra pt. 2
```

-----

## 💡 Design Decisions

- **Single HTML file** — zero build toolchain, instant deployment, easy to maintain
- **No localStorage** — privacy-friendly; no data stored between sessions
- **CSS custom properties** — consistent pastel yellow theme throughout
- **`direction: ltr` on formula blocks** — solves RTL/math arrow rendering issues

-----

*Built by [Yuli Ittah](https://github.com/yuliiix) — Bar-Ilan University, Computer Science*
