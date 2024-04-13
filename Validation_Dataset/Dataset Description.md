# Impact Weighted Accounts Test Dataset

This folder contains a dataset intended to validate the feasibility of integrating impact-weighted accounting data with data visualisation and analysis tools.

Here's a description of the files:		

| File                                               | Description                                                  |
| -------------------------------------------------- | ------------------------------------------------------------ |
| Dataset Description.md                             | This is the Markdown file you are currently reading          |
| **IWAI_Product_Impact_Data_2021.csv**              | **This is the validation dataset.** It has been formatted for ingress into data analysis tools with no whitespaces in the header row |
| IWAI_Product_Impact_Dataset_Field_Descriptions.csv | This document describes the information presented in the validation dataset |



Columns: 13

Values from financial reports: 1 (EBITDA)

The values from IWAI analysis are:

- "Total product impact" (expressed as USD). This is the monetised impact of the following **8** variables:
  - Affordability , calculated
  - Underserved, calculated
  - Health and Safety, calculated
  - Effectiveness, calculated
  - Basic need, calculated
  - Addiction, calculated
  - Pollution intensity, calculated
  - Recycling and waste, calculated

## Validated Databases Types:

Have validated imports of this file to the following database servers (or pending):

| Database Type | Validated? |
| ------------- | ---------- |
| MySQL         | ✅          |
| PostgreSQL    | ✅          |
| MongoDB       | ✅          |

## Validated Programs:

Programs the dataset was imported to alongside environment and results:

| Platform      | Environment    | Validated? |
| ------------- | -------------- | ---------- |
| Metabase      | Local (Docker) | ✅          |
| Apache Sunset | Local (Docker) | ✅          |
| MongoDB Atlas | Cloud          | ✅          |
| Aiven         | Cloud          | ✅          |
| Heroku        | Cloud          | Pending    |

## **Notes:**

- The dataset was compiled by research conducted by the Impact Weighted Accounts Initiative (IWAI) in 2021. 
- The International Foundation for Valuing Impacts (IFVI) continues this work. 
- The compilation of this edited dataset and this project reflects a private effort and is not endorsed by any particular entity

---

Author: Daniel Rosehill