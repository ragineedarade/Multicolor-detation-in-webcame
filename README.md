 # 🎨 Multi-Color Detection using OpenCV

A real-time color detection tool built with Python, OpenCV, and NumPy. This project identifies multiple predefined colors from your webcam feed using HSV color segmentation and displays bounding boxes with labels around each detected color.

---

## ✨ Features

✅ Detects multiple colors in real-time  
✅ Uses HSV color space for better accuracy  
✅ Highlights detected colors with bounding boxes & labels  
✅ Easily customizable to add new color ranges  
✅ Lightweight and efficient using OpenCV  

---

## 🎯 Colors Detected

- 🔴 Red  
- 🟠 Orange  
- 🟡 Yellow  
- 🟢 Green  
- 🌌 Sky Blue  
- 🔵 Blue  
- 🟣 Purple  
- 🌸 Pink  
- 🟤 Brown  
- 🌊 Cyan  
- ✨ Gold  
- ⚫ Black  
- ⚪ White  
- 🤎 Skin  

---

## 🧰 Tech Stack

- 🐍 Python  
- 👁️‍🗨️ OpenCV  
- 🔢 NumPy  

---

## ▶️ How to Run the Project

### 🔧 1. Install Dependencies

Make sure Python is installed, then open your terminal and run:

 
pip install opencv-python numpy

🚀 2. Run the Script
 
python color_detection.py
🔴 Press q to quit the program at any time.

 ⚙️ How It Works
Captures video frame-by-frame from your webcam

Converts each frame to HSV color space

Creates masks for each color range

Detects contours in the masked regions

Draws bounding boxes around regions with significant color presence

Labels each box with the corresponding color name

🧪 Customization
You can add or edit color detection ranges in the color_defs list within the script. Example format:

python
 
{"name": "ColorName", "ranges": [([H_min, S_min, V_min], [H_max, S_max, V_max])]}
To add a new color, just follow the same structure!

📸 Output Example
When you run the script, a window will open showing the webcam feed like this:

diff
 
+---------------------------+
| [ Sky Blue ]             |
| [ Red ]                  |  ← Bounding boxes & labels
|                           |
+---------------------------+
✅ Objects matching the color ranges will be outlined with a label in real-time.

📄 License
This project is open-source and free to use.
Feel free to fork, modify, and enhance it for your own use cases. Contributions are welcome!

🚀 Contributions
Want to contribute? You can:

Add more colors or improve range accuracy

Implement shape or object detection alongside

Optimize performance for low-end systems

💡 Happy Coding!

yaml
 

---

Let me know if you’d like a matching **project thumbnail**, **GIF demo**, or a **video recording** to add under the “Output Example” section!







