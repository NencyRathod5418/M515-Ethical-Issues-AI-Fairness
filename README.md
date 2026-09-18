
# M515 Ethical Issues for AI – Fairness Analysis and Bias Mitigation

## Project Overview

This project investigates fairness and potential bias in a machine learning model developed using the UCI Bank Marketing dataset.

The objective is to predict whether a customer subscribes to a term deposit while evaluating whether model outcomes differ between two age groups:

* Younger customers (<40)
* Older customers (40+)

## Methodology

The analysis includes:

1. Problem formulation
2. Dataset understanding and preprocessing
3. Baseline machine learning model development
4. Baseline fairness assessment
5. Fairness mitigation using reweighting
6. Post-mitigation fairness evaluation
7. Association-rule mining
8. Association rules by age group
9. Critical evaluation and recommendations

## Fairness Measures

The fairness analysis considers:

* Selection Rate
* Demographic Parity Difference (DPD)
* Disparate Impact (DI)
* True Positive Rate (TPR)
* False Positive Rate (FPR)
* False Negative Rate (FNR)
* False Discovery Rate (FDR)
* False Omission Rate (FOR)

Predictive performance is evaluated using accuracy, precision, recall, F1-score, ROC-AUC, and the confusion matrix.

## Bias Mitigation

Reweighting is used as a preprocessing-based fairness mitigation technique. The baseline and mitigated models are evaluated on the same held-out test set to make the comparison interpretable.

## Association Rules

Association-rule mining is included as a complementary descriptive analysis. Support, confidence, and lift are used to identify patterns associated with term-deposit subscription.

The association rules are not interpreted as causal relationships and are not used as a replacement for the classifier fairness audit.

## Dataset

The analysis uses the UCI Bank Marketing dataset:

Moro, S., Cortez, P. and Rita, P. (2014) *Bank Marketing*. UCI Machine Learning Repository.

## Academic Context

Module: M515 Ethical Issues for AI

Institution: GISMA University of Applied Sciences

This repository contains the computational work prepared for the M515 Ethical Issues for AI retake assignment.
