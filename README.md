Computer Vision-Based Air Quality Analysis

This project presents a novel approach to estimate air pollution levels by analyzing environmental images using computer vision techniques.

Project Overview:

Using Python, OpenCV, and cloud tools like Google Drive, the system extracts visual features from images—such as contrast, brightness, edge density, color saturation, and blue channel intensity—to determine pollution levels and classify air quality into categories like Excellent, Good, Moderate, and Poor.

Tech Stack:

Python

OpenCV

Google Colab + Google Drive

Matplotlib & Seaborn

Pandas

Methodology:

Image Collection: Environmental images (clear and polluted) uploaded to Google Drive.

Feature Extraction: Using OpenCV to calculate:

Brightness

Contrast

Edge Density (Canny Detection)

Blue Channel Intensity

HSV Saturation

Scoring: Weighted rule-based algorithm generates a pollution score (0–100).

Classification:

0–25: Excellent

26–49: Good

50–74: Moderate

75–100: Poor

Visualization: Pollution scores plotted using Seaborn; edge-detection results are also displayed.

Example Results:

Clear Sky: High blue intensity, high contrast, sharp edges → Low pollution score.

Polluted Air: Dull colors, low contrast, low edge density → High pollution score.

Files Included:

computervisioncode.ipynb – Colab notebook with full code

computervisionreport.docx – Detailed project documentation

clearSKY.jpeg, polluted.jpeg, pollutionIMG.png – Sample input images

pollution_results.csv – Output file containing calculated visual features and pollution scores for each image. This file can be used for analysis, validation, or integration with external dashboards.


