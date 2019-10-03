# Brain-Tumour-Detection-using-MRI

![Brain Tumour Detection](https://github.com/pranaysawant/Brain-Tumour-Detection-using-MRI/blob/master/check_brain_mri.jpeg)


## 1.1 Problem Definition
There are some Brain MRI images of some patients some patients have **Brain Tumour** and some do not have. So we need to build a model which can predicted tumour patients.

## 1.2 Data

The dataset contains 2 folders: yes and no which contains 253 Brain MRI Images. The folder yes contains 155 Brain MRI Images that are tumorous and the folder no contains 98 Brain MRI Images that are non-tumorous.

Data is collected from Kaggle.com.
https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection

## 1.3 Performance Metric

- Logloss
- Confusion Matrics

## Model

- build CNN models from scratch
- reused VGG16 model.

## Model Evalution
- Log Loss : 0.33
- Accuracy : 90%
- FNR : 0.04
- FPR : 0.20
