

# Feature Engineering ( panda vs pyspark )


* ### Time domain feature engineering:

  Calculate the rolling statistics of data to help data modeling and interpretability.

  Below shows the format of input and output data for feature engineering. By inputting a dataset with series of samples, some time domain and frequency domain features will be derived for each column in the original dataset.

  ![](https://i.imgur.com/czm0iqP.png)

* ### Panda vs pyspark:

  Pandas run operations on a single machine whereas PySpark runs on multiple machines. If you are working on a Machine Learning application where you are dealing with larger datasets, PySpark is a best fit which could processes operations many times(100x) faster than Pandas.
  
  In this github, we try use panda and pyspark way to do feature engineering. It save a lot of time especially in the large dataset.


* ### The rolling statistics show below: 

  ![](https://i.imgur.com/wPCkAaZ.png)






