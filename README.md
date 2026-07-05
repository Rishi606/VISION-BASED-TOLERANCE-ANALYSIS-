# VISION BASED TOLERANCE ANALYSIS

A web-based dimensional inspection project that compares a product sample with a master sample using image processing. The project uses a reference coin for scale calibration and calculates the object perimeter to determine whether the product passes or fails inspection.

## Features

- Capture master sample image
- Capture product sample image
- Uses coin diameter for scale calibration
- Detects object contour using OpenCV.js
- Compares product perimeter with master perimeter
- Shows PASS/FAIL result based on match percentage

## Tech Stack

- HTML
- CSS
- JavaScript
- OpenCV.js

## How It Works

1. Place a coin and the object clearly in the camera frame.
2. Capture the master sample.
3. Capture the product sample.
4. The system calculates the product match percentage.
5. If the match is 97% or above, the product passes.

## Project Files

- `index.html` — Main webpage structure
- `style.css` — Styling and layout
- `script.js` — Image processing and comparison logic

## Usage

Open `index.html` in a browser.  
Allow camera access when prompted.  
Capture the master sample first, then capture the product sample.

## Result

The system displays:

- Master perimeter in millimeters
- Product match percentage
- PASS or FAIL status

## Author

Rishi Vishwakarma
