# Spotify Data Analysis using PySpark

This project analyzes a Spotify tracks dataset using PySpark and Python. It includes exploratory data analysis, correlation analysis, predictive modeling, and natural language processing on track names.

## Project Files
- `Spotify_Data_Science_Project.ipynb`: Main analysis notebook.
- `DSCI5350 Data Wizards Presentation (2).pptx`: Project presentation.
- `Spotify Project.docx`: Project report.

## Dataset
Source: https://huggingface.co/datasets/maharshipandya/spotify-tracks-dataset

The notebook currently loads data from a local CSV path. Update the path in the notebook to your local dataset location.

## Analysis Summary
- EDA on top artists and top genres by popularity.
- Correlation analysis across audio features.
- Random Forest regression to predict `energy` from audio features.
- NLP on track names: keyword frequencies and word cloud.
- Sentiment analysis on track names using a Transformers model.

## Requirements
Typical Python packages used in the notebook:
- pyspark
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- wordcloud
- transformers
- torch

## How to Run
1. Open `Spotify_Data_Science_Project.ipynb` in Jupyter or Google Colab.
2. Set the dataset CSV path to your local file.
3. Run cells in order.

## Results Highlights
- Top artist and genre by popularity are reported in the notebook and presentation.
- Random Forest model achieves strong R^2 for energy prediction.
- NLP reveals common themes in track names; sentiment shows mixed tone.
