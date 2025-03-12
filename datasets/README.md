# 📊 E-Commerce Datasets for Customer Behavior Analysis & Personalization
This folder contains two datasets used in different phases of our project.

---

## **1️⃣ Customer Behavior Dataset (`customer_behavior_dataset.csv`)**  
📌 **Purpose:**  
- Used in **Phase 1** for **customer behavior prediction** using a **Stacked RF+GB model**.  
- Used in **Phase 2** for **customer clustering** using the **Cluster Boost model**.  

📑 **Dataset Details:**  
- **Total Records:** [Specify total rows]  
- **Total Features:** [Specify total columns]  
- **Missing Values:** [Yes/No]  
- **Columns & Descriptions:**  
  - `customer_id` → Unique identifier for each customer.  
  - `age` → Customer's age.  
  - `gender` → Male/Female/Other.  
  - `purchase_frequency` → Number of purchases made.  
  - `average_spending` → Average amount spent per purchase.  
  - `category_preference` → Preferred product categories.  
  - `visit_frequency` → How often the customer visits the platform.  
  - `device_type` → Device used (Mobile, Desktop, Tablet).  
  - `payment_method` → Preferred payment method.  
  - `last_purchase_date` → Date of the last purchase (`YYYY-MM-DD`).  
  - `customer_segmentation_label` → Labels from clustering (Phase 2).  
  - `personalization_score` → Effectiveness of recommendations (Phase 2, range: 0-1).  

---

## **2️⃣ Personalized Recommendation Dataset (`personalized_recommendation.csv`)**  
📌 **Purpose:**  
- Used **only in Phase 2** for **personalized product recommendations**.  

📑 **Dataset Details:**  
- **Total Records:** [Specify total rows]  
- **Total Features:** [Specify total columns]  
- **Missing Values:** [Yes/No]  
- **Columns & Descriptions:**  
  - `review_id` → Unique identifier for each review.  
  - `customer_id` → Links review to a customer (if applicable).  
  - `product_id` → Unique product identifier.  
  - `product_category` → Category of the reviewed product.  
  - `rating` → Customer rating (1-5).  
  - `review_text` → Written feedback from customers.  
  - `sentiment_score` → Sentiment analysis score (e.g., -1 to 1 for Negative to Positive).  
  - `recommended` → Whether the product was recommended (`Yes/No`).  

---

### **📢 How to Use These Datasets?**  
- Load `customer_behavior_dataset.csv` for behavior analysis and clustering.  
- Use `personalized_recommendation.csv` for building the recommendation model.  

---

