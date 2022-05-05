# Two-Knot-MachineLearning
This contains all the raw data and accessory code to train similar models

## .pkl files

The files with the `.pkl` extension contain the generated knots in various states of processing. To open these, you must import the Python module `pickle`, then call `pickle.load(open("file.pkl", "rb"))`. These files are in binary format, and so without the `rb`, trying to read the files will fail.

## Knots.ipynb

The file `Knots.ipynb` contains the actual training process from loading in the data, setting all the hyperparameters, and actually training the data. It also includes defining our three models and the training process, along with our accuracy results.

## Generation.ipynb

The file `Generation.ipynb` consists of code written in [SageMath](https://www.sagemath.org/), which based heavily off Python; if you can read Python code, you can read Sage code. Everything in the first cell consists of functions written last summer for the REU and is used to calculate the Alexander invariant for an arbitrary 2-knot using the Seifert-van Kampen theorem. The bottom-most cell was written for this project to generate arbitrary 2-knots and compute the corresponding Alexander invariant.
