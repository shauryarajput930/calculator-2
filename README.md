# Calculator

A polished, responsive browser calculator built with plain HTML, CSS, and JavaScript. It has no dependencies or build step.

## Features

- Addition, subtraction, multiplication, division, and modulo operations
- Decimal input validation, result rounding, and division-by-zero handling
- `AC` to reset and `DEL` to remove the last digit
- Full keyboard support: numbers, operators, `Enter`, `Backspace`, and `Esc`
- Persistent recent-calculation history, with reusable results and a clear option
- Accessible labels, keyboard focus styles, and a responsive mobile layout

## Run locally

Open [calculator.html](calculator.html) in any modern web browser.

Alternatively, from this folder run a local static server, then visit the address it prints:

```powershell
python -m http.server 8000
```

## Project structure

```text
.
|- calculator.html  # Application markup, styles, and calculator logic
`- README.md        # Project documentation
```
