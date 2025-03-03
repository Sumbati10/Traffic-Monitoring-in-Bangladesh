# Traffic Video Analysis with Object Detection

## Project Overview
In this project, I will be working with traffic video feed data from Dhaka, Bangladesh. The goal is to process each frame of video and detect and label objects such as cars and people in real-time. I will use a pre-trained YOLO (You Only Look Once) model and extend it to detect custom objects specifically for analyzing traffic feed data.

## Learning Objectives
By working on this project, I will learn:
- How to work with XML data containing bounding box annotations.
- How to extract frames from video files for object detection.
- How to apply a pre-trained YOLO object detection model.
- How to train YOLO to detect custom objects.
- How to augment data to enhance model performance.

## Technologies Used
- **Python** for scripting and data processing.
- **OpenCV** for video frame extraction and image processing.
- **YOLO (You Only Look Once)** for object detection.
- **TensorFlow/PyTorch** (optional) for training and extending models.
- **LabelImg** for annotating custom objects.
- **Pandas & NumPy** for data handling.

## Project Workflow
1. **Data Preparation**
   - Extract frames from traffic video footage.
   - Label and annotate objects (cars, people, etc.).
   - Convert XML bounding box annotations into a compatible format.
   
2. **Pre-trained YOLO Application**
   - Load and run YOLO on sample frames.
   - Evaluate detection accuracy.
   
3. **Custom Model Training**
   - Gather additional labeled data.
   - Fine-tune YOLO to recognize custom objects.
   - Train and test the extended model.
   
4. **Data Augmentation**
   - Apply transformations to improve model generalization.
   - Train the model on augmented data.
   
5. **Evaluation & Deployment**
   - Evaluate model accuracy using validation data.
   - Deploy the trained model for real-time detection.

## Installation & Setup
To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Sumbati10/Traffic-Monitoring-in-Bangladesh.git
   cd Traffic-Monitoring-in-Bangladesh
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download pre-trained YOLO weights:
   ```bash
   wget https://pjreddie.com/media/files/yolov3.weights
   ```

4. Run object detection on sample video:
   ```bash
   python detect.py --video input_video.mp4
   ```

## Contributing
If you'd like to contribute, please fork the repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License.https://creativecommons.org/licenses/by-nc-nd/4.0/ owned by @Worldquant University

