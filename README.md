# bioninformatic_project

All the experiments have been conducted in separated ipynb files.
All the experiments are contained in this two main folders:
  - "inactive promoters vs active promoters", contains the experiments done on tasks related to the promoters regions;
  - "inactive enhancers vs active enhancers", contains the experiments done on tasks related to the enhancer regions;
The sub-folders have been organized based on the different TMP thresholds used to decide the activation status of the regions and on the different types of neural network applied on that task.
Last sub-folders contains the ipynb file to run the single experiment, the images related to the performances obtained with that type of NN model and two csv files:
  - "all_performances_{region}_{TPM}_{model_name}.csv" file, in which are stored the perfomance obtained by the model on each holdout generated 
  - "best_models_{region}_{TPM}_{model_name}.csv" file, that contains a classification, based on the model selection step, of the best parameters that can be used in order to train a model for the given task.

All the experiments have been run in a COLAB environment with a GPU/TPU accelerator, the ipynb files contains also a cell with all the required library needed to run properly the code;

In order to run properly the ipynb related to the MMNN models the files "best_models_{region}_{TPM}_cnn.csv" and "best_models_{region}_{TPM}_ffnn.csv" need to be loaded on the environment.

