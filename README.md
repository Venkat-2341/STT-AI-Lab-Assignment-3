# Lab Assignment 3

## Overview
This assignment focuses on annotating NLP and Computer Vision (CV) datasets, evaluating inter-annotator agreement using statistical measures, and performing classification tasks.

## Project Structure
```
LAB ASSIGNMENT 3
│-- CV-annotations
│   │-- CV-annotations-3rd-member.csv
│   │-- CV-annotations-Arjun.csv
│   │-- CV-annotations-Venkat.csv
│-- imgs
│-- NLP-annotations
│   │-- NLP_POS_sentences.csv
│   │-- NLP-annotations-Arjun.csv
│   │-- NLP-annotations-Venkat.csv
│-- annotating-images.png
│-- annotating-text.png
│-- question3-cv.ipynb
│-- question3-nlp.ipynb
```

- **CV-annotations/**: Contains annotation CSV files for the Computer Vision task.
- **imgs/**: Contains 20 images used for the truck/no-truck classification task.
- **NLP-annotations/**: Contains annotation CSV files for the NLP task.
- **annotating-images.png / annotating-text.png**: Sample images showing annotations using Label Studio.
- **question3-cv.ipynb / question3-nlp.ipynb**: Jupyter notebooks for analysis and evaluation.

## Annotation Process

### NLP Task
1. We annotated 20 data points from the NLP dataset.
2. We used the following POS tags for annotation:
    - "NOUN", "PROPN", "VERB", "ADJ", "ADV", "ADP", "PRON", "DET", "CONJ", "PART", "PRON_WH", "PART_NEG", "NUM", "X"
3. POS tagging was performed using guidelines provided in the assignment.

### CV Task
1. We annotated 20 images for the presence of trucks.
2. Labels used:
    - "truck", "not_truck"
3. Classification tasks were performed to distinguish between images containing trucks or not.

## Inter-Annotator Agreement

### NLP Task
- **Cohen's Kappa** was used to measure agreement between two annotators.
- Annotations were exported in CSV format for calculation.

### CV Task
- **Fleiss' Kappa** was used to measure agreement among three annotators (Venkat, Arjun, and Srivats).
- The third annotation was obtained from another team to compute the metric.

## Results and Interpretation
- **Cohen's Kappa Score (NLP)**: 0.8011, indicating *very good agreement*.
- **Fleiss' Kappa Score (CV)**: 0.7222, indicating *substantial agreement*.

## Tools Used
- **Annotation Tool**: Label Studio (as shown in the sample images provided)
- **Programming Language**: Python
- **Libraries**: pandas, sklearn, statsmodels

## Outputs
- Annotated data exported in CSV format.
- Agreement scores calculated and interpreted.

## Instructions to Run
1. Open the Jupyter notebooks `question3-cv.ipynb` and `question3-nlp.ipynb`.
2. Run the code cells to calculate the inter-annotator agreement metrics.
3. Review the output agreement scores and their significance.

---
