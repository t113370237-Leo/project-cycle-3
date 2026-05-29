# Project Cycle 3: Variable Notes (Extension Analysis)

**Dataset:** `YRBS_2007.csv`
**Research Question:** Extension (Mental Health and Sleep Hours)

## 1. Group Variable (Independent)
* **Original Variable:** `SadOrHopeless`
* **New Variable:** `Sad_Label`
* **Definition:** Used to divide the sample into two groups based on mental health status.
* **Recoding Rules:** * Code `1` (Yes) -> **`'Sad / Hopeless'`**
  * Code `2` (No) -> **`'Not Sad'`**

## 2. Response Variable (Dependent)
* **Original Variable:** `Sleep`
* **New Variable:** `Sleep_Hours`
* **Definition:** Continuous numeric variable representing the average hours of sleep on a school night.
* **Transformation Rules:**
  * Original codes ranged from `1` (4 or less hours) to `7` (10 or more hours).
  * Rule: **`Original Code + 3`** -> Yields a continuous range from **`4 to 10`** representing actual hours.
