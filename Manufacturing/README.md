# Steel-Defect-Classification
This project applies binary classification to steel cast products using Tensorflow and Keras.

# Context

Steel Casting is a manufacturing process in which a liquid molten is poured into a mould with a hollow cavity of the desired shape, and is then allowed to solidify. Casting defects are an undesired irregularity in metal casting process. Defects include blow holes, pinholes, burr, shrinkage, mould material defects, pouring metal defects, metallurgical defects.

Traditionally, quality management for these errors are carried out manually, making the process time consuming and labour intensive. The human factor also adds an element of subjectivity which can translate into false positives and false negatives. However, machine learning can be employed to facilitate effective quality inspection.

# Data

The dataset contains 7348 images of impellers for submersible pumps sized 300x300 pixels. There are two classes of images: defective and optimal.

# Methodology

This is a binary classification problem. This notebook will deploy a convolutional neural network using TensorFlow and Keras to accurately classify defective and optimal impellers.
