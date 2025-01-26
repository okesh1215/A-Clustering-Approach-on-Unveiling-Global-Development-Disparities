# Cluster-Based-Classification-of-Students-Responses-to-Algebraic-Questions
# A Clustering Approach on Unveiling Global Development Disparities

## Overview
This project focuses on analyzing global development disparities by exploring socio-economic and development indicators of over 208 countries. The aim is to identify patterns, relationships, and regional classifications using advanced data analysis techniques like clustering, hypothesis testing, and attribute independence analysis.

The study emphasizes the importance of socio-economic variables such as birth rate, infant mortality, GDP, business tax rates, and energy in understanding development outcomes. It also highlights how clustering methods can group countries based on similar characteristics, aiding policy-making and fostering economic and social progress.

---

## Key Objectives
- Analyze 25 development variables from 208 countries.
- Identify relationships and interdependencies between socio-economic indicators using hypothesis testing.
- Evaluate clustering techniques for segmenting countries with similar characteristics.
- Compare clustering methods, including:
  - **K-Means**
  - **Hierarchical Clustering**
  - **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
  - **Spectral Clustering**
- Assess the impact of preprocessing methods, such as:
  - **Principal Component Analysis (PCA)**
  - **t-Distributed Stochastic Neighbor Embedding (t-SNE)**

---

## Features
1. **Data Preprocessing:**  
   - Handle outliers and preprocess high-dimensional datasets for better clustering results.
   
2. **Clustering Techniques:**  
   - Apply and compare K-means, Hierarchical Clustering, DBSCAN, and Spectral Clustering methods.
   - Evaluate clustering performance using metrics like **Silhouette Score**.
   
3. **Statistical Analysis:**  
   - Perform hypothesis testing to validate relationships between indicators like GDP growth, health expenditure, and life expectancy.
   
4. **Policy Insights:**  
   - Leverage clustering results to draw actionable insights for policy-making, economic development, and investment decisions.

---

## Methodology
1. **Dataset:**  
   - Includes socio-economic indicators such as GDP, birth rate, infant mortality, business tax rates, energy, and more from 208 countries.

2. **Clustering Techniques:**  
   - **K-Means Clustering:** Effective for partitioning datasets with distinct groups.
   - **Hierarchical Clustering:** Useful for visualizing nested groupings and relationships.
   - **DBSCAN:** Robust against outliers and suitable for data with noise.
   - **Spectral Clustering:** Performs well on non-linear relationships in datasets.

3. **Evaluation Metrics:**  
   - Silhouette Score is used to measure clustering performance and identify the best method.

4. **Dimensionality Reduction:**  
   - PCA and t-SNE are applied to visualize high-dimensional data and improve clustering performance.

---

## Results
- **K-Means and Hierarchical Clustering** provided better insights and clustering performance compared to other methods.  
- **Preprocessing steps**, including outlier handling and dimensionality reduction, significantly enhanced clustering outcomes.  
- **Hypothesis testing** revealed critical relationships, such as the correlation between business tax rates and GDP growth, and healthcare spending and life expectancy.

---

## Conclusion
This project demonstrates how clustering techniques and statistical analysis can uncover socio-economic patterns and guide decision-making for sustainable development. The comparisons between clustering methods and preprocessing techniques highlight the importance of selecting the appropriate method based on the dataset.

---

## Requirements
### Tools and Libraries
- Python (>=3.7)
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - scipy

---

## How to Run
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/okesh1215/clustering-global-development.git
Navigate to the Project Directory:
bash
Copy
Edit
cd clustering-global-development
Install Dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run the Analysis:
bash
Copy
Edit
python analysis.py
Author(s)
Okesh Ankireddypalli
Email: bl.en.u4aie22044@bl.students.amrita.edu
Mouhitha A
Email: bl.en.u4aie22075@bl.students.amrita.edu
Saranya Gujjula
Email: bl.en.u4aie22077@bl.students.amrita.edu
Sarada Jayan
Email: j_sarada@blr.amrita.edu
Acknowledgments
This project is part of the academic work at Amrita Vishwa Vidyapeetham, Bengaluru. Special thanks to the Department of Computer Science & Engineering and the Department of Mathematics for their guidance and support.
