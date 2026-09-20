# Sheetworks 📊

> **Note:** This project is currently **under active development**. While it is functional, new features and improvements are being added continuously. Feel free to explore, share, and test it out!

**Sheetworks** is a lightweight, fully functional web-based spreadsheet application built from scratch using pure web standards (HTML5, CSS3, and Vanilla JavaScript). It runs completely in the browser with zero external dependencies or heavy frameworks.

---

## 🚀 Key Features

* **Built-in Formula Engine:**
  * Evaluates mathematical formulas starting with `=`.
  * Supports standard operators (`+`, `-`, `*`, `/`, `^`, `%`).
  * Comprehensive function library:
    * **Math & Statistics:** `SUM`, `AVERAGE`, `MIN`, `MAX`, `COUNT`, `COUNTA`, `MEDIAN`, `ROUND`, `ABS`, `SQRT`, `POWER`, `MOD`, `PI`.
    * **Logic & Conditionals:** `IF`, `AND`, `OR`, `NOT`, `IFERROR`.
    * **Text Operations:** `CONCATENATE`, `LEN`, `UPPER`, `LOWER`, `TRIM`.
    * **Date & Time:** `TODAY`, `NOW`.

* **Cell Formatting & Styling:**
  * Customize font family, size, and text color.
  * Adjust cell background colors and toggle borders.
  * Typography options: Bold, Italic, and Underline.
  * Text alignment (Left, Center, Right).
  * Data formatting options (Currency `$`, Percent `%`, Integer, Date, Decimals).
  * Cell merging capability.

* **Data & Grid Management:**
  * Multi-cell, row, and column selection.
  * **Fill Handle:** Drag to auto-fill numbers and copy formulas across adjacent cells.
  * Interactive column and row resizing.
  * Insert and delete rows and columns.
  * Column sorting (A→Z and Z→A).
  * Live status summary bar displaying `SUM`, `AVG`, and `COUNT` for any active range.

* **Import & Export:**
  * Import external **CSV** files into a sheet.
  * Export the current sheet to a **CSV** file.

* **User Experience (UX):**
  * Full keyboard shortcuts (`Ctrl+Z`, `Ctrl+Y`, `Ctrl+C`, `Ctrl+V`, `Ctrl+B`, `Arrow keys`, `Tab`, etc.).
  * Multi-sheet tab navigation with double-click sheet renaming.
  * Auto-saves changes to local browser storage.

---

## 🛠️ Tech Stack

* **HTML5**: Application structure and layout.
* **CSS3**: CSS Grid and variables for high-performance spreadsheet rendering.
* **JavaScript (ES6+)**: Custom formula lexer/parser, evaluation engine, and UI logic.

---

## 📂 Project Structure

```text
.
├── spreadsheet.html   # Single-file standalone app containing HTML, CSS, and JS
└── README.md          # Project documentation
