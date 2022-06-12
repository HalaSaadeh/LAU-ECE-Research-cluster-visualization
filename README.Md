# LAU ECE Research: Cluster Visualization
Source code implementation for the visualization component of the "Hierarchical Indexing for Interactive Zooming of Document Clusters" research study.  
This study was performed at the Lebanese American University in the Electrical and Computer Engineering (ECE) department. 

## Description
### Overall System Architecture
The overall architecture of the system can be found below:  
![alt text](https://github.com/HalaSaadeh/LAU-ECE-Research-cluster-visualization/blob/main/readme_images/overall_architecture.png "Overall Architecture")

This repository contains the source code for the *Visualization (online) component.*
The repository for the **Indexing component** can be found here: [LAU-ECE-Research-cluster-indexing](https://github.com/HalaSaadeh/LAU-ECE-Research-cluster-indexing) 
## Visualization Component
This code contains the **Visualization Component** of the project. This component receives the index structure produced by the Indexing component as input and produces an interactive cluster visualization that includes cluster exploration and interactive zooming.  

## Experimental Results
### Performance Evaluation
Performance experiments were conducted to measure the following metrics: 
- Cluster visualization time: the time needed to load the interface and document clusters, while varying the size of the input index.
- Cluster zooming time: the time needed to perform the zooming action and load the zoomed cluster visualizations, while varying the size of the index.

Experimental results can be found in **Visualization_results.xlsx**.  
### Qualitative Evaluation
A qualitative survey was sent out to 10 senior engineering students at the Lebanese American University to evaluate the quality of the solution.  
The survey results can be found in **Survey_results.xlsx**

## Repository Structure  
The repository is structured as follows:  
- **readme_images**: source images for this README document
- **src**: implementation source code
- **Visualization_results.xlsx**: Experimental results and charts
- **Survey_results.xlsx**: Experimental results and charts

## Example
An example visualization can be found below. This example is based on the example found in [LAU-ECE-Research-cluster-indexing](https://github.com/HalaSaadeh/LAU-ECE-Research-cluster-indexing) based on 10 documents.  
Using the index produced in the indexing component, the following two visualizations are produced.
### Treemap
The treemap is interactive and zoomable and allows cluster exploration. Below are 3 example stages (root level, level 2, and the deepest level)
![alt text](https://github.com/HalaSaadeh/LAU-ECE-Research-cluster-visualization/blob/main/readme_images/treemap.png "Treemap")
### Circlepacking
The circlepacking visualization is interactive and zoomable and allows cluster exploration. Below are 3 example stages (root level, level 2, and the deepest level)
![alt text](https://github.com/HalaSaadeh/LAU-ECE-Research-cluster-visualization/blob/main/readme_images/circlepacking.png "Circlepacking")
