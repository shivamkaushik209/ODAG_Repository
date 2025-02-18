# CMS_AUDIT_ODAG
## Data Pipeline with Databricks

This project demonstrates a data pipeline in Databricks that extracts data from Azure Blob Storage, transforms it, and loads it into a data lake for further analysis. It also generates output files in .csv format.

## Table of Contents
1. [Overview](#overview)
2. [Setup and Installation](#setup-and-installation)
3. [Usage](#usage)
4. [Folder Structure](#folder-structure)
5. [Dependencies](#dependencies)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Overview
This Databricks project builds an end-to-end pipeline using Spark to process and analyze data. The project extracts data from Azure Blob Storage, transforms it, and stores it in a data lake. It also generates output files in .csv format.The workflow first ingests a parameter file that 

## Setup and Installation
1. Clone the repository:

    ```bash
    git clone https://github.com/shivamkaushik209/ODAG_Repository.git CMS_AUDIT_ODAG
    cd CMS_AUDIT_ODAG
    ```

2. Set up your Databricks workspace:
    - Create a cluster in Databricks with the necessary configurations.
    - Attach notebooks to the cluster.

3. Upload notebooks and datasets to the Databricks workspace.

## Usage
To use this project in Databricks:
1. I have created a Databricks workflow "ODAG Workflow". This runs the parameter notebook and other dependent notebooks:

## Folder Structure
```bash
├── notebooks/
│   ├── parameter_file.ipynb
│   ├── Header Validation.ipynb
|   ├── Aggregation
      ├──Final Table.ipynb
      ├──Null Report.ipynb
      ├──Truncation Report.ipynb
      ├──With Indicator.ipynb
      ├──Without Indicator.ipynb
      ├──stg table creation.ipynb
├── data/
│   ├── parameter-file/
│   └── input-file/
    └── aggregated-files/
