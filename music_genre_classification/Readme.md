# Music Genre Classification with PCA

## Project Overview

In the era of digital streaming, there’s an increasing need to categorize and recommend music based on genres. By analyzing various musical features extracted from tracks, we can delve deeper into their defining patterns. This music genre classification project aims to predict the genres of music tracks that have missing genre information.

The dataset contains various musical features extracted from tracks across different styles. The key challenge is that a significant portion of the records lacks specific genre information, which we need to predict using machine learning techniques.

## Objective

The primary goal of this project is to predict the genres of the unlabeled tracks in the dataset. We will:

1. **Perform Principal Component Analysis (PCA)**: Reduce the dimensionality of the dataset by transforming the features into principal components, making the data more manageable and revealing patterns that are not immediately obvious.
  
2. **Apply Logistic Regression**: Use PCA-transformed features as input to train a logistic regression model, a well-known supervised machine learning algorithm, to predict music genres.

## Why Principal Component Analysis (PCA)?

Music tracks are complex with numerous inherent features, some of which may be correlated. For example, specific rhythm patterns might be prevalent in rock and blues music. PCA helps in reducing redundancy by transforming correlated musical features into a set of linearly uncorrelated variables called principal components. Reducing dimensionality using PCA improves classification performance by eliminating noise and highlighting the most significant features.

## Project Structure

This project includes the following:

- **music_dataset_mod.csv**: The dataset containing musical features extracted from tracks across different genres.
- **Music Data Legend.xlsx**: A file that explains the features in the dataset.
- **Music Genre Classification with PCA - Project.ipynb**: A Jupyter Notebook where the machine learning model is built, evaluated, and predictions are made.

### Required Libraries

Before you begin, ensure you have the following Python libraries installed:

- pandas
- NumPy
- matplotlib
- scipy
- scikit-learn
- seaborn

These libraries will help with data manipulation, visualization, and building machine learning models.

## Getting Started

1. Download the **music_dataset_mod.csv** and **Music Data Legend.xlsx** files.
2. Open the **Music Genre Classification with PCA - Project.ipynb** notebook in Jupyter Notebook.
3. Run the first cell to import the required libraries and prepare the data.
4. Follow the steps in the notebook to perform PCA, train a logistic regression model, and predict the genres of the unlabeled tracks.

## Conclusion

By the end of this project, we'll have predicted the missing genres for the tracks in the dataset and learned how to apply PCA for dimensionality reduction and logistic regression for classification. This process will help us uncover hidden patterns in the music data that can be useful for building music recommendation systems and improving the accuracy of genre classification.

