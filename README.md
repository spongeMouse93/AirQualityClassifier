# AirQualityClassifier

This project uses the different machine learning categorical classification algorithms on Kaggle's Air Quality dataset.

## Obtaining the Dataset

You have two options for obtaining this data set:

1. This option requires installing the `kagglehub` package. To install for Python, run

`pip install kagglehub`

in your terminal window. Then, create a new Python project and write the following:

```
import kagglehub

path = kagglehub.dataset_download("rabieelkharoua/air-quality-and-health-impact-dataset")

print("Path to dataset files:", path)
```

The output will be the file path where the .csv file will be located.

2. You can directly download the zip file from [Kaggle itself](https://www.kaggle.com/datasets/rabieelkharoua/air-quality-and-health-impact-dataset/data) using this hyperlink.

## Results?
![alt text](https://github.com/spongeMouse93/AirQualityClassifier/blob/main/visualization.png "Accuracy Per Algorithm")

By the looks of it, the most accurate algorithm is the SVC with the polynomial kernel, which I have set with degree 3 and leading coefficient 2.
