# Big Data Analysis of Steam Game User Reviews

## Project Description

This project analyses Steam game user reviews using Apache Spark,
PySpark DataFrames and Spark SQL.

The analysis investigates:

- Overall review sentiment
- Sentiment for different games
- Player playtime and sentiment
- Helpful votes and sentiment
- Review languages
- Spark SQL validation
- Spark and Pandas processing performance

## Technologies Used

- Google Colab
- Python
- Apache Spark
- PySpark DataFrames
- Spark SQL
- Pandas
- Matplotlib
- Seaborn

## Source Code

The complete source code is available in this repository:

- `Steam_Review_Analysis.ipynb`

The notebook contains the data-loading, transformation, cleaning,
analysis, visualisation and performance-comparison processes.

## Dataset

Dataset name: Steam Reviews 2021

Dataset source:

https://www.kaggle.com/datasets/najzeko/steam-reviews-2021

The original dataset is not uploaded to this repository because it is
approximately 7–8 GB. It must be downloaded separately from Kaggle.

## Selected Attributes

The analysis uses eight transformed attributes:

1. `review`
2. `sentiment`
3. `app_id`
4. `app_name`
5. `language`
6. `playtime_hours`
7. `review_timestamp`
8. `helpful_votes`

## Instructions to Run the Code

1. Download the dataset from Kaggle.
2. Extract the downloaded dataset.
3. Upload `steam_reviews.csv` to Google Drive.
4. Place it inside the `Colab Notebooks` folder.
5. Open `Steam_Review_Analysis.ipynb` using Google Colab.
6. Mount Google Drive when requested.
7. Confirm that the dataset path is correct.
8. Select `Runtime` and then `Run all`.

The expected dataset path is:

`/content/drive/My Drive/Colab Notebooks/steam_reviews.csv`

If the dataset is stored somewhere else, change the dataset path in the
notebook before running the code.

## Authors

- Shui Zhan Hong (22068597), Ching Cheng Feng (23025653)
- Group 49

## Course Information

Course: IST3134 Big Data Analytics

Assessment: Group Assignment


