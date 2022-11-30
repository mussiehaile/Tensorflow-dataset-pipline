# Tensorflow-dataset-pipline

The tf.data.Dataset API supports writing descriptive and efficient input pipelines. Dataset usage follows a common pattern:

Create a source dataset from your input data.
Apply dataset transformations to preprocess the data.
Iterate over the dataset and process the elements.
Iteration happens in a streaming fashion, so the full dataset does not need to fit into memory.
