
![](/images/hh_logo.jpg)
# <center> Project: Resume analysis for HH.ru </center>
## Contents
1. [Project description](#Project-description)
2. [About Structure](#About%20Structure)
3. [Dependencies](#Dependencies)
4. [Download Project](#Download-Project)
5. [Autors](#Autors)
6. [Findings](Findings)

## Project description

> **HH.ru** - HeadHunter (hh.ru) is the largest Russian online recruitment company developing business in Russia, Belarus, and Kazakhstan. More than 515 thousand companies are HeadHunter clients. The extensive database of applicants on hh.ru contains more than 55 million resumes, and the average daily number of vacancies exceeds 933 thousand. According to SimilarWeb, HeadHunter ranks third in the world in popularity among job search portals and employees[3].


Main stage of Project:
* Formulation of the problem.
* Data structure research.
* Data preparation.
* Exploring data dependencies.
* Data cleaning.




**Purpose of formulation of the problem** — 
By setting the task, we understand the acquaintance with the data and the initial preparation of the data for work.

**Purpose of data structure research** — 
The research of the data structure is understood as the division of some features into several more informative ones. The study of the diversity of features obtained from the database. Suggestion for future work.

**Purpose of data data preparation** — 
Data preparation includes a deeper study of features and their comparison with each other.

**Purpose of exploring data dependencies** — 
The study of dependencies in data refers to the construction of pivot tables and the visualization of graphs to form an understanding of the need for further transformations. Based on the information obtained at this stage, we can get an understanding of the trends in the studied traits, outliers and traits that require detailed study.

**Purpose of data cleaning** — 
Drop "trash", that can interfere with the simulation or distort his result. In many tasks data cleaning - this is main part of stage of preparation data to build a model. 
For that need a lot of time to work.

**Adout Structure:**
* [data](./data) - folder with general and additional data base
* [plotly](./plotly) - folder with picture of diagrams from main file.
* [Project-1. Main-File.ipynb](./Project-1.%20Main-File.ipynb.ipynb) - jupyter-notebook, contained main code of project.


## Data Description
This project uses data from the training task SkillFactory School. Based on [MetaBase](https://www.metabase.com/)

The requirement of the terms of reference was to build informative tables based on the database of vacancies of the HH.ru resource. The database consists of 5 tables linked by keys. The tables contain information about: Companies, Vacancies, type of activity, regions and a linking table with keys.

## Used Dependencies
* Python (3.9):
    * [psycopg2 (2.9.5)](https://pypi.org/project/psycopg2/)
    * [pandas (1.3.4)](https://pandas.pydata.org)
    * [plotly (5.12)](https://plotly.com/python/)

## Download Project

```
git clone https://github.com/dI98Sk/project_HH_SQL
```

## Usage
All infirmation show in mainFile.ipynb.

##  Autor

* [Skakun Dmitrii](https://www.instagram.com/skakun_dr/)

## Findings

In conclusion, we can say that the work done has a positive effect on future modeling, and helps to build a more accurate model.
