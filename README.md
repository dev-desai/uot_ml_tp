## Overview

### Data Set

[Concrete Compressive Strength Data Set](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength)


I-Cheng Yeh, "Modeling of strength of high performance concrete using artificial neural networks," Cement and Concrete Research, Vol. 28, No. 12, pp. 1797-1808 (1998).

### Notebooks

- Data Set Analysis - this notebook contains a comprehensive analysis of the dataset. It will also contain functions to load, scrub and save the scrubbed data as an input for the machine learning notebooks
- K Neighbors Regression notebook evaluates the use of KNN models for prediction.
- Random Forests Regression notebook evaluates the use of Random Forests to predict concrete strength.

**Scrubbed Datasets**

Two scrubbed version of the dataset are available, one in json the other one in pickle format. The data has been scaled using MinMax scaler on the predictors and is split in train/test subsets.

- processed_data.json
- processed_data.pickle (Python version: 3.7.4)