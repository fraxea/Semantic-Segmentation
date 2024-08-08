# Semantic Segmentation

We did semantic segmentation task on a dataset used for self-driving cars.

## Model

The first architecture that we used is U-Net. Then we improved it by Attention U-Net.

## Results

By hyperparameter tuning on Attention U-Net model, we approched $\text{mIoU}=0.50$.

![alt text](./Images/results.png)

Here is the training phase results.

![alt text](./Images/loss.png)

More details on [Semantic_Segmentation notebook](./Semantic_Segmentation.ipynb).
