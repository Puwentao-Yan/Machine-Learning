# ML Artwork

The purpose of this project is to train machine learning models to learn how to predict the artists of historical paintings. Creating an accurate classifier for this problem can be greatly benifical to historians attempting to classify unknown artwork. We hope to classify artist names based on brush strokes, colour choice, and other stylistic techniques that are present in the artwork. 

# Team Members
Finn Tobin
Jas Dhaul
Puwentao Yan

# Dataset

The dataset used for this project can be found on [Kaggle](https://www.kaggle.com/datasets/antoinegruson/-wikiart-all-images-120k-link?resource=download). In total, there are over 120,000 images present! However, our project will use a cleaned version of this dataset since the original dataset contains rows with unknown artists.

# Sample Data

![four sample data images](https://i.imgur.com/Qrlazof.png)

# Relevant Papers

N. Viswanathan, “Artist Identification with Convolutional Neural Networks,” _Stanford Vision and Learning Lab_, 2017. [Online]. Available: http://vision.stanford.edu/teaching/cs231n/reports/2017/pdfs/406.pdf.

# Prerequisites

 - [Jupyter Notebook](https://jupyter.org/)
 - [Numpy](https://numpy.org/)
 - [Pandas](https://pandas.pydata.org/)
 - [Scikit-Learn](https://scikit-learn.org/stable/)      
 - [Tensorflow](https://www.tensorflow.org/)
 - [SciPy](https://scipy.org/)
 
 # Code

The files for this project can be found here: https://drive.google.com/drive/folders/1UD-sSwHy-Ie6MAOSQNkjOJXTiVAKzXiC?usp=share_link

Our main models are in the following files:
 - predict_artist_cnn.ipynb
 - predict_style_cnn.ipynb
 - predict_artist_resnet50.ipynb
 - predict_styles_resnet50.ipynb


Our data was cleaned with dataCleaner.ipynb and the images were loaded with download_images.ipynb.

The files in the folder `old_code` are models that were previously trained but were discarded since they had low accuracies and thus not the focus of our report.
