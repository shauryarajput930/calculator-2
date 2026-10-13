# Nova Calculator

A polished, responsive calculator web app built with plain HTML, CSS, and JavaScript. It runs directly in the browser with no dependencies or build setup.

## Features

- Arithmetic operations for addition, subtraction, multiplication, division, and modulo
- Decimal input handling with safe result formatting and division-by-zero protection
- `AC` to clear the current calculation and `DEL` to remove the last input
- Keyboard shortcuts for numbers, operators, `Enter`, `Backspace`, and `Esc`
- Persistent recent calculation history saved in the browser
- Reusable past results and a clear-history option
- Accessible UI with focus states and responsive layout for desktop and mobile screens

## Run locally

Open [index.html](index.html) in any modern web browser.

Alternatively, serve the project from this folder:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Project structure

```text
.
|- index.html   # Calculator interface, styling, and app logic
|- README.md    # Project documentation
```

## Notes

- The app stores recent calculations using `localStorage` in the browser.
- The interface is designed as a modern calculator with a compact history sidebar and responsive layout.