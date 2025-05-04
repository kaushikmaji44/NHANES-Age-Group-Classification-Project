# NHANES Age Group Classification Project

This project utilizes the National Health and Nutrition Examination Survey (NHANES) dataset to classify individuals into age groups based on various health and lifestyle features. The primary goal is to predict whether a respondent is an adult (under 65 years old) or a senior (65 years and older).

## Table of Contents

- [Dataset](#dataset)
- [License](#license)

## Dataset

The dataset used in this project is a subset of the NHANES 2013-2014 dataset. The selected features include physiological measurements, lifestyle choices, and biochemical markers.

- **Features:**
  - `SEQN`: Respondent sequence number
  - `RIDAGEYR`: Age in years at screening
  - `RIAGENDR`: Gender
  - `PAQ605`: Vigorous work activity
  - `BMXBMI`: Body Mass Index (BMI)
  - `LBXGLU`: Fasting glucose (mg/dL)
  - `DIQ010`: Doctor told you have diabetes
  - `LBXGLT`: Glucose tolerance test result
  - `LBXIN`: Insulin (µU/mL)

- **Target:**
  - `age_group`: Categorical variable indicating if the respondent is an adult (0) or a senior (1)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
