# Multi-Target Regression Meta-Model

A machine learning project focused on Multi-Target Regression (MTR) using ensemble learning and hierarchical clustering techniques to improve prediction accuracy across multiple dependent target variables.

## Abstract

Multi-Target Regression (MTR) refers to prediction of multiple target variables at the output end. Target variables may be mutually dependent and associated with each other. Each feature is dependent upon multiple targets and vice versa. Some target variables are similar due to their features being mutually related.

To reduce overfitting during the testing phase and improve prediction performance, an ensemble-based MTR Meta-Model was developed and evaluated on multiple multi-target datasets.

The proposed approach consists of:

<ul>
  <li>Determining correlated features using Recursive Feature Elimination (RFE)</li>
    <li>Dividing multi-target datasets into hierarchical clusters and trees using the C4.5 algorithm</li>
    <li>Extracting target-specific features</li>
    <li>Applying ensemble learning techniques including:
     <ul><li>Random Forest Regressor</li>
    <li>Histogram Gradient Boosting Regressor</li>
  </ul>
  </ul>

  Additionally, CART and C4.5 boosting algorithms were compared, and both produced similar error rates.

## Features
<ul>
  <li>Multi-target regression framework</li>
<li>Recursive Feature Elimination (RFE)</li>
<li>Hierarchical clustering of targets</li>
<li>C4.5 decision tree integration</li>
<li>Ensemble learning methods</li>
<li>Reduced overfitting</li>
<li>Performance evaluation using aRRMSE</li>
  </ul>

  ## Technologies Used
<ul>
  <li>Python</li>
<li>Scikit-learn</li>
<li>NumPy</li>
<li>Pandas</li>
<li>Random Forest Regressor</li>
<li>Histogram Gradient Boosting Regressor</li>
<li>C4.5 Decision Tree Algorithm</li>
 </ul>

## Workflow
<ol>
  <li>Load multi-target datasets</li>
<li>Perform feature selection using RFE</li>
<li>Build hierarchical clusters using C4.5</li>
<li>Extract target-specific features</li>
<li>Train ensemble regressors</li>
Evaluate model performance using aRRMSE</li>
</ol>

## Datasets
The project was evaluated on:
<ul>
  <li>OES97 Dataset</li>
<li>OES10 Dataset</li>
<li></li>
  <li></li>
   </ul>

## Usage

Run the main training script:
python main.py
