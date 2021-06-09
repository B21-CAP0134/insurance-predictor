# Insurance Predictor ML
The machine learning part from 3 different subteam (Cloud, Android, Tensorflow).

To replicate the model, open the notebook on a Colab session, local Jupyter, or your notebook client of choice and follow along the instructions inside the notebook.

## Model Architecture
For the machine learning part, the data is preprocessed from structured, table form to TF dataset with feature columns. Age and BMI are bucketized, sex region and smoker are transformed to categorical, and children is left as it is. The architecture of the model consists of the DenseFeatures, lambda layer to expand the feature dimension, a Conv1D with 16 filters and size kernel of 5, a flatten layer, 2 dense layers with 128 and 64 units respectively, and then the regressor layer that outputs the predicted medical charge. This is the summary of the model: <br>
![](https://github.com/B21-CAP0134/insurance-predictor/blob/main/model_summary.png)

## B21-CAP0134 Team Member

| Name   |      Student ID      |
|----------|:-------------:|
| Ali Naufal Ammarullah |  A0010022 |
| Muhammad Hafizhan |    A0010025   |
| Bob Yuwono | C0010017 |
| Qassandra Chaidir | C3302950 |
| Indah Puspita | M0010008 |
| Fahreza Ikhsan Hafiz | M0010015 |
