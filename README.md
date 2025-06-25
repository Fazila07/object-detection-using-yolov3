🎯 Real-Time Object Detection with YOLOv3, OpenCV, and Text-to-Speech (TTS)
This project leverages the YOLOv3 model to detect objects from a webcam feed in real time and uses Text-to-Speech (TTS) to announce the detected objects out loud. It combines OpenCV, Darknet pre-trained YOLOv3, and pyttsx3 to bring vision and voice together in one cool demo.

✨ Features
🖥️ Captures video from your webcam live

🎯 Detects objects using YOLOv3 (pre-trained on COCO dataset)

🧠 Labels each object with a bounding box and confidence

🔊 Speaks out detected object names using pyttsx3

🚫 Avoids repeating the same object names too frequently

🛠 Tech Stack
Component	Technology
Object Detection	YOLOv3 (Darknet model via OpenCV DNN)
Video Input	OpenCV (cv2)
Text-to-Speech	pyttsx3
Programming Lang	Python 3.x

📦 Requirements
Install dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
requirements.txt should include:
Copy
Edit
opencv-python
numpy
pyttsx3
📁 Files Needed
Ensure the following YOLOv3 model files are in your project directory:

yolov3.cfg – YOLOv3 configuration file

yolov3.weights – Pre-trained weights (on COCO)

coco.names – List of object classes

🔗 Download from:

Weights: yolov3.weights

Config: yolov3.cfg

COCO Names: coco.names

▶️ How to Run
bash
Copy
Edit
python yolov3_tts.py
Or use it in Jupyter Notebook cell-by-cell for better understanding and customization.

📸 Sample Output
You’ll see webcam footage with bounding boxes and hear detected object names spoken out loud like:

“person... dog... car...”


## 📄 License

This project is licensed under the [MIT License](./LICENSE).
