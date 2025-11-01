### Econometric analysis of factors affecting Life expectancy

- This project is done in the course ```Econometrics``` at IIT Palakkad
- This is a regression analysis of all factors affecting life expectancy
- Data is taken from Kaggle's WHO Life expectancy dataset
- [Kaggle link](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)


### Features (Independent Variables)
1. Country
2. Status
3. Adult Mortality
4. percentage expenditure
5. Measles
6. BMI
7. Polio
8. Diphtheria
9. HIV/AIDS
10. GDP
11. Population
12. thinness  1-19 years
13. Income composition of resources


### Target (Dependent variable)
- Life expectancy

### Minimal requirements
- Python3


### How to run
1. Create a virtual environment
- On linux / maxOS (Command Line or Terminal)
``` bash []
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -r requrirements.txt
```

- On windows (Powershell or Command Line)
``` powershell []
> python -m venv .venv
> .venv/Scripts/activate
> pip install -r requirements.txt 
```

2. Go to [main notebook](notebooks/main.ipynb) in vscode or jupyterlab / jupyter notebook.
3. Select ```.venv``` as the python environment for the notebook
4. Click ```run all cells``` to get the analysis results



### Tech stack used
1. python
2. jupyter notebook
3. vscode (for editing)
4. python libraries
    - statsmodels
    - scikit-learn
    - pandas
    - numpy
    - seaborn


### Directory structure
```
.
├── data
│   └── Life-Expectancy-Data.csv    # Main dataset used
├── LICENSE                         # License
├── notebooks
│   └── main.ipynb                  # Core code resides here
├── README.md                       # This file
└── requirements.txt                # project dependencies
```