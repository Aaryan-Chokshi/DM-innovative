# Garbage image classification using YOLOv8n

Performed classification task of identifying 28 different waste categories from the WaRP - Waste Recycling Plant Dataset (available at Kaggle - [link](https://www.kaggle.com/datasets/parohod/warp-waste-recycling-plant-dataset)) using a YOLOv8n model.

Trained the model over forty iterations to ensure appropriate training. The training was monitored from WandB, which gives real-time info regarding the loss function, accuracy improvements and the result of latest training over a small validation set. 

We were able to get 64% precision and box loss to be 0.76. The attached files here contain the final trained weights and data to help train and refine the model further.
