1. Overview
This repository provides the dataset used to train and evaluate the YOLO-based dust detection and tracking models in our study. The dataset is made publicly available to support reproducibility, benchmarking, and further research on dust generation.

2. Dataset Contents
Images: High-resolution frames.
Annotations (YOLO format): Bounding boxes of 'jet-stone' and 'jet'.
Class definitions included in classes.txt.

3. Folder Structure
YOLO
 |- ...(ultralytics or something else)
 |- datasets
      | - train
      |    | - images
      |    | - labels
      | - val
           | - images
           | - labels
      
