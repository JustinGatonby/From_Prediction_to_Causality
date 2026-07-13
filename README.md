# From Prediction to Causality: Choosing the Right Tool for Attribution and Driver Analysis

This presentation aims to clearly sepearte the tasks of prediction, model explanation, attribution and causal inference. Using the IBM Telco Churn dataset with hypothetical extensions, it shows how each task should be defined and which tools are best suited for it. 

The first task is prediction. Here the question is: “who is likely to churn?”. We use various classification models to show how to identify high-risk customers so that the business can prioritise retention activity. 

The second task is model explanation. Once we have a good prediction model, stakeholders naturally ask: “why did the model flag this customer?”. This is answered using methods, such as SHAP values, that explain the model’s prediction by showing which features pushed a customer’s predicted churn risk up or down. 

The third task is attribution. Here we ask: “which factors are related to churn, after accounting for other variables?”. For example, are month-to-month contracts, high charges or lack of tech support associated with churn? We consider logistic regression, GAMs and GAMMs for this task. 

The fourth task is causal effect estimation. This is the strongest and most demanding question. Here we ask: “what would happen if we changed something?”. For example, did a retention call actually reduce churn? To answer this, we employ causal thinking, not just predictive modelling, exploring DAGs, SEM, Bayesian SEM, and causal inference techniques such as propensity score matching and difference-in-differences. 

For each task, the key question is not “which method is most sophisticated?” but rather “what question are we answering, and does the data support that answer?”.
