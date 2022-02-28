# Cookiecutter ETL Data Engineer

_A project structure for doing and sharing data engineer work._


## Installation guide
Please install the files in [requirements.txt](requirements.txt) for the project execution.
> **Note**: To run the main program it is necessary to install all the required packages.
This can be done with the command:

```sh
pip3 install -r requirements.txt 
```

## Create a new project

In a folder where you want your project generated:

```bash
cookiecutter https://github.com/th3edger/DataEngineer_ETL
```


## Resulting directory structure

    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── extract            <- Folder with the necessary files files for data extraction.
    |
    ├── load               <- folder with the necessary files files for data upload.
    │
    ├── transform          <- Folder with the necessary files files for data wrangling.
    │
    ├── pipeline.py        <- Pipeline for successful execution.
    │
    │        
    ├── requirements.txt   <- The requirements for the project execution.
    │
    ├── .gitignore         <- Files to ignore by `git`.
    │
    │
    └── README.md          <- The top-level README for developers using this project.