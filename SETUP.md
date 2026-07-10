# AI Coursework Setup Guide

This guide will help you set up the environment required to run the AI coursework notebook (`.ipynb` file).

---

## 📌 Prerequisites

Make sure you have:

- Python 3.10 or later
- Terminal / Command Prompt access
- Internet connection for installing packages

---

## Python Installation

Check if Python is installed:

```bash
python --version
```

You should see something like:

    Python 3.12.13

- If Python is not installed or your version is outdated, download it from:
    https://www.python.org/downloads/

## Required libraries
The following Python libraries are required for this project:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Run the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run this command to confirm everything is installed correctly:

```bash
python -c "import pandas, numpy, seaborn, matplotlib, sklearn; print('All libraries installed successfully!')"
```
    
If everything is installed correctly, you should see:

    All libraries installed successfully!

---

## Download Dataset (UNSW-NB15)

The dataset required for this coursework is hosted on UNSW SharePoint.

Download it from the following link:

https://unsw-my.sharepoint.com/personal/z5025758_ad_unsw_edu_au/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fz5025758%5Fad%5Funsw%5Fedu%5Fau%2FDocuments%2FUNSW%2DNB15%20dataset%2FCSV%20Files%2FTraining%20and%20Testing%20Sets&viewid=f8d1dec5%2Dcd5%2D42ae%2D8b06%2D2fece580c74a

---

### Steps to Download

1. Open the link in your browser .
2. Download the entire folder containing:
   - UNSW_NB15_testing-set.csv
   - UNSW_NB15_training-set.csv

---

### Move Files to Correct Directory

After downloading:

1. Locate the downloaded folder (usually in **Downloads**).
2. Extract 'UNSW_NB15_testing-set.csv' and 'UNSW_NB15_training-set.csv',

then move it to the main project directory into the folder named 'data'.

Your final project structure should look like this:
```text
AI-COURSEWORK/
│
├── notebook.ipynb
├── SETUP.md
├── recording.mp4
└── data/
    ├── UNSW_NB15_testing-set.csv
    └── UNSW_NB15_training-set.csv
```

---

## Running the Notebook

Once everything is set up (Python, libraries, and dataset), you can run the Jupyter Notebook.

---

### Navigate to Project Folder

Open your command line interface and go to the project directory:

```bash
cd path/to/AI-COURSEWORK
```

### Start Jupyter Notebook

Run:
```bash
jupyter notebook
```
This will open a browser window.

### Open the notebook
```bash
jupyter notebook
```

### Alternatively run on google collab
1. Go to https://colab.research.google.com/
2. Click Upload
3. Upload notebook.ipynb
4. Upload the data/ folder
5. Update file paths in the notebook if needed
6. Run all cells