# It’s Time to get Real: Investigating the Effectiveness of Linguistic and Sentimental Features in Identifying Fake Review

This repository presents the code and datasets related to my Master Thesis for Marketing Analytics. Within the code section, you can find the data preparation and cleaning, feature extraction code (linguistic features and sentiment features), feature selection code using RFE, and machine learning code with analysis.

## Introduction

In my thesis, I have researched to what extent a machine learning algorithm can detect fake reviews using only linguistic and sentimental features in e-commerce and which linguistic and sentimental features are most effective. Consumers have extensively used electronic word of mouth (eWOM) through online platforms to acquire product feedback. However, the increasing number of fake reviews has raised concerns among customers. This research aims to provide more transparency and information on detecting fake reviews and their relevant features.

## Summary

Consumers' dissatisfaction and suspicion towards online reviews have led to an urgent need for more transparency and information on detecting fake reviews. Previous studies have shown that linguistic and sentiment analysis features can effectively distinguish between fake and real reviews. In this research, textual features such as sentiment and linguistics are analyzed to understand and predict fake reviews. The effectiveness of sentiment lexicons in detecting fake reviews is also explored.

## Data Description

I used an Amazon dataset (https://www.kaggle.com/datasets/lievgarcia/amazon-reviews) for this research. The dataset contains 21,000 reviews equally distributed across product categories, with 10,500 fake reviews and 10,500 real reviews. The reviews are labeled as fake (label 1) or real (label 2). The dataset also includes additional features for each review, such as rating, verified purchase, product category, product ID, product title, review title, and review text. The data is stored in the "data" folder of this repository.

## Directory Structure

- **data**: Contains the Amazon dataset used for the research.
- **src**: Contains the code for data preparation, cleaning, feature extraction, and machine learning.
  - **src/machine_learning_code**: Contains the machine learning code and analysis.
  
## Build Instructions

### Dependencies
To replicate this project, you need the following dependencies:
- Python
- pandas
- NLTK
- textstat
- vaderSentiment
- scikit-learn
- matplotlib

You can install the necessary Python packages using the following command:
pip install pandas nltk textstat vaderSentiment scikit-learn matplotlib

### Running the Project
1. Clone this repository to your local machine.
2. Install the required dependencies as mentioned above.
3. Navigate to the appropriate directory where the code is stored.
4. Execute the code files in the desired order to perform data preparation, feature extraction, and machine learning analysis.

## Contributing:
  You can contribute by doing one of the following:
  - Starring the repository ⭐
  - Forking the repository 🍴
      1. Fork the repository.
      2. Create a new branch: `git checkout -b feature/new-feature`
      3. Commit changes: `git commit -am 'Add new feature'`
      4. Push to the branch: `git push origin feature/new-feature`
      5. Submit a pull request.
  - Creating an Issue ❌
  - Creating a Pull Request ✔
