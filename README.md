# Data Clustering and Analysis - 2024 Internship Coding Challenge 📊

This repository contains my submission for the 2024 Internship Coding Challenge. It consists of a comprehensive Jupyter notebook that explores data clustering techniques and their performance analysis.

## Sections in the Notebook

- **Data Exploration**: Initial examination of the dataset to understand its characteristics and distribution.
- **Clustering Algorithms**: Implementation and comparison of different clustering methods.
- **Performance Analysis**: Evaluation of each algorithm based on the clustering results.
- **Future Scope**: Discussion on potential improvements and future research directions.
- **References**: Citing all the resources and literature used in this analysis.

### Data Exploration 🕵️‍♂️

**Observations**:

- The principal component analysis reveals a significant variance along the first component, suggesting a primary axis of data spread.
- The continuous scatter of data points indicates that traditional clustering might face challenges in distinctly grouping the data.

### Clustering Algorithms 🧮

1. **K-Means**: Determination of the optimal number of clusters using the elbow method.
   ![plot](./plots/kmeans-pca-plot.png)
   
3. **DBSCAN**: Density-based spatial clustering of applications with noise.
   ![plot](./plots/dbscan-pca-plot.png)
   
5. **HDBSCAN**: Hierarchical density-based clustering.
   ![plot](./plots/hdbscan-pca-plot.png)

Each algorithm is briefly described and utilized to find patterns within the data.

### Performance Analysis and Conclusion 🔍

- **K-Means Clustering**: Effective if data structures have compact and distinct groupings.
- **DBSCAN Clustering**: Capable of identifying dense regions and distinguishing outliers, providing insights into the noise within the dataset.
- **HDBSCAN Clustering**: Offers a robust identification of clusters with varying densities, potentially aligning well with complex data distributions.

**Conclusions**:

- HDBSCAN's performance is promising for data with non-spherical clusters or varying densities.
- DBSCAN's distinction between the main cluster and outliers could be crucial if the noise is a significant factor.
- The simplicity of K-Means might be beneficial if the data contains well-separated categories.

### Future Scope 🚀

- **Feature Extraction**: Leverage GPT and BERT for generating deep semantic embeddings to enhance clustering inputs.
- **Parameter Tuning**: Refine DBSCAN and HDBSCAN settings to optimize clustering outputs.
- **Feature Analysis**: Delve into the driving forces behind cluster formations and explore feature engineering opportunities.
- **Dimensionality Reduction**: Investigate alternative methods beyond PCA for revealing data structures.
- **Ensemble Methods**: Combine multiple clustering algorithms for a consensus approach to mitigate individual limitations.
- **Domain-Specific Insights**: Engage with experts to validate and interpret clustering results in the context of domain knowledge.
- **Predictive Modeling**: Utilize clusters as features in predictive models to assess their contribution to model performance.
- **Scalability and Efficiency**: Address the scalability of algorithms for larger datasets and improve computational efficiency.

### Running the Notebook 🏃‍♀️

Please refer to the `readme.txt` file for detailed instructions on running the Jupyter notebook and visualizing the results with Plotly.

