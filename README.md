# Titanic Survival Prediction
## _Predicting survival rates for Titanic Survival_

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

## Dataset

The train.csv will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.

The `test.csv` dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.Using the patterns you find in the train.csv data, predict whether the other 418 passengers on board (found in test.csv) survived.

## Installation

The project code should be executed on Python and can be downloaded from below:
- [Python](https://www.python.org/ftp/python/3.9.6/python-3.9.6-amd64.exe) 

Python's package manager(Pip) is required to install python libraries. This will be downloaded and installed automatically with the above step. In case if its not installed by default, follow the below steps:
- Download the package from [Package Manager](https://bootstrap.pypa.io/get-pip.py) using Firefox browser. For any other browser, right click on the opened page and click `Save As` to save the file
- From command prompt, navigate to the directory where the pacakge is downloaded
- Run the command `python get-pip.py`

To install the dependent libraries execute the below commands in command prompt:
- pip install pandas
- pip install -U scikit-learn

To run the code, we also need an IDE which can be installed from [Jupyter Notebook](https://jupyter.org/install)

## Code

- The executable code is given in the code folder and the filename is `TitanicSurvivalPrediction.py`. The code performs the preprocessing on training and testing datasets followed by handling missing data with various statistical measures, Scaling and then we trained it with Machine Learning Algorithms followed by Hyper parameter tuning and CrossValidation mechanism.

-  The model is built and the test data is passed to calclulate accuracy which is our evaluation metric and produced predictions in a new file i.e. `gender_submissions.csv` to submit on kaggle and get the final score. 

## Execution
Run `TitanicSurvivalPrediction.py` which is available in the Code folder, dataset files that are mentioned above should be placed in `data` folder and follow the below steps:
- Open Jupyter Notebook
- Click on `Cells` (option which is available on the top pallette)
- From pop-up window, click `Run All` and it runs the code
## Repository

Project Link: https://github.com/pavanadityay/TitanicSurvival








