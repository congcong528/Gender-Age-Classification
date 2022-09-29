## To execute training

The libraries for PyTorch, Cleverhans and Numpy are required for this project. This code is executed in Python 3.8.10. CUDA is preferred but not strictly necessary.

To install Cleverhans, type in:

pip3 install cleverhans

Download the Adience dataset file called aligned.tar.gz from http://www.cslab.openu.ac.il/download/adiencedb/AdienceBenchmarkOfUnfilteredFacesForGenderAndAgeClassification/aligned.tar.gz, and create a folder called data in the same directory as the .ipynb notebooks. Then, extract the dataset to the data folder, into a folder called 'aligned'

After that, download all the files from this Github Repository https://github.com/GilLevi/AgeGenderDeepLearning/tree/master/Folds/train_val_txt_files_per_fold and put them into the data folder.

The data folder should consist of:

data/aligned/...
data/train_val_txt_files_per_fold/test_fold_is_0
data/train_val_txt_files_per_fold/test_fold_is_1
data/train_val_txt_files_per_fold/test_fold_is_2
data/train_val_txt_files_per_fold/test_fold_is_3
data/train_val_txt_files_per_fold/test_fold_is_4

Then, execute all the blocks of code.

# Pretraining

Create a folder called data_faces in the same directory as the .ipynb files.

Download the CelebA aligned image dataset, along with the list_attr_celeba.csv that is part of the dataset.

Extract the aligned image dataset into a folder called img_aligned_celeba inside the data_faces folder.

The data_faces folder should consist of:

data_faces/img_aligned_celeba/*.jpg
data_faces/list_attr_celeba.csv

Then, execute all the blocks of code.
