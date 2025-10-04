# Mobile Phone Pricing ML Project | from Unified Mentors
## Overview

<span class="line">This project aimed to explore and predict the price range of mobile phones based on their technical specifications and features using the provided `dataset.csv`. The dataset, obtained from a Unified Mentors internship, contains 2000 entries and 21 features, including the target variable `price_range`, which categorizes phones into four distinct price brackets.</span>
<span class="line">The initial phase involved Exploratory Data Analysis (EDA) to understand the dataset's structure, identify potential issues, and gain insights into the relationships between features and the target variable. The dataset was found to be clean, with no missing or duplicated values, which simplified the preprocessing steps.</span>
<span class="line">A significant part of the EDA involved creating meaningful visualizations to explore various aspects of the data. These charts helped in understanding the distribution of individual features and their correlations, revealing how the presence or absence of these features influences the price bracket.</span>
<span class="line">Following the EDA, the data was prepared for Machine Learning (ML) by splitting it into training and testing sets. The features were scaled using `StandardScaler` to ensure that all features contribute equally to the model training process, preventing features with larger scales from dominating those with smaller scales.</span>
<span class="line">The ML phase involved training and evaluating different classification models: Each model was trained on the scaled training data and then evaluated on the unseen test data using metrics.</span>
<span class="line">The best model, was then saved using `joblib` or `pickle` for future use, allowing for easy deployment and prediction on new, unseen data without retraining the model. The saved model was loaded and tested on the same test set to confirm its performance.</span>
<span class="line">In summary, this project successfully performed EDA to understand the mobile phone dataset and built several ML models to predict the price range. The insights gained from the EDA, particularly the strong correlation between RAM and price range, along with the high accuracy of the chosen model, provide a solid foundation for understanding the factors influencing mobile phone pricing and for making accurate price range predictions. Further work could involve exploring feature importance from the best model or trying more advanced ensemble techniques to potentially achieve even higher prediction accuracy.</span>

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset includes features such as battery power, RAM, screen size, camera specifications, and more. Each record is labeled with a price range (0: Low, 1: Medium, 2: High, 3: Very High).


## Usage

Open and run the `mobilePhonePricing_ML.ipynb` notebook in Jupyter Notebook or JupyterLab:

```bash
jupyter notebook mobilePhonePricing_ML.ipynb
```

Follow the notebook cells to preprocess data, train models, and evaluate results.

## Project Structure

```
.
├── Dataset.csv
├── mobilePhonePricing_ML.ipynb
├── README.md
└── requirements.txt
```

## Results

- Data preprocessing and feature engineering
- Model training using algorithms like Logistic Regression, Random Forest, and SVM
- Evaluation using accuracy, confusion matrix, and classification report
- Best model achieved accuracy of over 90% on the test set

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

## License

This project is licensed under the MIT License.