 # Multi-Color Detection using OpenCV

This Python project detects multiple predefined colors in real-time using your webcam. It utilizes the HSV color space to identify various color ranges and highlights them with bounding boxes and labels on the video feed.

## 📌 Features

- Real-time webcam capture
- Detection of multiple colors (Red, Orange, Yellow, Green, Blue, Purple, etc.)
- Bounding box with label for each detected color
- Easily extensible: Add or modify color ranges in HSV space

## 🎯 Colors Detected

- Red
- Orange
- Yellow
- Green
- Sky Blue
- Blue
- Purple
- Pink
- Brown
- Cyan
- Gold
- Black
- White
- Skin

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy

## ▶️ How to Run

### 1. Install Dependencies

Ensure you have Python installed. Then, install the required libraries:

```bash
pip install opencv-python numpy
2. Run the Script
bash
Copy
Edit
python color_detection.py
Press q to quit the program.

🔧 How it Works
The webcam feed is read frame-by-frame.

Each frame is converted to the HSV color space.

For each color range defined, a mask is created.

Contours are found in the mask.

If the contour area is above a threshold, a bounding rectangle is drawn.

The color name is labeled above the rectangle.

📝 Customization
You can tweak or add more color ranges by modifying the color_defs list inside the script. Each range is defined in HSV format as:

python
Copy
Edit
{"name": "ColorName", "ranges": [([H_min, S_min, V_min], [H_max, S_max, V_max])]}
📷 Output Example
When the script runs, it opens a window showing the webcam feed with real-time boxes and color labels around detected color regions.

📄 License
This project is open-source and available for modification and distribution.

Feel free to contribute by improving detection accuracy, optimizing performance, or adding new features like shape detection!

yaml
Copy
Edit

---

Would you like a sample image or GIF to include in the README as a visual example?
