# Faster RCNN using MMDetection Notebook Pipeline

A streamlined, all-in-one Jupyter Notebook-based pipeline for object detection using MMDetection's Faster R-CNN. This project provides a comprehensive setup for training, testing, and visualizing results, with minimal configuration required. Simply modify the data conversion function and model configuration to get started!



## Getting Started

### Prerequisites
1. Clone this repository:
   ```bash
   git clone https://github.com/MjdMahasneh/object_detection_with_mmdetection_tutorial.git
   cd object_detection_with_mmdetection_tutorial
   ```


Install the dependencies:

```bash
pip install -r requirements.txt
```

Ensure you have the required dataset, formatted appropriately or ready to be converted to COCO format.

### Usage
Open the notebook:

```bash
jupyter notebook faster_rcnn_pipeline.ipynb
```

- Modify the Data Conversion Function: Update the section for converting your dataset to COCO format.

- Configure the Model: Adjust the Faster R-CNN configuration file as per your dataset requirements.

- Run Training and Testing: Execute cells to train and test the object detection model.

- Visualize Results: Use the integrated visualization scripts to inspect results.



