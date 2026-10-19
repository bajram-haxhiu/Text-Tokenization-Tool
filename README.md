# Text Tokenization Tool

A Python-based project that compares different text tokenization methods using `split()`, NLTK, and spaCy.

## Project Overview

This project explores how different tokenization methods process text and how their results vary depending on contractions, numbers, dates, punctuation, email addresses, and URLs.

It also includes word frequency analysis and data visualization.

## Features

- Text tokenization using `split()`, NLTK, and spaCy
- Comparison of token counts across different text categories
- Analysis of user-provided text
- Word frequency analysis
- Data visualization using Matplotlib
- Export of tokenization results to CSV
- Export of word frequency results to CSV

## Technologies Used

- Python
- Jupyter Notebook
- NLTK
- spaCy
- Pandas
- Matplotlib

## Project Structure

```text
Text-Tokenization-Tool/
├── tokenization_analysis.ipynb
├── tokenization_comparison.csv
├── word_frequency.csv
├── requirements.txt
└── README.md
```

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/Text-Tokenization-Tool.git
   ```

2. Navigate to the project folder:

   ```bash
   cd Text-Tokenization-Tool
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `tokenization_analysis.ipynb` and run the cells.

## Output Files

- `tokenization_comparison.csv`: Contains the comparison of token counts produced by the three tokenization methods.
- `word_frequency.csv`: Contains word frequency analysis results.

## Learning Objectives

- Understanding text tokenization
- Comparing NLP libraries
- Working with Python data structures and Pandas
- Visualizing data
- Exporting analysis results to CSV

## Future Improvements

- Support for additional languages
- Stop-word removal
- Lemmatization and stemming
- Interactive web interface for text analysis

