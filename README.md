# Comparing SVM and Neural Nets to Solve a News Classification Problem

# Goal
classify news based on their headline and short description into 4 categories (politics, wellness, entertainment, travel)

# Dataset
https://www.kaggle.com/rmisra/news-category-dataset

# Methods
* Text vectorization : TF-IDF
* SVM : polynomial kernel
* Neural network : fully connected layer

# Result
## SVM
* accuracy : 0.865 (testing)
* training time : 673.17 s

## Neural network (trained using GPU)
* accuracy : 0.994 (trainng) and 0.857 (testing)
* training time : 192.48 s
