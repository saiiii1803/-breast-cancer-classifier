# Breast Cancer Classifier

This project uses a deep learning model to classify breast ultrasound images into three categories:

- Normal  
- Benign  
- Malignant  

## Files and Folders

- `billumain.ipynb`: Main notebook with model training, evaluation, and prediction.
- `benign/`, `malignant/`, `normal/`: Folders containing sample images for each class.
- `results/`: Folder where output images (like predictions, confusion matrix) are saved.

## Output

- Confusion matrix and ROC curve to evaluate the model.
- Gradio interface to test predictions using your own images.
- Visualization of 9 random predictions from the test dataset.

## Libraries Used

- PyTorch  
- torchvision  
- scikit-learn  
- matplotlib  
- numpy  
- gradio  

## Note

This is a basic image classification project for breast ultrasound images, aimed at educational purposes.

