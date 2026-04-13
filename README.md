# Serenity
A lightweight tiling window manager for Windows, built in Python.

## Prerequisites

- **Python 3.14** — [python.org/downloads](https://www.python.org/downloads/)
  - During install, check ✅ "Add Python to PATH"
- **pywin32** — Windows API bindings for Python
- **VS Code** (recommended) with the **Pylance** extension

## Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd Serenity
   ```

2. Install dependencies:
   ```bash
   python -m pip install pywin32
   ```

3. Run the project:
   ```bash
   python src/main.py
   ```

## Project Structure

```
Serenity/
├── src/
│   └── main.py       # Entry point
└── README.md
```

## Core Concepts

Serenity uses the following Win32 APIs via `pywin32`:

| API | Purpose |
|-----|---------|
| `win32gui.EnumWindows` | List all open windows |
| `win32gui.SetWindowPos` | Move and resize windows |
| `win32gui.FindWindow` | Find a window by title |
| `win32api.GetSystemMetrics` | Get screen dimensions |
## Useful Resources

- [Win32 API Reference](https://learn.microsoft.com/en-us/windows/win32/apiindex/windows-api-list)
- [pywin32 docs](https://mhammond.github.io/pywin32/)
- [komorebi](https://github.com/LGUG2Z/komorebi) — open source tiling WM for Windows (Rust)
- [glazewm](https://github.com/glzr-io/glazewm) — open source tiling WM for Windows (C#)
