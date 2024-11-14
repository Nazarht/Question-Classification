# 📝 Question Similarity Detection

This project explores various approaches to identifying whether two given questions are similar or different. By experimenting with multiple methods, ranging from simple vector comparisons to advanced deep learning techniques, we aim to find an effective solution for question similarity detection.

## 🚀 Project Overview

The project covers the following approaches:

1. **Simple Similarity Check**  
   Uses sentence vectors and Cosine Similarity to determine if two questions are similar or different. This method serves as a quick, baseline approach.

2. **XGBoost Model**  
   Applies a gradient boosting model to analyze relationships between question vectors, effectively capturing non-linear patterns for better classification.

3. **BERT Fine-Tuning**  
   Leverages the BERT model to capture deeper semantic relationships between questions. Fine-tuning BERT helps achieve higher accuracy by understanding the context and nuances in language.

## 📁 Project Structure

```
├── Final_ML.ipynb                      # Jupyter Notebook with all approaches
├── data/                               # Folder for any datasets (optional)
└── README.md                           # Project documentation
```

## 🛠️ Getting Started

### Prerequisites

Make sure you have Python and Jupyter Notebook installed. You will also need some additional Python libraries. You can install the necessary dependencies using:

```bash
pip install transformers datasets torch scikit-learn tqdm sentence-transformers
```

### Running the Notebook

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd question-similarity-detection
    ```

2. Open the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

3. Run the cells in `Final_ML.ipynb` to see the different approaches in action.

## 📊 Results

- The **Simple Similarity Check** provides a fast but basic solution.
- The **XGBoost Model** improves accuracy by capturing complex patterns.
- **BERT Fine-Tuning** offers the best performance by leveraging contextual understanding.
