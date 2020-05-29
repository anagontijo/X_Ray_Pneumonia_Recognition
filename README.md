# Pneumonia recognition in x-ray images
## Project by Ana Carolina Gontijo Graça for the Machine Learning - UFMG 2019.1 course

# The data set:
The data set used was obtained in Kaggle, in the link below:
    https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

  The "chest-xray-pneumonia/chest_xray/" folder must be in the current diretory where you run the notebook locally.

# Execution time:
  As it is a deep-learning project, its execution is really slow for a normal computer. If the program takes too long to run locally, uncomment lines 6, 7 and 8 from the python notebook's first cell and running in google colab with GPU acceleration the execution time is reduced considerably. It's important to notice that the images loading part will be slower in google colab, but the trainings will be faster. It's also important to notice that uncommenting the specified lines will activate the use of Google Drive as a data source, and so it will be necessary to uploads the data to that drive.
