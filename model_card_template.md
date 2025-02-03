# Model Card

For additional information see the Model Card paper: https://arxiv.org/pdf/1810.03993.pdf

## Model Details

- Developer: Nicole Paul
- Model Date: 02/03/2025
- Model version: v1.0
- Model type: RandomForest Classifier

## Intended Use

Predict whether income exceeds $50K/yr based on census data.

Variables considered are:
- Age
- Education level
- Marital status
- Occupation
- Race
- Sex

## Training Data

Training data contains 80% of the original dataset.

## Evaluation Data

Evaluation data contains 20% of the original dataset.

## Metrics
- Precision: 0.7977
- Recall: 0.5292
- F1: 0.06363

## Ethical Considerations

- Potential for historical biases (consider minorities and women)
- Sensitive data: Anonymization is a good practice for this kind of data

## Caveats and Recommendations

Ensure data results are being used in a productive and unbiased manner.

Recommendation to consider new or other features to improve accuracy.