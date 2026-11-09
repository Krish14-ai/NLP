# NLP Practice Repository

This repository is a collection of hands-on Natural Language Processing (NLP) projects focused on text preprocessing, feature extraction, and machine learning classification tasks. It is designed for practice, experimentation, and learning core NLP techniques using Python and Jupyter notebooks.

## Project Overview

The workspace contains multiple mini-projects that cover common NLP workflows such as:

- Text cleaning and preprocessing
- Tokenization and vectorization
- Bag-of-Words and N-grams
- Sentiment and topic classification
- Spam detection
- Resume classification

## Included Projects

### 1. Bag_of_Words
Contains notebooks for exploring Bag-of-Words and N-gram based text representation techniques.

### 2. Imbd classification
Focuses on IMDb review classification using preprocessing and a machine learning model pipeline.

### 3. News Article Classification
Uses a news dataset to classify articles into categories such as business, entertainment, sports, and technology.

### 4. Resume Classifier
Classifies resumes into categories using a text-based dataset and NLP preprocessing methods.

### 5. Spam Detection
Builds a SMS spam detection model to distinguish spam and legitimate messages.

## Repository Structure

```text
NLP Practice/
├── README.md
├── NLP-/
│   ├── Bag_of_Words/
│   ├── Imbd classification/
│   ├── News Article Classification/
│   ├── Resume Classifier/
│   └── Spam Detection/
└── .venv/
```

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib / Seaborn

## Getting Started

1. Clone the repository:

```bash
git clone <repository-url>
cd "NLP Practice"
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
```

3. Install the required dependencies:

```bash
pip install jupyter pandas numpy scikit-learn nltk matplotlib seaborn
```

4. Open the notebooks in Jupyter or VS Code and run the cells.

## Usage

Each project folder contains its own dataset and notebook. Open the relevant notebook and follow the workflow:

- Load the dataset
- Clean and preprocess text
- Split data into train/test sets
- Transform text into features
- Train a classifier
- Evaluate the model

## Notes

This repository is intended as a practical learning workspace for NLP fundamentals and beginner-level text classification experiments. It is ideal for improving skills in data preprocessing, machine learning pipelines, and model evaluation.

## License

This project is for educational and personal learning purposes.
