# FUTURE_ML_02 – Support Ticket Classification

## Objective
Automatically classify customer support tickets and assign priority levels.

## Features
- Text preprocessing with TF-IDF
- Ticket category classification
- Priority tagging: high / medium / low
- Model evaluation using accuracy, precision, recall and F1-score
- Confusion-matrix visualization
- Prediction of new tickets
- Saved trained models

## Categories
Account Access, Delivery, Billing, Technical Issue, Returns

## Files
- `support_ticket_classification.ipynb` – complete notebook
- `support_tickets.csv` – synthetic demonstration dataset
- `ticket_category_model.pkl` – generated after running the notebook
- `ticket_priority_model.pkl` – generated after running the notebook
- `requirements.txt` – dependencies
- `README.md` – documentation

## Workflow
Load data → inspect/clean → train/test split → TF-IDF → Logistic Regression → evaluate → visualize → predict new tickets → save models.

## Dataset note
The included dataset is synthetic demonstration data created for this portfolio project; it is not real customer data.

## Run
Open the notebook in Google Colab or Jupyter and run all cells from top to bottom.
