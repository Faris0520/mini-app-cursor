# Tip Calculator

A simple tip calculator in a **single HTML file** (`index.html`) — HTML, CSS, and JavaScript with no build steps or npm dependencies.

Created by Cursor Agent.

## Features

- **Bill** input
- Preset tip options: **5%**, **10%**, **15%**, **25%**, or **Custom**
- Bill splitting based on the **number of people**
- **Tip Amount / person** and **Total / person** displays (calculated in real time as you type)
- Basic validation (e.g., the number of people cannot be 0)
- **Reset** button to clear all inputs

## How to Run

Simply open the file in your browser:

```bash
# From the repository root
xdg-open index.html   # Linux
open index.html       # macOS
```

Alternatively, you can use a local server (optional):

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080/index.html](http://localhost:8080/index.html).

## Calculation Example

| Bill | Tip | People | Tip / Person | Total / Person |
|------|-----|--------|--------------|----------------|
| $100 | 15%  | 2      | $7.50        | $57.50         |

**Formula:**

- Total tip = Bill × (Tip % / 100)
- Total bill = Bill + Total tip
- Per-person amount = Total amount ÷ Number of people

## Project Structure

```text
.
├── index.html   # Complete application (UI + logic)
└── README.md
```

## License

A sample project created for the Global Hack Week submission challenge.
