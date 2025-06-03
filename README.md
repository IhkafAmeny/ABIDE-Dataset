## **Autism Brain Imaging Data Exchange Downloader and Preprocessor (CPAC Pipeline)**

This project provides a Python script designed to run in **Google Colab**, enabling:

- Automatic download of a subset of 250 subjects from the **ABIDE** dataset using the **CPAC** pipeline.
- Extraction of preprocessed functional MRI images (`func_preproc`).
- Creation of a clean CSV file containing key phenotypic information (diagnosis, sex, age, site).
- Compression of the images and CSV into a `.zip` file for easy download.



## Features

-  Automated download using **Nilearn**.
-  CSV generation for subject-level metadata.
-  Compression of images + metadata into a single archive.
-  Download-ready from the Colab environment.

## References
- [ABIDE Preprocessed Project](http://preprocessed-connectomes-project.org/abide/)
- [Nilearn – fetch_abide_pcp Documentation](https://nilearn.github.io/stable/modules/generated/nilearn.datasets.fetch_abide_pcp.html)

## About
This script was developed as part of a research project on brain MRI analysis, focusing on autism spectrum disorder detection using neuroimaging data.
