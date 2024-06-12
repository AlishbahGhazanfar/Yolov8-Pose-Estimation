# Yolov8-Pose-Estimation

This project demonstrates the use of YOLOv8 for pose estimation. It involves loading a pretrained YOLOv8 model from Ultralytics, training the model on the COCO8 dataset, and using it to analyze video files for pose estimation. The results are saved and visualized using Matplotlib.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/yolov8-pose-estimation.git
   cd yolov8-pose-estimation
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Load and Train the Model:

   Load a pretrained YOLOv8 model from Ultralytics and train it on the COCO8 dataset for pose estimation.

2. Analyze Video Files:

   Replace `video_path.mp4` with the path to your video file and run the pose estimation.

3. Visualize the Results:

   Use Matplotlib to display the saved results.

## Examples

Here are some screenshots of the application in action:

- Output Image
- ![val_batch0_pred](https://github.com/AlishbahGhazanfar/Yolov8-Pose-Estimation/assets/171797920/4f76e0bd-568a-4db7-bf06-8671476d5877)
![val_batch0_labels](https://github.com/AlishbahGhazanfar/Yolov8-Pose-Estimation/assets/171797920/16c06786-c771-413b-b1fb-4416f1c451a4)
![train_batch1](https://github.com/AlishbahGhazanfar/Yolov8-Pose-Estimation/assets/171797920/eb1ac742-7aa5-4827-8a3b-8928e6003e73)


## Acknowledgements

- YOLOv8
- Matplotlib
