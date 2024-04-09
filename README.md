# Financial Crisis Prediction Using Kaminsky Model

## Overview
This repository implements the Kaminsky model to predict financial crises by monitoring various economic indicators against specified thresholds. It employs machine learning techniques and statistical analysis to evaluate the predictive power of each indicator, aiming to identify early warnings of potential crises. The implementation is based on the insights and methodologies discussed by Graciela Kaminsky, Saul Lizondo, and Carmen M. Reinhart in their working paper "Leading Indicators of Currency Crises."

## Methodology
The core methodology involves:
- **Defining a financial crisis** based on sharp currency depreciations or significant declines in international reserves, using an exchange market pressure index.
- **Selecting indicators** such as international reserves, exports, imports, terms of trade, real exchange rate deviations, and more, based on their theoretical relevance and data availability.
- **Calculating signal thresholds** for each indicator to distinguish normal from abnormal levels, optimizing these thresholds to balance the risk of false alarms against missed crises.
- **Evaluating predictive performance** through precision, accuracy, recall, F1, and the specifically designed Kaminsky Score (SP), which measures the effectiveness of indicators in signaling crises.

## Implementation
The Python code provided includes functions for calculating the Kaminsky Score, evaluating model performance, determining optimal thresholds for crisis prediction, and generating predictive signals. It also showcases an application of the model to FISLAC data, illustrating the process of identifying early warnings for financial crises across different countries and variables.

## Usage
To use this model, follow the steps outlined in the code comments to input your data, specify the prediction window, and select the economic indicators of interest. The model will then calculate the optimal thresholds for each indicator and evaluate their predictive performance.

## Contributions
Contributions to improve the model's accuracy or extend its functionality are welcome. Please refer to the issues section for current tasks or submit your suggestions via pull requests.

### Based on
This model and the methodologies employed within this repository are based on the findings and discussions presented in the paper: "Leading Indicators of Currency Crises" by Graciela Kaminsky, Saul Lizondo, and Carmen M. Reinhart, POLICY RESEARCH WORKING PAPER 1852. The paper discusses the effectiveness of various economic indicators in predicting currency crises and provides a framework for the analysis. For further details, refer to the [full paper](https://documents1.worldbank.org/curated/zh/906771468766484527/129529322_20041117161108/additional/multi-page.pdf).
