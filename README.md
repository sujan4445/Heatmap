Heatmap Visualization of Stress Tolerance Index (STI)

This script is designed to create a high-resolution heatmap that visualizes the Stress Tolerance Index (STI) values for different genotypes under various traits or conditions. The heatmap provides a clear and interpretable way to examine the relative performance of genotypes, facilitating comparison and clustering based on STI profiles.
Purpose
The primary goal of this script is to generate a heatmap that clusters genotypes based on their STI values. This visual representation helps researchers identify patterns of tolerance or sensitivity among genotypes under stress conditions.
Input
The script takes a dataset containing STI values for various genotypes. The dataset must include a column for genotype names and multiple columns for STI values across different traits or experimental conditions.
Process
1. Genotype names are used as row labels in the heatmap.
2. The STI values are organized into a matrix format suitable for clustering and visualization.
3. Hierarchical clustering is performed on the genotypes (rows) using Euclidean distance and complete linkage method to identify similarity patterns.
4. Columns (traits or conditions) are not clustered, allowing easy comparison across consistent categories.
5. he final heatmap is styled with readable font sizes, appropriate row heights, and Times font for clarity and presentation.
Output
The heatmap is exported as a high-resolution TIFF image, ensuring suitability for publication or detailed analysis. The image file is saved under the name `STI_heatmap111.tiff`.

