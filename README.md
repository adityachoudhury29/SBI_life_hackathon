# AI-Driven Personalized Insurance Recommendation System

## Team Name
- **Losers?**

## Overview
This project was developed as part of the SBI Life Hackathon to create an **AI-driven personalized recommendation system** for insurance policies. Our solution aims to enhance customer experience and increase the propensity to purchase by offering **intelligent and tailored insurance recommendations**.

## Problem Statement
Customers often struggle to find the right insurance policy due to **generic recommendations** and a **lack of personalization**. Our AI-driven solution enhances **customer experience and retention** by leveraging **AI insights** to provide **tailored insurance suggestions**.

## Solution Approach
Our system utilizes **machine learning algorithms** to classify users based on their suitability for specific policies. The project currently employs:
- **Random Forest Classifier**: Used to classify users and recommend policies.
- **TabTransformer (Future Enhancement)**: To analyze structured transactional data for improved personalization.
- **BERT (Future Enhancement)**: To analyze customer interactions and behavior for deeper insights.

## Methodology
1. **Data Processing**: Cleaned and preprocessed insurance data.
2. **Feature Engineering**: Extracted meaningful insights from customer attributes.
3. **Model Training**: Implemented **Random Forest** for initial classification.
4. **Evaluation & Optimization**: Assessed model performance and planned improvements.
5. **Future Enhancements**: Integration of **TabTransformer** and **BERT** for deep personalization and behavioral analysis.

## Project Structure
```
SBI_life_hackathon/
│── SBI_Life_Losers_.ipynb  # Jupyter Notebook with implementation
│── modified_insurance_v2.csv  # Processed insurance dataset
│── modified_insurance_v3.csv  # Updated dataset version
└── README.md  # Project documentation
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/adityachoudhury29/SBI_life_hackathon.git
   ```
2. Navigate to the project folder:
   ```bash
   cd SBI_life_hackathon
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook SBI_Life_Losers_.ipynb
   ```
4. Run the notebook cells to execute the model.

## Future Plans
- **Integration of TabTransformer** for structured data analysis.
- **Implementation of BERT** for customer interaction analysis.
- **Deployment of the model** via a web-based recommendation system.

---
