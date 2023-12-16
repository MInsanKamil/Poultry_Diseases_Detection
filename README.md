## Poultry Diseases Detection

Kaggle Notebook: https://www.kaggle.com/insankamil1004/kamil-yolov8

### CIoU Loss Function

The CIoU loss function is defined as:

\[ L_{CIoU} = 1 - IoU + \frac{d^2}{C^2} + \alpha v \]

### Model Evaluation

- **Total Loss:** 1.2307
  - Box Loss: 1.0388
  - Class Loss: 0.1919

- **Total Validation Loss:** 1.3289
  - Validation Box Loss: 1.1277
  - Validation Class Loss: 0.2012

- **Mean Average Precision(MaP):** 0.4252
  - MaP@[IoU=50]: 0.6511
  - MaP@[IoU=75]: 0.4607
  - MaP@[area=small]: 0.2214
  - MaP@[area=medium]: 0.3984
  - MaP@[area=large]: 0.5520

- **Recall**
  - Recall@[max_detections=1]: 0.4525
  - Recall@[max_detections=10]: 0.5031
  - Recall@[max_detections=100]: 0.5031
  - Recall@[area=small]: 0.2531
  - Recall@[area=medium]: 0.4696
  - Recall@[area=large]: 0.6417
