# CNN Cancer Detection Kaggle Mini-Project

#### CSCA 5642 Introduction to Deep Learning

## Project Summary

The objective of this competition is to detect the presence of metastatic cancer in small image patches taken from larger digital pathology scans. This is a critical problem in medical diagnostics, as early detection of cancer can significantly improve treatment outcomes.

This project is a Week 3 assignment for my Introduction to Deep Learning course. The notebook includes rubric requirements for each step.

## Data Source

The data is gathered from [Histopathologic Cancer Detection](https://www.kaggle.com/c/histopathologic-cancer-detection/data).

The dataset includes training and test sets. The training data consists of 220,025 images, each sized 96x96 pixels, accompanied by corresponding labels: '0' for no cancer and '1' for cancer. These images are extracted from larger whole slide images and are stored in TIFF format. The test data comprises a set of images without labels, which will be used to evaluate the model's performance. The images are small patches of tissue, with each patch representing a different region of a slide, making the dataset diverse in terms of tissue structures and staining variations.

For more details, please refer to notebook in this repository.