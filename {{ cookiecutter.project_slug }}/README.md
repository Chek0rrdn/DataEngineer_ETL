# {{ cookiecutter.project_name }}
By: {{ cookiecutter.project_author_name }}


# Introduction
{{ cookiecutter.project_description }}


## Installation guide
Please install the files in [requirements.txt](requirements.txt) for the project execution.
> **Note**: To run the main program it is necessary to install all the required packages.
This can be done with the command:


```sh
pip3 install -r requirements.txt 
```


## Using the Scraper
To use the program use the following syntax:

```sh
python3 pipeline.py
```



## Resulting directory structure
 {{ cookiecutter.project_slug }}
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
