# Introduction to Data Science and Machine Learning with Python

<p align="center">
  <img src="/imgs/mtp_logo.png"/>
</p>

The notebooks of this repository have been developed to support the 
**Introduction to Machine Learning with Python** course I designed and delivered for
[marktechpost.com](https://www.marktechpost.com/).

<hr>

### Data Science Libraries

The notebook dl_libraries shows and explains the usage of some Data Science libraries for
data analysis and data visualization:
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Wordcloud
- Folium (to visualize data on interactive maps)
- Scikit-learn (mainly considered in the other notebook)

<hr>

### Machine Learning Pipeline

The ml_pipeline notebook shows how to implement a typical machine learning pipeline to detect the age
of a person based on voice data:
- Data Exploration: the dataset used is the 
[Common Voice](https://www.kaggle.com/datasets/mozillaorg/common-voice?select=README.txt) dataset from Kaggle

- Data Pre-Processing: data cleaning and transformation

- Feature Engineering: feature extraction, transformation, and selection through scikit-learn

- Model Selection: trained through scikit-learn Support Vector Machine and Random Forest models that are finally evaluated through the cross-validation technique
