# D4 Cow Counter

A lightweight counter designed for tracking progress toward the secret cow level in Diablo IV. The goal is to reach 666 cows, making it easier to monitor progress while farming.

## About

This project was created while farming the secret cow level in Diablo IV, where the goal is to reach 666 cows to trigger the drop and continue the quest.

The idea was simple: keep track of how many cows were killed during each run without losing progress or doing the math manually.

It is a lightweight browser utility built for quick and practical use while farming.

## Live Demo

https://gabriel-brasil.github.io/d4-cow-counter/

## Features

- Increment the counter by clicking a number
- Decrement the counter by right-clicking a number
- Reset the counter at any time
- Visual progress bar showing how close you are to the goal
- Persistent state saved in localStorage
- Simple and responsive UI

## How it works

This project is a small front-end app that:
- renders number buttons dynamically
- updates the displayed counter
- calculates the progress percentage toward 666
- persists the current value in the browser

## Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/gabriel-brasil/d4-cow-counter.git
   ```

2. Navigate to the project folder:
   ```bash
   cd d4-cow-counter
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Compile the TypeScript:
   ```bash
   npm run build
   ```

5. Open `index.html` in your browser.

## Project Structure

```text
d4-cow-counter/
├── index.html
├── package.json
├── tsconfig.json
├── src/
│   ├── script.ts
│   └── style.css
├── dist/
│   └── script.js
├── README.md
└── .gitignore
```

## Controls

- Left click: add the selected value
- Right click: subtract the selected value
- Reset button: clears the counter

## Notes

This project is intentionally simple and lightweight, created as a practical tool for farming and tracking progress during Diablo IV runs.
