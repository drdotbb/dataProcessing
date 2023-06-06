#### COMMAND TO RUN: python3 dataProcessing.py input predict output.csv > outputlog.txt

Data will run a comparison with p scores against various models, choosing the model with the highest score for evaluation and fitting. Data will then run against test data to produce some test predictions. Test predictions will be compared to actual classification to produce an accuracy percentage.

- input - folder to put the walking data. Data is already provided
- predict - folder to put the data for predicting. Data is already provided
- dataProcessing.py - program to read, process, and output results
- output.csv - output program for result comparison
- outputlog.txt - an outline of the processes in the program including Data reading/formating/processing, model testing, and accuracy evaluation
