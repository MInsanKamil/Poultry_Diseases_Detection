## Poultry Diseases Detection

Kaggle Notebook: [Link to Notebook](https://www.kaggle.com/insankamil1004/kamil-yolov8)

Inference Notebook : [Link to Inference Notbook](https://github.com/MInsanKamil/Poultry_Diseases_Detection/blob/main/Poultry_Diseases_Detection_YOLOv8.ipynb)
## CIoU Loss Function (Box Loss)

$$ L_{CIoU} = 1 - \text{IoU} + \frac{d^2}{C^2} + \alpha v $$

Where:

$$ v = \frac{4}{\pi^2}(arctan\frac{w^{gt}}{h^{gt}} - arctan\frac{w}{h})^2 $$

$$ \alpha = \frac{v}{(1-IoU) + v} $$

## Model Evaluation

- **Total Loss:** 1.0158
  - Box Loss: 0.8695
  - Class Loss: 0.1463

- **Total Validation Loss:** 1.2293
  - Validation Box Loss: 1.0498
  - Validation Class Loss: 0.1795

- **Mean Average Precision(MaP):** 0.4681
  - MaP@[IoU=50]: 0.7298
  - MaP@[IoU=75]: 0.4896
  - MaP@[area=small]: 0.2132
  - MaP@[area=medium]: 0.4627
  - MaP@[area=large]: 0.5581

- **Recall**
  - Recall@[max_detections=1]: 0.4938
  - Recall@[max_detections=10]: 0.5425
  - Recall@[max_detections=100]: 0.5425
  - Recall@[area=small]: 0.2886
  - Recall@[area=medium]: 0.5252
  - Recall@[area=large]: 0.6294
