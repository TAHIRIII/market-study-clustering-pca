# 🌍 Market Study — Country Segmentation for Chicken Export

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 🎯 Objective

An agri-food company specializing in chicken products wants to expand internationally. The goal of this study is to **identify the most promising target countries** for export by grouping them into meaningful clusters based on food consumption and demographic data.

---

## 🔬 Methodology

### Data (Source: FAO)
Each country is characterized by 4 variables:
- Population growth rate (2008 → 2018)
- - Proportion of animal proteins in total protein supply
  - - Food availability in proteins per capita (g/day)
    - - Food availability in calories per capita (kcal/day)
     
      - ### Steps
      - 1. **Data cleaning & preparation** — merging 5 FAO datasets, removing duplicates (Chinese provinces)
        2. 2. **Hierarchical Clustering** — dendrogram with Ward linkage, cut at 5 clusters
           3. 3. **K-Means** — validation and refinement of clusters
              4. 4. **PCA** — visualization of partitions in the first factorial plane
                 5. 5. **Statistical tests** — normality test (Shapiro-Wilk) + comparison test between 2 clusters (Student's t-test)
                    6. 6. **Centroid analysis** — characterization of each cluster and identification of target countries
                      
                       7. ---
                      
                       8. ## 📁 Files
                      
                       9. | File | Description |
                       10. |------|-------------|
                       11. | `P5_Code_Houssain_TAHIRI.ipynb` | Full analysis notebook |
                       12. | `P5_cluster_final.csv` | Final cluster assignments per country |
                       13. | `P5_groupes_centroides.csv` | Centroid positions for each cluster |
                       14. | `P5_dendrogramme_5_clusters.png` | Dendrogram — version 1 |
                       15. | `P5_dendrogramme_5_clustersv2.png` | Dendrogram — version 2 |
                      
                       16. ---
                      
                       17. ## 🛠️ Tools & Libraries
                      
                       18. `Python` · `Pandas` · `NumPy` · `Scikit-learn` · `Scipy` · `Matplotlib` · `Seaborn`
                      
                       19. ---
                      
                       20. ## 👤 Author
                      
                       21. **Houssain TAHIRI** — Data Analyst
                       22. [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/houssain-tahiri-246b00100/)
