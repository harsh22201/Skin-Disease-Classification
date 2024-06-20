# Skin Disease Classification

### Team

-   Harsh Rajput - 2022201
-   Tejash Prasad - 2022539

## Introduction

The following repository is our SML winter project which aims to utilize machine learning techniques that classify dermoscopic images into distinct diagnostic categories. By harnessing advanced algorithms and a wealth of data, we seek to develop a reliable classification system.

## Problem statement and Motivation

The incidence of skin cancers has been on the rise globally over the past few decades. Among them, melanoma stands out as one of the deadliest types. It is projected that melanoma-related deaths will rise by 3.8 percent in 2024. Despite its severity, early detection significantly increases the chances of successful treatment.

Dermatologists have the potential to improve diagnostic precision by integrating contextual images from the same patient into detection algorithms. This approach could facilitate distinguishing between different types of skin lesions more accurately. Successful implementation of such classifiers could greatly enhance the efficiency of dermatological clinic procedures.

## Dataset

The HAM10000 dataset comprises a comprehensive collection of dermatoscopic images featuring common pigmented skin lesions from various sources. This dataset encompasses 10,015 images and serves as an resource for academic machine learning, particularly for training purposes. It covers a wide spectrum of important diagnostic categories within pigmented lesions, including Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec), basal cell carcinoma (bcc), benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl), dermatofibroma (df), melanoma (mel), melanocytic nevi (nv), and vascular lesions (angiomas, angiokeratomas, pyogenic granulomas, and hemorrhage, vasc).

## Method

-   **Lesion Dermoscopic Feature Segmentation** - Delineate and Isolate specific features within dermatoscopic images for detailed analysis.
-   **Lesion Dermoscopic Feature Extraction** - Extracts relevant features from Lesion area
-   **Lesion Classification** - Classifies skin lesions into different diagnostic categories based on extracted features
