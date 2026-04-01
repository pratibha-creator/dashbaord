# Dashboard

A lightweight, browser-based dashboard that visualises data from a CSV file.

---

## Project Structure

```
dashbaord/
├── css/
│   └── style.css       # All styles / design
├── script/
│   └── main.js         # Functional & logical code
├── index.html          # Main entry point
└── README.md           # This file
```

---

## Run on Localhost

This project is plain HTML/CSS/JS — no build step required.

### Option 1 — VS Code Live Server (recommended)

1. Open the `dashbaord` folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` → **Open with Live Server**.
4. Browser opens at `http://127.0.0.1:5500`.

### Option 2 — Python HTTP Server

```bash
# Python 3
cd dashbaord
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

### Option 3 — Node.js `serve`

```bash
npm install -g serve
cd dashbaord
serve .
```

Then open the URL shown in the terminal (usually `http://localhost:3000`).

---

## Next Steps

- Share the CSV file so charts and tables can be wired up to real data.
