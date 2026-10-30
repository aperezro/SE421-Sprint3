# Complexity Lab

An interactive, browser-based teaching visualization for **SE/CprE 4210 Learning Sprint #3, Problem 5**.

## What it teaches

The app compares the abstract operation counts of four common growth patterns:
- Binary search: `O(log n)`
- Linear search: `O(n)`
- Nested loops: `O(n²)`
- Branching recursion: `O(2ⁿ)`

It connects rapid algorithmic growth to the concept of **algorithmic-complexity denial of service** without running harmful or expensive code.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in any modern web browser.
3. Move the input-size slider, select an algorithm, or use the increment/reset buttons.

No build tools, servers, dependencies, or API keys are required.

## Try an experiment

Select `O(2ⁿ)` and compare the operation count at `n = 10` and `n = 20`. It rises from 1,024 to 1,048,576 operations—a 1,024× increase for only 10 more input units.

## Implementation and limitations

Written in HTML, CSS, and vanilla JavaScript. The counts are simplified theoretical models rather than measured runtime; actual implementations can differ by constant factors and input characteristics. The bar chart uses the exponential value as its scale to highlight differences in growth.

## Repository contents

- `index.html` — complete interactive app
- `README.md` — overview and instructions
- `reflection.md` — learning and development reflection
