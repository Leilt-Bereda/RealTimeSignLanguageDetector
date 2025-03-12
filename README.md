🚀 Overview

  This project showcases a real-time Sign Language Detector that uses AI to recognize common sign language gestures via a webcam. Built with TensorFlow Object Detection API and OpenCV, this system demonstrates the power of computer vision in accessibility and communication.


🔥 Key Highlights:

📸 Image Collection – Captured real-world sign language poses.

🏷️ Data Labeling – Processed dataset with accurate annotations.

🔄 Transfer Learning – Leveraged pre-trained models for efficiency.

🎯 Real-Time Detection – Detects gestures instantly via a webcam.
  
🚀 AI-Powered Model – Based on SSD MobileNet V2 for fast predictions.


📊 Dataset & Model Training

  📷 Image Collection & Annotation
  
The dataset consists of multiple labeled images representing five key sign language gestures:

    ✋ Hello
    👍 Yes
    👎 No
    🙏 Thank You
    🤟 I Love You
Annotation Process:

Using LabelImg, bounding boxes were drawn to accurately label gestures. This ensures the model understands distinct hand shapes.


🏗️ Model Training & Optimization

Training was conducted using transfer learning with TensorFlow’s SSD MobileNet V2 architecture, leveraging pre-trained weights for improved accuracy.

🔹 Steps in Training:

Pre-processing – Convert labeled images into TFRecords.

Fine-Tuning – Train the model on sign language gestures.

Performance Evaluation – Validate results with unseen test data.


🙌 Acknowledgments

  🏆 TensorFlow Object Detection API – https://github.com/tensorflow/models
  
  📸 OpenCV – https://opencv.org/
  
  🏷️ LabelImg – https://github.com/tzutalin/labelImg


