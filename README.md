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

### 2. **Semi-Automated Annotation**
#### **Evidence Considered in Annotation Workflow**:
- MS matching with customizable ppm tolerance.  
- Detection of isotope and adduct patterns.  
- Spatial distribution analysis of ions.  
- Evidence-based correlation between MSI and LC-MS datasets.  

#### **Modular Design**:
- The annotation workflow operates as a complete pipeline or as 8 independent functions.  
- Facilitates integration of additional algorithms and evidence types.  

### 3. **Extensibility and Customization**
- Modular architecture for easy adaptation to new computational methods.  
- Open for integration with domain-specific workflows or advanced algorithms.  

### **Development**
The toolkit is under active development, with new features and functionalities being added to further enhance its capabilities.
