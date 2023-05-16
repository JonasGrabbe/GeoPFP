
# Protein Function Prediction with Geometric Deep Learning


![Jonas_Grabbe_MINIMALITSTIC_This_repository_WILL_contains_the_im_805beb60-a212-487f-a9bf-ac4c073b1496](https://github.com/JonasGrabbe/GeoPFP/assets/77153915/7bb5f75b-058e-468f-8d5d-3f9f8db9cf89)


This repository (WILL) contains the implementation of a protein function prediction model, which harnesses the power of geometric deep learning (GeoDL) to predict protein functions. The project aims to address the protein function prediction problem by using GeoDL to leverage the amino-acid sequences of proteins and other data. This approach is designed to enhance our understanding of protein functions, which could potentially lead to advances in drug discovery and the treatment of various diseases.

### Table of Contents
- [x] Background
- [x] Geometric Deep Learning
- [x] Current State of Protein Function Prediction
- [ ] Approach

Proteins, composed of 20 types of building blocks known as amino acids, are responsible for a plethora of activities in our tissues, organs, and bodies. The sequence of amino acids determines the 3D structure and dynamics of the protein, which in turn defines its biological function. In the current era of genome sequencing, we are inundated with large amounts of genomic sequence data, which informs us of the amino-acid sequence data of proteins. However, assigning function to a specific protein can be challenging due to their multifunctional nature and the ability to interact with multiple partners. Thus, effective protein function prediction is key to understanding life at the molecular level and potentially curing diseases.

### Geometric Deep Learning
Geometric Deep Learning is a branch of machine learning that focuses on learning from data that is not structured as grids. Unlike traditional machine learning, which operates on unstructured vectors, GeoDL acknowledges the inherent mathematical properties of data [Bronstein et al., 2017, 2021]. This is especially true for structured objects, such as proteins, which have paramount importance for our structural biology applications.

GeoDL has been successfully applied to various areas of biology, including protein functions and drug discovery, providing significant improvements over standard methods. It leverages mathematical structures in machine learning methods, such as group symmetries of the data and distance between points that is not the Euclidean distance, to predict molecular properties, ligand binding sites, and design de novo molecules.

### Current State of Protein Function Prediction
Despite the significant strides made in the field of protein function prediction, there is still room for improvement. Current methods such as BLAST, SVM, PNN, KNN, ProtCNN, and BiLSTM have shown varying degrees of accuracy [1, 2, 3]. However, these methods have yet to be thoroughly evaluated and optimized, leading to limitations in their usage.

### Approach
The approach harnesses the power of geometric deep learning to predict protein functions. By leveraging the 3D structure of proteins, we aim to improve the accuracy of protein function prediction. GeoDL models such as ScanNet and PersGNN have shown promise in predicting protein binding sites and protein-protein interactions based on protein 3D structures.

The work aims to build upon these foundations, incorporating advanced techniques such as graph representation learning and topological data analysis to capture a complex set of both local and global structural features. Our end goal is to develop an end-to-end trainable deep learning model that can accurately predict protein functions using only the structural information of a protein.
