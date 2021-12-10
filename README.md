# Time Dynamic NEAT - A Validation Set-Based Heuristic for Neuroevolution on Large Datasets
## Amogh Shreedhar Inamdar, Anagha M Rajeev, Sindhuja V Rai

This project defines heuristics for data input to the NEAT algorithm.
It compares the default neat-python implementation with heuristics and backpropagation using Keras on a classification task on a cardiovascular disease dataset.

The dataset is in the '3-cleaned-normalized.csv' file.

The default neat-python implementation on this dataset is in the neatCARDIO Jupyter Notebook. It has an associated configuration file (required by neat-python) called cardioconfig.
--The dataset sample size used can be changed using the max_items variable, and the number of generations can be changed in the p.run() function.

A template heuristic implementation with directly modifiable parameters is in the neat-heuristic Jupyter Notebook. The associated configuration file is neat-config-cardio.
--The dataset sample size used can be changed using the max_items variable. The heuristic parameters can be varied in the run_dynamic function.

The Validation Heuristic is implemented in the neat-validation-heuristic Jupyter Notebook. The associated configuration file is, again, neat-config-cardio.
--The dataset sample size used can be changed using the max_items variable.

The backpropagation algorithm is implemented in the keras_neural_network Jupyter notebook.

