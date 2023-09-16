# Acute Lymphoblastic Leukemia (ALL) Classification with CNN

## Overview

This repository contains the code and resources for a project focused on the classification of Acute Lymphoblastic Leukemia (ALL) using Convolutional Neural Networks (CNNs). ALL is the most common type of childhood cancer, and this project aims to develop a deep learning model that can accurately identify leukemia blasts from normal cells in microscopic images.

### Dataset

The dataset used in this project comprises 15,135 images from 118 patients, with two labeled classes:

1. Normal cell
2. Leukemia blast

The images have been segmented from microscopic images and reflect real-world conditions, including staining noise and illumination errors. Expert oncologists have annotated the ground truth labels for these images.

You can access the dataset on Kaggle [here](https://www.kaggle.com/datasets/andrewmvd/leukemia-classification).

## Project Structure

The repository is organized as follows:

- `data/`: This directory contains the dataset or instructions on how to obtain it.

- `notebooks/`: Jupyter notebooks used for data exploration, model training, and evaluation.

- `src/`: Source code for the CNN model and any related utilities.

- `model/`: Saved model checkpoints and configuration files.

- `results/`: Visualizations, performance metrics, and other project results.

- `requirements.txt`: A list of Python packages required to run the code.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/OumaimaBadi/leukemia-cnn-classification.git
   ```

2. Set up your Python environment with the required packages by running:

   ```bash
   pip install -r requirements.txt
   ```

3. Follow the Jupyter notebooks in the `notebooks/` directory for step-by-step instructions on data preprocessing, model training, and evaluation.

4. To reproduce the results, you can use the provided saved model checkpoints or train your own CNN model.

## Contributions

Contributions to this project are welcome. If you have suggestions, improvements, or would like to report issues, please feel free to open an issue or submit a pull request.

## License

- **Dataset**: The dataset used in this project, sourced from "ALL Challenge dataset of ISBI 2019" on [The Cancer Imaging Archive](https://doi.org/10.7937/tcia.2019.dc64i46r), does not specify a particular license. It is accessible for free and the authors have requested citation upon usage.

- **Code**: The code in this repository is licensed under the MIT License. You are free to use and modify the code for your projects, but if you do use this code, we kindly request that you provide attribution by referencing this GitHub repository or the project it originated from.


## Acknowledgments

### Data Citation

We would like to express our gratitude to the authors Gupta, A., & Gupta, R. for providing the leukemia dataset used in this project. The dataset can be found in the "ALL Challenge dataset of ISBI 2019" available on [The Cancer Imaging Archive](https://doi.org/10.7937/tcia.2019.dc64i46r).

### Publication Citation

- Anubha Gupta, Rahul Duggal, Ritu Gupta, Lalit Kumar, Nisarg Thakkar, and Devprakash Satpathy, “GCTI-SN: Geometry-Inspired Chemical and Tissue Invariant Stain Normalization of Microscopic Medical Images,”, under review.
Ritu Gupta, Pramit Mallick, Rahul Duggal, Anubha Gupta, and Ojaswa Sharma, "Stain Color Normalization and Segmentation of Plasma Cells in Microscopic Images as a Prelude to Development of Computer Assisted Automated Disease Diagnostic Tool in Multiple Myeloma," 16th International Myeloma Workshop (IMW), India, March 2017.

- Rahul Duggal, Anubha Gupta, Ritu Gupta, Manya Wadhwa, and Chirag Ahuja, “Overlapping Cell Nuclei Segmentation in Microscopic Images UsingDeep Belief Networks,” Indian Conference on Computer Vision, Graphics and Image Processing (ICVGIP), India, December 2016.
Rahul Duggal, Anubha Gupta, and Ritu Gupta, “Segmentation of overlapping/touching white blood cell nuclei using artificial neural networks,” CME Series on Hemato-Oncopathology, All India Institute of Medical Sciences (AIIMS), New Delhi, India, July 2016.

- Rahul Duggal, Anubha Gupta, Ritu Gupta, and Pramit Mallick, "SD-Layer: Stain Deconvolutional Layer for CNNs in Medical Microscopic Imaging," In: Descoteaux M., Maier-Hein L., Franz A., Jannin P., Collins D., Duchesne S. (eds) Medical Image Computing and Computer-Assisted Intervention − MICCAI 2017, MICCAI 2017. Lecture Notes in Computer Science, Part III, LNCS 10435, pp. 435–443. Springer, Cham. DOI: https://doi.org/10.1007/978-3-319-66179-7_50 .

## Contact

For questions or further information, please contact [badioumaima11@gmail.com](mailto:your-email@example.com).



