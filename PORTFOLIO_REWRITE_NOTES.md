# Portfolio Rewrite Notes

## Recommended GitHub Repository Name

`brazilian-ecommerce-review-prediction`

## Recommended One-line Description

End-to-end analytics project predicting customer review satisfaction from Brazilian e-commerce logistics, payment, seller, customer, and geolocation data.

## Group-to-Portfolio Framing

Use transparent wording:

> This project was originally completed as a group academic assignment. This portfolio version organizes the files and narrative around the end-to-end analytics workflow, with emphasis on my data planning, feature engineering, modelling, and business interpretation contributions.

Avoid implying the whole group project was individual work. Instead, focus on the skills demonstrated and the parts you can confidently explain in an interview.

## Files Renamed for Portfolio

| Current File | Portfolio-friendly Name |
|---|---|
| `AIP Report (Group 8).pdf` | `brazilian_ecommerce_review_prediction_report.pdf` |
| `group_8_presentation.pdf` | `brazilian_ecommerce_review_prediction_presentation.pdf` |
| `Code/Step.4_Feature correlation.ipynb` | `Code/Step.4_Feature_Correlation.ipynb` |
| `Code/Step.5_Modelling and Evaluation.ipynb` | `Code/Step.5_Modelling_and_Evaluation.ipynb` |

Renaming notebooks should be done only after checking all internal file references.

## README Positioning

Lead with business value:

- Predict review satisfaction.
- Identify logistics and fulfillment drivers.
- Support proactive customer service and seller monitoring.

Then show technical depth:

- Multi-table data integration.
- Feature engineering.
- Imbalanced classification.
- Model comparison.

## Interview Talking Points

- Why review score was converted into a binary target.
- Why accuracy alone was not enough due to class imbalance.
- Why logistics-related features are business-actionable.
- Why class-weighted Random Forest was selected after tuning.
- What you would improve next with SHAP, dashboards, and cleaner pipelines.
