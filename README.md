# ECE285-GAN-for-Super-Resolution

## Implement ESGAN for Super Resolution based on https://github.com/xinntao/ESRGAN
1.Dependencies: Python3 and PyTorch.
<br>
2.Change the dataset to a subset of Caltech-256: select images random from different classes.

## train.ipynb used for training
1.The training set is stored in HR_data, and the validation set is stored in Val_data.
<br>
2.The ESGAN architecture is implemented in model.py and block.py, the loss function is implemented in loss.py.

## demonstration.ipynb used for demostration
1.The HR, LR and SR images are stored in HR, LR and SR respectively.
<br>
2.The trained model, pretrained model from https://github.com/xinntao/ESRGAN and fine tuned model are stored in SavedNetworks.
