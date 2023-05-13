
![](/images/hh_logo.jpeg)
# <center> Project on intelligence analysis of data on vacancies HH.ru </center>
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
* Preliminary data analysis.
* Detailed analysis of the job market.
* Detailed study of employers.
* Subject analysis of the IT area.





**Purpose of preliminary data analysis** — 
The study of the main quantitative indicators.

**Purpose of detailed analysis of the job market.** — 
Consideration of the main dependencies between tables, and the formation of conclusions based on their comparison..

**Purpose of detailed study of employers.** — 
Formation of requests that allows you to establish the importance of some representatives to the market as a whole..

**Purpose of exploring data dependencies** — 
Subject analysis of the IT area.


**Adout Structure:**
* [images](./images) - folder with additional pictures for decoration. .
* [plotly](./plotly) - folder with picture of diagrams from main file.
* [mainFile.ipynb](./mainFile.ipynb) - jupyter-notebook, contained main code of project.


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
