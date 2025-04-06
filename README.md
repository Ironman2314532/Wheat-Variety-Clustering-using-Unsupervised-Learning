# Wheat Variety Clustering Using Unsupervised Learning

This project focuses on clustering different wheat varieties using unsupervised learning techniques. By applying Principal Component Analysis (PCA) for dimensionality reduction and K-Means clustering, we aim to group wheat varieties based on their inherent similarities.

## Project Overview

Understanding the relationships among wheat varieties is crucial for agricultural planning and crop improvement. In this project, we utilize the [seeds dataset](https://doi.org/10.24432/C5H30K) from the UCI Machine Learning Repository, which contains measurements of geometrical properties of kernels belonging to three wheat varieties: Kama, Rosa, and Canadian. The dataset comprises 210 samples, with 70 samples per variety.

The analysis involves:

1. **Dimensionality Reduction**: Using PCA to simplify the dataset while retaining key features, facilitating more effective clustering.
2. **Clustering**: Applying K-Means clustering to group the wheat varieties based on their characteristics.

This approach provides valuable insights into the relationships and distinctions among wheat varieties, demonstrating the effectiveness of combining PCA and K-Means for agricultural data clustering and interpretation.

## Dataset

The dataset used in this project is sourced from:

Charytanowicz, M., Niewczas, J., Kulczycki, P., Kowalski, P., & Lukasik, S. (2012). Seeds. UCI Machine Learning Repository. [https://doi.org/10.24432/C5H30K](https://doi.org/10.24432/C5H30K)

It includes seven real-valued attributes:

1. Area
2. Perimeter
3. Compactness
4. Length of kernel
5. Width of kernel
6. Asymmetry coefficient
7. Length of kernel groove

## Repository Contents

- `seeds_dataset.txt`: The dataset file containing measurements of wheat kernels.
- `seeds_type_clustering.ipynb`: Jupyter Notebook with the implementation of PCA and K-Means clustering on the dataset.

## Getting Started

To explore this project:

1. **Download the Dataset**: Obtain the `seeds_dataset.txt` file from the repository.
2. **Open the Notebook**: Access the `seeds_type_clustering.ipynb` file in Jupyter Notebook or Google Colab.
3. **Upload the Dataset**: In your notebook environment, upload the `seeds_dataset.txt` file.
4. **Run the Analysis**: Execute the cells in the notebook to perform PCA and K-Means clustering on the dataset.

## Results

The clustering analysis reveals distinct groupings among the wheat varieties, aligning with their known classifications. Visualizations included in the notebook illustrate how PCA effectively reduces dimensionality, and how K-Means clustering accurately groups the varieties based on kernel measurements.

## Contributing

Pull requests are welcome.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments
Special thanks to the UCI Machine Learning Repository for providing the seeds dataset, which has been instrumental in this analysis.
