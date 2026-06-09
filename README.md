# Velocikey

A desktop typing speed test application built with Python. Select a difficulty, type the given sentence as fast and accurately as you can, and get your WPM and accuracy score instantly.

Built as a 1st year, 1st semester project by **Team PYTHRONAUTS**.

---

## Features

- **Three difficulty levels** — Easy, Medium, and Hard sentence sets
- **WPM calculation** — measures your words per minute based on elapsed time
- **Accuracy scoring** — compares your input word-by-word against the original sentence
- **Clean GUI** — built with customtkinter for a modern desktop look
- **Retry support** — reset and test again without restarting the app

---

## Tech Stack

| | |
|---|---|
| Language | Python 3 |
| GUI | customtkinter |
| Image handling | Pillow (PIL) |

---

## Getting Started

### Prerequisites

```bash
pip install customtkinter pillow
```

### Run

```bash
python VELOCIKEY.py
```

> **Note:** The logo image path in `VELOCIKEY.py` is currently hardcoded to a local directory. Update the `Image.open()` path to match your local setup, or place `VELOCIKEY_LOGO2.jpg` in the same directory as the script and change the path to `"VELOCIKEY_LOGO2.jpg"`.

---

## How to Use

1. Run the app
2. Type `easy`, `medium`, or `hard` in the input field
3. Click **START TEST**
4. Type the displayed sentence as fast as you can and press **Enter**
5. Your WPM and accuracy will be shown
6. Click **Retry** to go again

---

## Project Structure

```
Velocikey/
├── VELOCIKEY.py        # Main application (final version)
├── VELOCIKEY_LOGO2.jpg # App logo/banner
├── beta.py             # Beta build
├── raw_code.py         # Early draft
└── window.py           # Window prototype
```

---

## Contributors

- **Ace Philip Denulan** ([@naxareth](https://github.com/naxareth)) - Project Manager
- **Will Anthony Barillo**
- **Myke Jovellanos**
- **Renz Dexther Soriano**

---

## Notes

This was our first Python GUI project — built in 1st year, 1st semester at PHINMA University of Pangasinan. The code still has inline Filipino comments from when we were learning. We kept them.

---

## License

For academic use. PHINMA University of Pangasinan — 1st Year, 1st Semester.
