# E-Commerce Public Data Analysis with Python - Dicoding  [![E-Commerce Data Dashboard]](link-to-your-dashboard-image)

## Table of Contents

*   [Overview](#overview)
*   [Project Structure](#project-structure)
*   [Installation](#installation)
*   [Usage](#usage)
*   [Data Sources](#data-sources)

## Overview <a name="overview"></a>

This project focuses on data analysis and visualization of public e-commerce data.  It includes code for data wrangling, exploratory data analysis (EDA), and a Streamlit dashboard for interactive exploration. The primary goal is to analyze the E-Commerce Public Dataset.

## Project Structure <a name="project-structure"></a>
data-analyst-dicoding/
├── dashboard/
│   └── Dashboard.py  # Streamlit dashboard
├── data/
│   └── *.csv           # Raw CSV data files
├── NotebookFinal.ipynb     # Data analysis notebook (English)
└── README.md          # This documentation
## Installation <a name="installation"></a>

1.  Clone the repository:

    ```bash
    git clone [https://github.com/mhdhfzz/data-analyst-dicoding.git](https://github.com/mhdhfzz/data-analyst-dicoding.git)
    ```

2.  Navigate to the project directory:

    ```bash
    cd data-analyst-dicoding
    ```

3.  Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage <a name="usage"></a>

1.  **Data Wrangling:**  Scripts for data preparation and cleaning are located in `notebook.ipynb`.

2.  **Exploratory Data Analysis (EDA):**  Conduct data exploration and analysis using the Python scripts provided.  The EDA insights will help you understand e-commerce data patterns.

3.  **Visualization:**  Launch the Streamlit dashboard for interactive data exploration:

    ```bash
    cd data-analyst-dicoding/dashboard
    streamlit run dashboard.py
    ```

    Access the dashboard in your web browser at `http://localhost:8501`.

## Data Sources <a name="data-sources"></a>

This project utilizes the E-Commerce Public Dataset from [Belajar Analisis Data dengan Python's Final Project](https://drive.google.com/file/d/1MsAjPM7oKtVfJL_wRp1qmCajtSG1mdcK/view), provided by [Dicoding](https://www.dicoding.com/).
