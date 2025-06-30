![79d9cf1a-ddc7-4710-a80e-3defb391de06](https://github.com/user-attachments/assets/64396bfd-3855-449a-8055-773b0a6300ed)# Pneumonia-Detection-with-Deep-Learning-using-CNNs
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
<img width="936" alt="image" src="https://github.com/user-attachments/assets/f2ed5d92-553c-4fda-b2d1-74060cd0f88c" />

### Result training 
<img width="991" alt="image" src="https://github.com/user-attachments/assets/f16f77b2-ea05-4767-b0d7-2155e38f63c2" />
<img width="830" alt="image" src="https://github.com/user-attachments/assets/7d6fe749-d497-4557-9ff8-5c9365b1322d" />




