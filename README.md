# object-detection-comparison
Performance comparison of deep learning models for image analysis, focusing on inference time, number of objects detected, and probabilities.

---

## Description  
This project compares the performance of two deep learning object detection models:  
- **Faster R-CNN** (Faster Region-Convolutional Neural Network)  
- **YOLO** (You Only Look Once)  

The comparison focuses on three key metrics:  
1. **Inference Time**: How quickly each model processes images.  
2. **Objects Detected**: Total number of objects identified by the model.  
3. **Probabilities**: Confidence scores of the detections.  

---

## Project Setup

### Dependencies
Ensure the following libraries and tools are installed:  
- **Python** (version 3.8 or above)  
- **PyTorch**  
- **TorchVision**  
- **Ultralytics**  
- **Pandas**  
- **Matplotlib**  
- **Pillow**

Install dependencies using:
```bash
pip install torch torchvision ultralytics pandas matplotlib pillow
```

---

### Installing
1. Clone the repository:
 ```bash
 git clone https://github.com/your-username/object-detection-comparison.git
 cd object-detection-comparison
 ```
2. Set up the images folder:
- Place all input images into a folder called **images**.
- The script will automatically read images from this folder.

### Execution
Run the main script to process the images and compare the models.
1. Open Jupyter Notebook:
```bash
jupyter notebook
```
2. Run the following notebook:
```bash
object_detection_comparison.ipynb
```

The script will:
- Display annotated images with bounding boxes and confidence scores.
- Export the performance results to `object_detection_results.csv`.

---

## Author
Kempton McCarty
- Email: [kempton@berkeley.edu](mailto:kempton@berkeley.edu)  
- LinkedIn: [linkedin.com/in/kempton-mccarty](https://linkedin.com/in/kempton-mccarty)  
