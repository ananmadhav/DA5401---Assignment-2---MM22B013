# DA5401 – Assignment 2

**Name:** Anan Madhav T V  
**Roll Number:** MM22B013  

---

## 📂 Folder Structure  

├── DA5401_A2_MM22B013.ipynb       # Main Jupyter Notebook  
├── README.md                          # Documentation file  
└── mushrooms.csv                      # Mushroom dataset

---

## ⚙️ How to Run  
1. Open the notebook `DA5401_PCA_MM22B013.ipynb` in **Jupyter Notebook** or **Google Colab**.  
2. Ensure the `mushrooms.csv` file is present in the same directory.  
---
## 📌 Documentation & Insights  

### 🔹 EDA & Preprocessing  
- One-hot encoding expands categorical attributes into a high-dimensional feature space.  
- Standardization ensures balanced contribution from each feature before applying PCA.  

### 🔹 PCA Analysis  
- A **scree plot** and **cumulative explained variance plot** guide the choice of optimal components.  
- Projection onto the first two PCs shows clear separability between edible and poisonous mushrooms.  

### 🔹 Model Evaluation  
- Logistic Regression on the **original features** achieves **100% accuracy**, since the dataset is perfectly separable.  
- Logistic Regression on **PCA-transformed features** (95% variance retained) achieves **~99.9% accuracy**.  

