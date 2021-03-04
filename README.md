# unet_pytorch

To use this model, first change the Dataset class in dataset.py.
I used it to train a Brain Scan dateset to segement the part of the scan with brain tumor.
To apply tranforms you can either use the tranforms in __getitem__ function or use the torchvision transforms.

Second thing you would need to change in the train and validaiton directory of images in the train.py.

I got a dice score of ~64% will training on the following dataset:- https://figshare.com/articles/dataset/brain_tumor_dataset/1512427.
