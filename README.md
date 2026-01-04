Task 2 – Sports Article Classification Prototype
================================================

Repository structure:
.
├── Task2.ipynb   # Jupyter Notebook with text classification pipeline
├── Task2.html    # Static HTML export of the notebook
└── README.md     # Project documentation


Description:
This repository contains a prototype solution for Task 2 focused on
automatic classification of sports-related articles into predefined categories.

The task addresses supervised text classification using traditional
machine learning techniques with an emphasis on interpretability,
reproducibility, and controlled experimentation.


Problem scope:
- Input: short sports articles / reports
- Output: single-label category assignment
- Classes include match reports, reactions, interviews, previews, transfers, etc.
- No external APIs or pretrained large language models are used


Solution approach:
- Text preprocessing (cleaning, normalization)
- Feature extraction using vectorization techniques
- Supervised classification using classical ML models
- Evaluation with standard classification metrics


Repository usage:

Option 1 – Jupyter Notebook
$ jupyter notebook Task2.ipynb

Option 2 – HTML preview
Open Task2.html directly in a web browser (read-only preview).


Key characteristics:
- Fully reproducible training and evaluation pipeline
- No dependency on external services or online resources
- Transparent feature-based classification
- Metrics-driven evaluation (accuracy, precision, recall, F1-score)


Evaluation:
- Separate train and test splits
- Per-class performance analysis
- Macro and weighted averages reported
- Class imbalance explicitly considered


Limitations:
- Performance depends on feature engineering quality
- Limited semantic understanding compared to LLM-based approaches
- Fixed label taxonomy requires manual maintenance


Possible extensions:
- Hierarchical or multi-label classification
- Combination with neural or embedding-based models
- Data augmentation for minority classes
- End-to-end integration with text generation (Task 1)


Author:
Kristián Marcinčák

This repository was created as part of a technical assignment and serves
as a prototype for experimental and educational purposes.
