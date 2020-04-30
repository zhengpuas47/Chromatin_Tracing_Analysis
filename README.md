# Chromatin_Tracing_Analysis
Repository for codes analyzing sequential and combinatorial choromatin imaging data

This repository contains two main sections, as following:

1. Combinatorial_tracing - contains all code and examples relevant to combinatorial genome-wide chromatin imaging. Code is separated into the following categories, each contained in an individual sub-folder. Each of these sub-fodlers contains a "functions" folder, in which all functions and classses are defined in .py files. In addition, it contains Jupyter notebook (.ipynb) files, in which examples of scripts running the functions on data are given:
   a. BarcodeGeneration - contains the code and examples for generating barcodes and assigning them to genomic loci of interest
   b. ImageAnalysis - contains all code and examples used from the point at which raw microscopy images are obtained, until a set of detected loci and their coordinates (as well as transcriptional state and location of nuclear bodies, if relevant) is calculated
   c. PostAnalysis - contains all functions and examples scripts used to generate the figures in the paper from imaging data (after conversion to a list of localizations for all detected loci, as outlined in ImageAnalysis). This section also contains a Data sub-folder, in which the actual positions, transcriptional states and distances from nuclear bodies measured in the experiments reported in this study are made available
   
2. Sequential_tracing - contains all code and examples relevant to sequential, chromosome-wide chromatin imaging. This section contains a source sub-folder, in which all function and class-containing .py files are organized. The ImageAnalysis fodler contains a Jupyter notebook (.ipynb) file with example scripts, showing how to run the functions on data. The Data sub-folder contains the actual positions, transcriptional states and distances from nuclear bodies measured in the experiments reported in this study

by Pu Zheng, Seon Kinrot and Bogdan Bintu

Feb.18, 2020
