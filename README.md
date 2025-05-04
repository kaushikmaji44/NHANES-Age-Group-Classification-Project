# NHANES Age Group Classification Project

This project utilizes the National Health and Nutrition Examination Survey (NHANES) dataset to classify individuals into age groups based on various health and lifestyle features. The primary goal is to predict whether a respondent is an adult (under 65 years old) or a senior (65 years and older).

## Table of Contents

- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
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

## Project Structure

```
.
├── data
│   └── nhanes_subset.csv          # Original dataset file
├── notebooks
│   └── Classification_Project.ipynb  # Jupyter notebook with the project code
├── README.md
└── requirements.txt               # Required Python packages
```
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
