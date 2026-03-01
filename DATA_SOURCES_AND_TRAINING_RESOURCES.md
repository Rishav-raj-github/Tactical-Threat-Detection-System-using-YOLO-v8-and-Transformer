# Threat Detection Training Data & Resources

Comprehensive guide to datasets, models, and tools for threat detection, anomaly detection, and object recognition.

## Object Detection Datasets

### YOLO Datasets
- **COCO 2017** - https://cocodataset.org/ (330K images, 80 classes, object detection)
- **OpenImages** - https://storage.googleapis.com/openimages/web/index.html (9M images, 600 classes)
- **Roboflow Universe** - https://universe.roboflow.com/ (thousands of labeled datasets)

### Threat & Weapon Datasets
- **Gun Detection Dataset** - https://www.kaggle.com/datasets/andrewmvd/gun-dataset
- **Weapons Detection** - https://github.com/pierluigiferrari/ssd_keras/blob/master/notebooks/data.py

## Pretrained Models

### YOLOv8
- Official: https://github.com/ultralytics/ultralytics
- Weights: https://docs.ultralytics.com/tasks/detect/#models
- YOLOv8n, YOLOv8s, YOLOv8m, YOLOv8l, YOLOv8x variants

### Vision Transformers
- HuggingFace Vision Transformer: https://huggingface.co/facebook/deit-base-distilled-patch16-224
- Swin Transformer: https://github.com/microsoft/Swin-Transformer

### Anomaly Detection Models
- Isolation Forest: scikit-learn
- Autoencoders: TensorFlow/Keras
- One-Class SVM: scikit-learn

## Video Surveillance Datasets

### Video Action Recognition
- **UCF101** - 13,320 videos, 101 action classes
- **Kinetics-700** - https://www.deepmind.com/open-source/kinetics
- **ActivityNet** - https://www.activity-net.org/

## Data Augmentation Tools

```bash
# Using Albumentations
pip install albumentations

# Using imgaug
pip install imgaug

# Using torchvision transforms
pip install torchvision
```

## Performance Benchmarks

- YOLOv8 mAP50: 87.5% (COCO)
- YOLOv8 Speed: 2.3ms (GPU)
- Vision Transformer Accuracy: 88.0% (ImageNet)

## Training & Validation

- Train/Val/Test Split: 70/15/15
- Image Size: 640x640
- Batch Size: 32-64 (GPU dependent)
- Epochs: 100-300
- Learning Rate: 0.001 (with warmup)

## Tools & Libraries

- **OpenCV**: Image processing
- **PyTorch**: Deep learning framework
- **Ultralytics**: YOLO implementation
- **TensorFlow**: Alternative DL framework
- **Albumentations**: Data augmentation
