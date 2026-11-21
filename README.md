# Certification Task

A data analytics project using Netflix title data to explore content distribution, growth patterns, countries, genres, ratings, durations, and release trends.

## Project Overview

This project covers the complete data-analysis workflow:

- Importing and exploring the raw dataset
- Handling missing values and duplicate records
- Cleaning and transforming columns
- Detecting and reviewing duration outliers
- Engineering date and decade features
- Performing exploratory data analysis (EDA)
- Creating visualizations for business questions (in Certification_Task.ipynb file )
- Documenting findings and key insights

## Dataset

The repository contains:

- `Dataset/Raw/NetFlix.csv` — original Netflix dataset
- `Dataset/Cleaned/Netflix_Cleaned.csv` — cleaned and transformed dataset

The cleaned dataset contains 17 columns, including engineered fields for movie duration, TV-show seasons, content addition year and month, and release decade.

## Repository Structure

```text
Certification-task/
├── Dataset/
│   ├── Raw/
│   │   └── NetFlix.csv
│   └── Cleaned/
│       └── Netflix_Cleaned.csv
├── Docx/
│   └── Project documentation.pdf
├── NoteBook/
  └── Certification_Task.ipynb

```

- **NoteBook/** contains the complete Jupyter/Google Colab analysis.
- **Dataset/** contains the raw and cleaned data.
- **Docx/** contains the project documentation PDF.
- **Visualization/** is reserved for exported charts and visual assets.

## Analysis Areas

The notebook analyzes:

- Movies versus TV shows
- Content growth over time
- Country and genre distribution
- Audience ratings
- Movie durations
- TV-show season counts
- Release years and decades
- Monthly content additions
- Relationships between content type and rating
- Correlations among available numerical features

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Kaini9/Certification-task.git
cd Certification-task
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook NoteBook/Certification_Task.ipynb
```

Update the dataset path in the notebook if needed. To use the included data locally, read:

```python
import pandas as pd

df = pd.read_csv("Dataset/Raw/NetFlix.csv")
```

The notebook can also be opened directly in Google Colab using the badge included at the top of `Certification_Task.ipynb`.

## Documentation

Detailed project documentation is available in [`Docx/Project documentation.pdf`](Docx/Project%20documentation.pdf).

## Author

**Saval Kaini**
