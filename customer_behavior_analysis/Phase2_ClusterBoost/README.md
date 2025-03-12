📌 **Phase 2 - Cluster Boost Model**  

# 📖 Overview  
The **Cluster Boost Model** is an advanced **ensemble learning approach** designed to enhance customer behavior analysis in **e-commerce**.  
This model builds upon **stacking techniques** to improve **prediction accuracy** and **personalization**.  

## 🔍 Key Features  
✅ **Combines Clustering & Boosting**: Uses **clustering techniques** to group similar customers and applies a **boosting model** for refined predictions.  
✅ **Higher Accuracy**: Achieves **97.62% accuracy**, surpassing traditional models.  
✅ **Adaptive Learning**: Leverages **cluster-based segmentation** to optimize personalization strategies.  

## 🏗 Model Architecture  

### 1️⃣ Data Preprocessing  
- Handles **missing values**, **outliers**, and **feature scaling**.  
- Uses **median imputation** for `reviews_per_month`.  

### 2️⃣ Feature Engineering  
- Creates **new features** based on **customer interaction patterns**.  
- Employs **one-hot encoding** and **dimensionality reduction**.  

### 3️⃣ Clustering Analysis  
- Groups customers using **K-Means** or **Hierarchical Clustering**.  
- Determines **optimal clusters** based on **Silhouette Scores**.  

### 4️⃣ Boosting Model (Cluster Boost)  
- Uses **Gradient Boosting (GB)** to make **predictions within each cluster**.  
- Assigns **different weightages** to clusters based on **past behavior**.  

### 5️⃣ Evaluation & Metrics  
- Assesses performance using **accuracy, precision, recall, and F1-score**.  
- Compares against baseline models (**Random Forest, XGBoost**).  

## 🛠 How to Run  
1. Open **Jupyter Notebook** or **Google Colab**.  
2. Run all cells in **phase2_cluster_boost_model.ipynb**.  
3. Review **performance metrics** and **cluster visualizations**.  

## 📌 Conclusion  
The **Cluster Boost Model** effectively enhances **customer behavior predictions**, helping **e-commerce businesses** deliver **better recommendations** and **personalized experiences**.  
