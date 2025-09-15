
# AI-Driven Predictive Maintenance

## Project Overview
This project presents an end-to-end machine learning solution for **predictive maintenance** in a manufacturing environment. The goal is to proactively identify potential machine failures using sensor data, thereby reducing costly downtime and optimizing maintenance schedules. This repository contains the full code for data preprocessing, model training, and performance evaluation.

## Key Features
- **End-to-End ML Pipeline:** A structured workflow covering data loading, cleaning, feature engineering, and model training.
- **Feature Engineering:** Creation of a new, insightful `Power` feature from rotational speed and torque data.
- **Imbalanced Data Handling:** Implemented a robust strategy using `class_weight='balanced'` to effectively handle the rarity of machine failures.
- **Model Selection:** Utilized a **Random Forest Classifier**, a powerful and interpretable algorithm well-suited for this classification task.
- **Comprehensive Evaluation:** Performance is measured using key metrics like the **ROC-AUC curve** and **Classification Report**, providing a clear understanding of the model's predictive power.

## Repository Structure
```

.
├── predictive-maintenance-ai4i.ipynb  \# The main Jupyter Notebook with all the code
└── README.md                         \# This file

````

## Dataset
The project uses a publicly available dataset that simulates a real-world manufacturing process. The dataset includes sensor readings such as temperature, rotational speed, torque, and tool wear, with a binary target variable indicating machine failure.

## Getting Started

### Prerequisites
To run this notebook, you need to have the following Python libraries installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install them using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
````

### Usage

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)[Your_Username]/predictive-maintenance-ai4i.git
    cd predictive-maintenance-ai4i
    ```
2.  **Download the Dataset:**
      - Download the `ai4i2020.csv` file from the [Kaggle Predictive Maintenance Dataset](https://www.kaggle.com/datasets/stephanmatzka/predictive-maintenance-dataset-ai4i-2020) page.
      - Place the CSV file in the root directory of the cloned repository.
3.  **Run the Notebook:**
      - Open the `predictive-maintenance-ai4i.ipynb` notebook in Jupyter or a similar environment.
      - Run all the cells in the notebook to reproduce the results and explore the model.

## Results

The model successfully identifies potential machine failures with a high degree of confidence. The ROC-AUC score and other metrics confirm the model's strong performance, demonstrating its effectiveness as a tool for proactive maintenance and operational efficiency.

## Author

  - **[Your Name]** - [Your LinkedIn Profile Link]
  - [Your GitHub Profile Link]

## License

This project is open-source and available under the MIT License.

```
```
