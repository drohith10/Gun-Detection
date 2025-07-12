# Gun-Detection
# 🔫 Gun Detection using YOLOv5 (Object Detection Project)

This project uses the **YOLOv5 object detection algorithm** to detect guns in images and videos. It was built using Python and trained/fine-tuned using labeled gun image datasets. The goal is to identify and locate firearms in real-time, which can be applied in surveillance, security, and threat detection systems.

## 🧠 Key Features
- Detects guns with high accuracy using YOLOv5
- Real-time video processing
- Built and tested using Python (Google Colab environment)
- Custom dataset training supported

## 🛠️ Tech Stack
- Python
- [YOLOv5](https://github.com/ultralytics/yolov5)
- OpenCV
- PyTorch
- Google Colab
- LabelImg (for annotation, if needed)

## 📁 Project Structure
├── gun_detection_yolov5.ipynb # Main notebook

├── runs/ # Output results (images/videos with detections)

├── data/ # Training dataset (images + labels)

├── yolov5/ # YOLOv5 clone from Ultralytics

├── requirements.txt # Dependencies

└── README.md # Project documentation


## 🚀 How to Run the Project

1. Clone the YOLOv5 repository:
   ```bash
   git clone https://github.com/ultralytics/yolov5
   cd yolov5
   pip install -r requirements.txt
Prepare your dataset in YOLO format (images + .txt label files).

Run the notebook (gun_detection_yolov5.ipynb) in Google Colab or locally:

For training: use the train.py script or notebook cells.

For inference on custom images or videos:
python detect.py --weights runs/train/exp/weights/best.pt --img 640 --source path_to_image_or_video
📊 Results:

🔍 The model achieves ~90% accuracy on the custom gun detection dataset after training for 50+ epochs.

📦 Dataset
You can use any gun image dataset in YOLO format.

Alternatively, annotate your own dataset using LabelImg.

📌 Applications
Public surveillance systems

School/airport security

Real-time threat detection systems

📄 License
This project is open-source and for educational purposes only. Make sure to follow ethical AI practices when using it in real-world scenarios.

🙋‍♂️ Author
Rohith Daram

GitHub:drohith10
