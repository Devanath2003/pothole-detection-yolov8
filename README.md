# Pothole Detection using YOLOv8

This project implements pothole detection on urban roads using YOLOv8.  
The model was trained on the **Pothole Segmentation YOLOv8 dataset from Roboflow**.

## Dataset
- Source: [Roboflow Pothole Dataset](https://universe.roboflow.com/farzad/pothole_segmentation_yolov8/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true)  
- Contains annotated images of potholes.

## Steps
1. Trained YOLOv8 model on the dataset using Google Colab.
2. Evaluated the model on test images/videos.
3. Saved trained weights and sample detection results.

## Files in this Repo
- `Pothole_Detection.ipynb` → Colab notebook with code.  
- `weights/best.pt` → Trained YOLOv8 model weights.  
- `results/` → Sample detection images and video outputs.  

## Sample Results
Example detections from test images:  

<img width="1445" height="725" alt="image" src="https://github.com/user-attachments/assets/e4a9a226-c649-4dfd-84cf-d15c805c270c" />



<img width="1771" height="838" alt="image" src="https://github.com/user-attachments/assets/1b8a518b-4d8b-4258-9b65-673c62bd8eaf" />




