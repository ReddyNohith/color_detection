# Color Detection using Python, OpenCV & Pandas

## Overview

This project is a simple and interactive Color Detection Application built using Python, OpenCV, and Pandas. The application allows users to double-click anywhere on an image to identify the closest matching color name along with its RGB values.

It uses a CSV file containing color information and compares pixel values from the selected image to find the nearest matching color.

---

## Features

* Detect colors directly from images
* Displays:

  * Color Name
  * RGB Values
* Interactive mouse double-click detection
* Real-time color preview
* Beginner-friendly project using Python

---

## Technologies Used

* Python
* OpenCV
* Pandas

---

## Project Structure

```bash
Color-Detection/
│
├── color_detection.py
├── colors.csv
├── Picture1.jpg
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/color-detection.git
cd color-detection
```

### 2. Install Required Libraries

```bash
pip install pandas opencv-python
```

---

## How to Run

```bash
python color_detection.py
```

---

## Usage

1. Run the Python script.
2. An image window will open.
3. Double-click anywhere on the image.
4. The application will display:

   * Detected Color Name
   * RGB values
5. Press `ESC` to exit.

---

## Example Output

* Double-clicking on a red object may display:

```bash
Red R=255 G=0 B=0
```

---

## Key Concepts Used

* Image Processing with OpenCV
* Mouse Event Handling
* CSV Data Handling with Pandas
* RGB Color Matching Algorithm

---

## Future Improvements

* Add HEX color code display
* Support webcam-based live color detection
* Improve UI design
* Add custom image upload support

---

## Author
P Reddy Nohith
Developed as a beginner-friendly Computer Vision mini project using Python.

---

## License

This project is open-source and free to use for learning purposes.
