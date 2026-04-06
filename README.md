# Introduction-to-Computer-Vision-Final-Project
# NutriCheck: Computer Vision-Based Nutritional Analysis

**NutriCheck** is an automated system designed to estimate the caloric value of food items through image processing. By leveraging state-of-the-art Deep Learning techniques, the project aims to simplify nutritional tracking and provide users with data-driven dietary insights.


Project Overview
The core objective of this project is to bridge the gap between visual food data and nutritional information using a two-stage computer vision pipeline:

* Object Detection: Identifying multiple food components within a single frame.
* Instance Segmentation: Precisely delineating the boundaries of each item to facilitate volume estimation and improve caloric accuracy.

Datasets
To ensure robust model performance and generalization, we utilize comprehensive open-source datasets (primarily sourced from Kaggle and academic repositories):
* **Nutrition5k:** Selected for its rich metadata regarding ingredient weight and macronutrient distribution.
* **Food-101:** Utilized for broad-spectrum classification of diverse food categories.

Technical Approach
We are currently evaluating high-performance architectures to balance inference speed with segmentation precision. The primary candidates under consideration include:
* **YOLO Series (v8/v10/v11):** For optimized real-time detection performance.
* **Mask R-CNN:** For high-fidelity pixel-level mask generation, essential for complex plate compositions.

> **Status:** We are presently in the benchmarking phase, conducting comparative tests to determine the optimal architecture based on the specific constraints of our datasets.



Research Team
* **Aiym Kairbayeva**
* **Sabina Tolkynbekova**
* **Talgat Tastemir**
* **Balausa Kyzaibayeva**

