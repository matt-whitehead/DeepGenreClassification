# DeepGenreClassification
Music Genre Classification as a final project for SI 670: Applied Machine Learning

## Introduction
Music Genre Classfication in Scikit-learn and Keras on the GTZAN dataset from the University of Victoria. You can download the data [here](http://opihi.cs.uvic.ca/sound/genres.tar.gz).

## Notebooks
* [Traditional Machine Learning](https://github.com/matt-whitehead/DeepGenreClassification/blob/master/Traditional_ML.ipynb)
  * Feature Extraction
  * Data Visualization
  * Modeling
      * Logictic Regression
      * Random Forest
      * Gradient Boosted Forest
      * SVM (RBF kernel)
      
* [Spectrogram Extraction](https://github.com/matt-whitehead/DeepGenreClassification/blob/master/Spectrogram_Extraction.ipynb)
  * Data Preprocessing 
  
* [Neural Model](https://github.com/matt-whitehead/DeepGenreClassification/blob/master/Neural_Model.ipynb)
  * Model Building
  * Training
  * Evaluation
  
  # Note
  Training the neural network used in this project takes quite a long time. It took me a little over an hour to train on an NVIDIA Tesla K80 GPU running on an AWS p2.xlarge instance.
