# 🐶 Cat Adoption Project 

## Objective 

This project creates and builds data models and deploy databases for the cat adoption data 

## Technologies 

* Database: PostgreSQL
* Language: Python

## Data Architecture 
<img width="591" alt="237030996-a92947af-5e9b-42be-8a34-9b4073f6e7ef" src="https://github.com/Leon-Fray/data-engineering/assets/143506006/b1e40c2f-896a-4b7e-aaaa-79ee5bff9229">

1. Data is extracted from Kaggle and saved locally.
2. The cat_adoption.ipnyb scipt initiates a connection to PostgreSQL and creates teh database with auto-commit being run
3. Tables are created with the appropriate columns and data types
4. Data is fed into the newly created tables. 
