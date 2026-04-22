# Image to GIF Creator

This Python script creates a GIF from multiple image files using the `imageio` library.

## 📌 Description
The script reads a list of image files and combines them into a single animated GIF.

## 🛠️ Requirements
- Python 3.x
- imageio library

Install the required library using:
pip install imageio

## 📂 Files
Make sure the following image files are in the same directory:
- team-pic1.png
- team-pic2.png

## ▶️ How to Run
Run the script using:
python import_imageio.py

## ⚙️ Output
- The script generates a file named `team.gif`
- Each image is displayed for 500 milliseconds
- The GIF loops infinitely

## 📌 Code Overview
- Reads images using `imageio.v3.imread()`
- Stores them in a list
- Writes them into a GIF using `imageio.v3.imwrite()`

## 📎 Script Reference
See the Python file here: :contentReference[oaicite:0]{index=0}
