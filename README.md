## Month Calendar

A clean, responsive web-based **Month Calendar** built using HTML, CSS, and vanilla JavaScript. It dynamically displays the current month, full date, and highlights the current day on a Monday-to-Sunday grid.

## Features

* **Dynamic Date Rendering:** Automatically detects the current month, year, and exact day of the week using JavaScript's built-in `Date` object.
* **Current Day Highlight:** Automatically highlights today's date in blue so it stands out on the calendar grid.
* **Monday-First Week Layout:** Displays days aligned from **Monday** through **Sunday** with automatic empty slot padding at the start of the month.
* **Interactive Hover Effects:** Highlights valid date cells when hovered over while ignoring empty placeholder slots.

## Built With

* **HTML5** – Semantic structure for the calendar container, header, weekdays, and day grid.
* **CSS3** – Flexbox layout, custom card styling, rounded corners, drop shadows, and hover states.
* **JavaScript (ES6)** – DOM manipulation and date calculations (`getMonth()`, `getFullYear()`, `getDate()`, `getDay()`).

## Project Structure

```text
month-calendar/
├── index.html      # Main HTML structure
├── style.css       # Styling and layout rules
└── script.js       # Dynamic date generation logic
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com
   ```
2. **Navigate to the project folder**
   ```bash
   cd month-calendar
   ```
3. **Run the project**
   Open `index.html` directly in any web browser. No build tools or external dependencies are required.

## Future Improvements

* Add **Previous** and **Next** buttons to navigate across different months and years.
* Allow users to click on a specific date to add notes or reminders.
* Fix minor typos in CSS (`box-sizing: border-box;` and class naming `.calendar`).
