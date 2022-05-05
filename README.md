# Two-Knot-MachineLearning
This contains all the raw data and accessory code to train similar models

## .pkl files

The files with the `.pkl` extension contain the generated knots in various states of processing. To open these, you must import the Python module `pickle`, then call `pickle.load(open("file.pkl", "rb"))`. These files are in binary format, and so without the `rb`, trying to read the files will fail.

## Knots.ipynb

The file `Knots.ipynb` contains the actual training process from loading in the data, setting all the hyperparameters, and actually training the data. It also includes defining our three models and the training process, along with our accuracy results.
