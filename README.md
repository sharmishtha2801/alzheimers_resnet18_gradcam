# alzheimers_resnet18_gradcam
CNN+ Grad-CAM based Alzheimer's detection from MRI scans using ResNet18.

# Alzheimer's Disease Detection using ResNet-18 and Grad-CAM

This project uses a deep learning model (ResNet-18) to classify MRI brain scans and detect Alzheimer's disease. Grad-CAM is applied to visualize important brain regions contributing to the model's decisions.

## 🔧 Tools & Technologies
- Python, PyTorch, torchvision
- Grad-CAM, NumPy, Matplotlib
- Jupyter Notebook, Google Colab

- # 📂 Project Structure
- alzheimers_resnet18_gradcam/
├── model/ # Pretrained ResNet18 model
├── outputs/ # Grad-CAM visualizations
├── data/ # Sample MRI scan(s)
├── alzheimers_resnet18_gradcam.ipynb # Main notebook
├── README.md

Dataset used: Alzheimer's MRI dataset from Kaggle](https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images) 
Classes: Alzheimer's Disease, Mild Cognitive Impairment, Normal  

## 🚀 How to Run
1. Clone the repository
2. Open main_notebook.ipnyb in Jupyter or Google Colab.
3. Make sure the model (resnet18_trained_model.pth) is in the model/ folder.
4. Run all cells to see classification results and Grad-CAM output.

## Sample Output
![Grad-CAM Output](https://github.com/user-attachments/assets/dd7f5302-80fc-4888-b846-f613fca563c1)

#### 👩‍💻 Author
Sharmishtha Bharti (https://github.com/sharmishtha2801)
