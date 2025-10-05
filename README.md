# DA5401 A5: Visualizing Data Veracity Challenges in Multi-Label Classification

***Name:** Aaradhya Dashore* <br>
***Roll No:** ME22B089*

---

1. **Data Simplification:**  
   Loaded the Yeast dataset, extracted 103 features and 14 binary labels, and reduced labels into 4 interpretable categories for visualization.
2. **Feature Scaling:**  
   Standardized all features using `StandardScaler` to ensure uniform contribution across dimensions.
3. **Manifold Visualization:**  
   Applied **t-SNE** (perplexity = 30) to reveal local structures and **Isomap** to preserve global manifold geometry.
4. **Veracity & Manifold Analysis:**  
   Detected noisy labels, outliers, and hard-to-learn regions; analyzed manifold curvature to explain why simple classifiers struggle on this dataset.
