# Smart-Fruit-Distribution-System
This project uses deep learning (ResNet-50) to predict the remaining shelf life of bananas based on their images, supporting sustainability-focused decisions.

📌 Problem -
Food waste is a major global challenge. This model helps in classifying bananas by estimated shelf life so they can be directed to:
- Warehouses for export
- Nearby vendors for quick sale
- Processing units (juice, pulp) if nearing spoilage

🚀 Features -
- ResNet-50 pretrained backbone
- Balanced dataset using augmentation
- Regression model outputting shelf life in days
- Sustainability-based recommendations

🛠 Tech Stack - 
- Python
- TensorFlow
- OpenCV
- NumPy 

📂 Folder Structure - 
banana-shelf-life-model/
│
├── Banana_Shelf_Life_Model.ipynb         
├── best_banana_model.h5                  
├── README.md                                    
│
├── dataset_sample/
│   ├── Banana(1-5)/                      
│   ├── Banana(5-10)/
│   ├── Banana(10-15)/
│   └── Banana(15-20)/
│
