# Project Cycle 3: Variable Notes & Recoding Rules

**Dataset:** `YRBS_2007.csv`
**Research Question:** Question 3 (Gender and Sad or Hopeless Feeling)

## 1. Group Variable Definition
* **Variable Name:** `WhatIsYourSex`
* **Definition:** Used to divide the sample into two independent groups (Female vs. Male).
* **Coding:** 
  * `1` = Female
  * `2` = Male
  * *Note: Missing values (NaN) were dropped.*

## 2. Response Variable Definition & Recoding
* **Variable Name:** `SadOrHopeless`
* **Definition:** Binary response variable indicating whether the student felt sad or hopeless.
* **Recoding Rules:**
  * Original Code `1` (Yes) -> **Recoded as `1`** (Success / Exposed group)
  * Original Code `2` (No) -> **Recoded as `0`** (Failure / Comparison group)
  * *Note: Missing values (NaN) or any other invalid codes were dropped to ensure data integrity.*
