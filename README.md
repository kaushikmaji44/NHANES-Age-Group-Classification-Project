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

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nhanes-age-group-classification.git
   cd nhanes-age-group-classification
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Jupyter Notebook:**
   Launch Jupyter Notebook to explore and run the project code.
   ```bash
   jupyter notebook notebooks/Classification_Project.ipynb
   ```

2. **Follow the steps in the notebook:**
   - Load and inspect the dataset.
   - Preprocess the data by handling missing values and encoding categorical variables.
   - Standardize the features.
   - Split the data into training and testing sets.
   - Train a logistic regression model.
   - Evaluate the model performance using confusion matrix and classification report.
   - Optionally, visualize the data using PCA.

## Results

The logistic regression model will classify individuals into age groups with an accuracy that can be evaluated through various metrics provided in the classification report. The PCA visualization helps in understanding the data distribution in a 2D space.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any feature additions, bug fixes, or improvements.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
