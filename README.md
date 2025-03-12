# MSI-LCMS-Correlated-Data-Annotation-and-Analysis-Workflow-Toolkit

## Overview
This Python-based toolkit is designed for annotation, analysis, and visualization of correlated Mass Spectrometry Imaging (MSI) and LC-MS data. It provides an automated annotation workflow, clustering tools, and interactive visualization features to support comprehensive exploration and analysis of datasets.  
*(Note: This toolkit is optimized for MSI data preprocessed using the oycxms project methodology.)*

## Features

### 1. **Interactive Visualization and Clustering**
- Tools for dimensionality reduction and clustering, such as PCA and t-SNE.  
- Spectral visualization options, including:  
  - Mean intensity plots  
  - Cometograms  
  - Extracted Ion Chromatograms (XIC)  
  - Total Ion Chromatograms (TIC)  
- Interactive capabilities to explore datasets in detail.  

### 2. **Semi-Automated Annotation toolkit(SAA toolkit)**
#### **Evidence Considered in Annotation Workflow**:
- MS matching with customizable ppm tolerance.  
- Detection of isotope and adduct patterns.  
- Spatial co-localization.   

#### **Modular Design**:
- Achieving semi-auto MSI annotation 
- Facilitates integration of additional algorithms and evidence types.
- Modular architecture for easy adaptation to new computational methods.

### 3. **Comparison pipeline**
-This script processes amino acid data by reading, normalizing, calculating ratios, and visualizing results.
Functions:
1. read_data(file_path): Reads the input file.
2. normalize_data(df, exclude=[]): Normalizes LC-MS and MSI data.
3. calculate_ratios(df): Computes ratios between pairs of amino acids.
4. compare_values(df, output_file_path): Exports normalized values.
5. plot_results(result_df, output_file): Visualizes LC-MS and MSI ratio comparison.
6. plot_individual(result_df): Visualizes individual LC-MS and MSI correlation.
7. pipeline(input_file, output_file, exclude=[], pairing=True): Main pipeline function.

Usage:
- Adjust input_file and output_file paths.
- Use 'exclude' to filter out specific amino acids.
- Set 'pairing' to True for pairwise ratio analysis or False for individual analysis.

Example:
input_file = r"path/to/input.tsv"
output_file = r"path/to/output.tsv"
pipeline(input_file, output_file, exclude=['Arginine'], pairing=True)   

### 4. **Correlation toolkit**

### **Development**
The toolkit is under active development, with new features and functionalities being added to further enhance its capabilities.
