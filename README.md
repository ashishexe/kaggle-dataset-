# Bollywood Dataset Analysis

![Bollywood Movies](https://example.com/bollywood-banner.jpg) <!-- Add a relevant banner image if available -->

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Analysis](#analysis)
  - [Data Cleaning](#data-cleaning)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Insights](#insights)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

This repository contains an analysis of the Bollywood dataset sourced from Kaggle. The aim of this project is to explore the dataset and derive meaningful insights about Bollywood movies, such as trends in movie production, box office performance, popular genres, and more.

## Dataset

The dataset used in this project is from Kaggle and contains information about Bollywood movies, including titles, release dates, genres, box office collections, and more.

- **Source:** [Kaggle Bollywood Dataset](https://www.kaggle.com/datasets/saurabhshahane/bollywood-dataset)
- **Features:**
  - Movie Title
  - Release Year
  - Genres
  - Box Office Collections
  - IMDB Ratings
  - Director
  - Cast
  - And more...

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ashishexe/bollywood-dataset-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd bollywood-dataset-analysis
    ```
3. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Analysis

### Data Cleaning

The data cleaning process involved handling missing values, correcting data types, and normalizing data to ensure consistency. The details of this process can be found in the `01-data-cleaning.ipynb` notebook.

### Exploratory Data Analysis (EDA)

EDA was conducted to understand the distribution and relationships within the dataset. Key visualizations were produced to highlight trends and patterns. The EDA process is documented in the `02-eda.ipynb` notebook.

### Insights

Several interesting insights were derived from the dataset, such as:
- Trends in movie production over the years.
- Analysis of box office performance by genre.
- Correlation between IMDB ratings and box office collections.

Detailed insights can be found in the `03-insights.ipynb` notebook.

## Results

The results of the analysis include:
- Cleaned and processed dataset.
- Visualizations showcasing trends and patterns.
- Summarized insights in tabular and graphical formats.

## Conclusion

This analysis provides a comprehensive overview of the Bollywood movie industry based on the available dataset. It highlights key trends and patterns that could be useful for stakeholders in the industry.

## Future Work

Future work could involve:
- Incorporating more recent data to update the analysis.
- Expanding the dataset to include more features, such as critic reviews.
- Applying machine learning models to predict box office performance.

## Acknowledgements

- Kaggle for providing the dataset.
- Any other contributors or sources you want to acknowledge.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
