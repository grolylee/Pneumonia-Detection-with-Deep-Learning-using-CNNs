# Pneumonia-Detection-with-Deep-Learning-using-CNNs
Object Detection using Convolutional Neural Network (CNN), Application of imgage precessing and AI to detect pneumonia, classification using X-ray images
# Project objective
1. Knowledge of Machine Learning and Deep Learning Techniques
2. Binary Classification for Pneumonia Detection
3. Retraining the Problem with Advanced Models
   - CNNs custom
   - VGG16
   - ResNet50
   - DenseNet-121
4. Model Improvement and Performance Evaluation
5. Deploy demo application

# Datashet 
**Source:** 
- Training: https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-penumonia/data​
- Validation: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia​

**Data augmentation**
- Flip, rotation, scale, random crop, translation, zoom.
<img width="397" alt="Data Augmentation" src="https://github.com/user-attachments/assets/31e08a88-1a9f-43a3-931c-02b05e95f504" />

# Traning model
## CNN Architecture
- Training: 1341 (NORMAL), 3875 (PNEUMONIA)
- 5 layers Convolution
- 3 layers Fully-Connected
- Softmax classifier
![79d9cf1a-ddc7-4710-a80e-3defb391de06](https://github.com/user-attachments/assets/f2925db1-02d5-402a-8b66-6e416444e941)

### Training model with 20 epochs

### Validation Model 
<img width="950" alt="cnn" src="https://github.com/user-attachments/assets/c354a2c2-53af-4505-a19b-23dc98676f01" />

## VGG16 Model 
- 16 layers included 13 layers CNNs and 3 layers Fully-Connected
  
<img width="649" alt="image" src="https://github.com/user-attachments/assets/c224e773-479f-4b86-a945-a2a7cf7523e4" />

## Resnet50
- All layers = 50 

## DenseNet-121
- 120 layers CNNs, 1 layers Fully-Connected and 4 layers Dense

<img width="713" alt="image" src="https://github.com/user-attachments/assets/fb8f42d1-821d-4c2d-901d-f4b5b8f4857a" />

# Result 
<img width="665" alt="image" src="https://github.com/user-attachments/assets/af69cd4f-861d-43c8-8e48-801c3b7fb22f" />

<img width="566" alt="image" src="https://github.com/user-attachments/assets/d9eca361-f380-438b-a2f7-84b48026343e" />

# Demo 
<img width="878" alt="image" src="https://github.com/user-attachments/assets/57cb5937-d2f1-4226-b5ff-82f5b126e5ec" />





