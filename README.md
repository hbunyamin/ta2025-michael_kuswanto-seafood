# Tugas Akhir Michael Kuswanto (2172037)
## Penggunaan Model Pre-trained Convolutional Neural Network untuk Klasifikasi Makanan Seafood

### Abstract
Seafood allergies such as shrimp, crab, shellfish, and fish are common triggers of allergic reactions that can pose serious health risks. To address the challenge of identifying foods containing allergens, this study developed an image classification system based on Convolutional Neural Networks (CNN) using MobileNetV2 and EfficientNetV2-S architectures. Data was collected through web scraping and preprocessed via resizing, normalization, and augmentation. The models were trained using pretrained
weights with manually tuned hyperparameters, including dropout, regularization, and fine-tuning strategies. Evaluation was conducted using accuracy, precision, recall, and F1-Score. The best-performing model, EfficientNetV2-S, achieved an accuracy of 97,5%, precision 97,59%, recall 97,5%, dan F1-score 97,5%, and showed greater stability in avoiding overfitting compared to MobileNetV2. The optimal hyperparameters included a dropout rate of 0.5, L1 and L2 regularization values of 0.01 each, a batch
size of 32, and frozen layers. The trained model was converted into TensorFlow Lite format and integrated into the FoodLergic mobile application. Final testing on new images and through the mobile interface demonstrated consistent and accurate predictions. These findings suggest the system is feasible as an initial solution for detecting food allergens through images on mobile devices.
    
**Keywords**: Convolutional Neural Network, EfficientNetV2-S, food allergy, MobileNetV2, TensorFlow Lite   
   
### Link : [tar.gz](https://drive.google.com/file/d/1GMH-ioKitBwh8BnHnW9zFZ_ken1SR9K2/view?usp=sharing) 
