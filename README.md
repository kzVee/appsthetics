# Appsthetics

Appsthetics is a neural network model developed with the use of the fast.ai library to predict the visual aesthetic rating of mobile Android applications' user interfaces.

The present Jupyter Notebook contains all of the code, training and the results achieved by the model and is structured as such:

## Part 0 - Coming back from a restart...
This is a quick, one-step, code cell that will reinitialize all of the imports and variables needed for training. It should only be ran after a Runtime restart. If you're accessing the Notebook for the first time in a while, skip to Part 1 for the proper initialization of the project.

## Part 1 - Initializations
This section takes care of all the initializations needed, from checking if the current machine's specs are adequate to setting up your Google Drive as a virtual disk so the Notebook can read from and write to it.
Library imports and all the prep work for the dataset also takes place in here.

## Part 2 - ResNet34
This was the starting point of Appsthetics. We load up the ResNet34 model and perform trainings, fine-tunings and evaluate the results for the ResNet34 in this section.

## Part 3 - Less powerful networks...
This section covers the training, fine-tunings and results of the ResNet18 model.

## Part 4 - More powerful networks...
This section covers the training, fine-tunings and results of the ResNet50 and ResNet101 models.

## Part 5 - Saved models
This is a section with notes of the best achieved results for each model trained. For quick future reference.

## Part 6 - Misc.
This section contains some work that was being done for the Bland & Altman test and some other things.
