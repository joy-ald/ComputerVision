#Image classification

These files demonstrates image classification/prediction using KNearest Neighbor by subsampling from CIFAR-10

knn.ipynb predicts the class (to a class available in CIFAR-10 dataset ) of given image.
Model is trained 80:20 on 50,000 dataset, 32x32 images
training subsample size = 5000 (Ntr), test subsample size = 500 (Nte)
Compute Euclidian distances between each test and training data, a matrix of size NtexNtr

