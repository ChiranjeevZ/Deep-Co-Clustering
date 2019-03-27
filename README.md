# Deep-Co-Clustering

This is a reference implemenmtation for Deep Co-Clustering (SDM'19). Please feel free to contact Dongkuan Xu (dux19@psu.edu) if you have any question.

# Main function
The main file is DeepCC/Code/main_coil20.py. It is for the Coil20 dataset.

Other datasets used in our paper are included in DeepCC/Data.

# Input and Output
The input is the data in the form of a matrix. Rows and columns represent instances and features respectively.

The output is the accuracy and NMI of each iteration.

# Run DeepCC on your datasets
It is easy to run DeepCC on your datasets by changing the data_path in main_coil20.py (Line 13).

Please change the input dimensions of autoencoders correspondingly when run it for other datasets (Line 19, 21).

# Important

1. The main file is: main_coil20.py

1.1. main_coil20.py is for the Coil20 dataset

1.2. it is easy to run DeepCC on other datasets by changing the data_path in main_coil20.py

1.3. Another important file is: core/paegmm/kddcup10/kddcup10_pae_gmm.py. This file contains the main body of DeepCC (including the hyperparameter setting).

2. The main file is: main_
