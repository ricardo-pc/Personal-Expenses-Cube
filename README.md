# Personal Expenses Cube
A collection of Python scripts to transform and consolidate my personal expense data from various debit and credit accounts, harmonizing the information into a unified data cube for analysis and wealth management.


## Table of Contents
1. [About the Project](#about-the-project)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Usage](#usage)
5. [Data](#data)


## About the Project
To achieve my personal goal of starting a master’s degree in Data Science, I first needed to secure the financial stability that would make it possible. With this in mind, I developed a personal project to monitor my spending and increase my savings.

After implementing this project for two years, I successfully raised my savings rate from 10% to 40%, bringing me closer to my goal.

The core value of this project lies in consolidating all transactions from my various accounts into a unified source of truth. This integration has proven to be a powerful tool, enabling me to gain insights and identify areas where spending can be optimized. The project covers three financial institutions — BBVA, AMEX, and HeyBanco — across both debit and credit accounts.

## Features
The project is designed with the following structure:

### **Provision Layer**
  - Prepares expense data into a unified single source of truth.
  - Includes one script per financial institution and account type (debit or credit).
  - 📕 [AMEX - Provision Layer notebook](https://github.com/ricardo-pc/Personal-Expenses-Cube/blob/main/01%20Scripts/amex-tdc-script.ipynb)
  - 📕 [BBVA Debit - Provision Layer notebook](https://github.com/ricardo-pc/Personal-Expenses-Cube/blob/main/01%20Scripts/bbva-tdb-script.ipynb)
  - 📕 [BBVA Credit - Provision Layer notebook](https://github.com/ricardo-pc/Personal-Expenses-Cube/blob/main/01%20Scripts/bbva-tdc-script.ipynb)
  - 📕 [HeyBanco Debit - Provision Layer notebook](https://github.com/ricardo-pc/Personal-Expenses-Cube/blob/main/01%20Scripts/heybanco-tdb-script.ipynb)
  - 📕 [HeyBanco Credit - Provision Layer notebook](https://github.com/ricardo-pc/Personal-Expenses-Cube/blob/main/01%20Scripts/heybanco-tdc-script.ipynb)

### **Working Structure - Composer Layer**
  - Combines all individual sources into one file.
  - Manual additions and changes can be applied here.
  - 📕 [Working Structure - Composer Layer notebook](https://github.com/ricardo-pc/Personal-Expenses-Cube/blob/main/01%20Scripts/spendcube-composer-script.ipynb)


### **Working Structure - Categorizer Layer**
  - Categorizes the spending.
  - 📕 [Working Structure - Categorizer Layer notebook](https://github.com/ricardo-pc/Personal-Expenses-Cube/blob/main/01%20Scripts/spendcube-categorizer-script.ipynb)

## **Project Structure**

This repository is organized as follows:
- `0 Data/`: Contains demo datasets (not real data).
  - `AMEX`: Demo data from American Express.
  - `BBVA Credit`: Demo data from BBVA bank, credit account.
  - `BBVA Debit`: Demo data from BBVA bank, debit account.
  - `HeyBanco Credit`: Demo data from HeyBanco, credit account.
  - `HeyBanco Debit`: Demo data from HeyBanco, debit account.
- `01 Scripts/`: Jupyter Notebooks including the Provision Layer and Working Structure.

- `02 Individual Datasets/`: Output of the Provision Layer files.
  
- `03 Consolidated Dataset/`: Output of the Working Structure - Composer Layer.
  
- `04 Taxonomy/`: Taxonomy to be used for the categorization.

- `05 Consolidated Categorized Dataset/`: Output of the Working Structure - Categorizer Layer.

## Data

This project relies on datasets stored in the `0 Data/` directory. Below are the details:

---
### **1. Included Datasets**
The following datasets are included in the repository:
  - `AMEX`: Demo data from American Express.
  - `BBVA Credit`: Demo data from BBVA bank, credit account.
  - `BBVA Debit`: Demo data from BBVA bank, debit account.
  - `HeyBanco Credit`: Demo data from HeyBanco, credit account.
  - `HeyBanco Debit`: Demo data from HeyBanco, debit account.

