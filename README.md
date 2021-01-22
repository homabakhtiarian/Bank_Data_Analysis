# Bank Data Tensorflow Project
We'll use the <a href='https://archive.ics.uci.edu/ml/datasets/banknote+authentication'>Bank Authentication Data Se</a> from the UCI repository.

The data consists of 5 columns:

* variance of Wavelet Transformed image (continuous)
* skewness of Wavelet Transformed image (continuous)
* curtosis of Wavelet Transformed image (continuous)
* entropy of image (continuous)
* class (integer)

Where class indicates whether or not a Bank Note was authentic.

** When using Neural Network and Deep Learning based systems, it is usually a good idea to Standardize your data! **

** Now create a tf.estimator.pandas_input_fn that takes in your X_train, y_train, batch_size and set shuffle=True. You can play around with the batch_size parameter if you want, but let's start by setting it to 20 since our data isn't very big. **
