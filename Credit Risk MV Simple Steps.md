In consideration of both OSFI and Basel IV, in combination with updates from SR 26-2

Step 1: Evaluate Methodology on Definition of Default: 
  - How this was defined, whether it is comparable to OSFI requirements and whether the methodology chosen is reasonable for products. 
  - Consider fraudulent borrowers and withdrawals and the impact of the defaults
Step 2: Data quality requirement assessment:  
  - Does the development sample contain a representative range of economic conditions
  - Does the model use external data, and how they were used
  - Percentage of the missing data in each variable and impact on model 
Step 3: Margins of conservatism (MoC): consideration of uncertainties that may produce unestimated risks to the model; examples may include data uncertainty or regrade uncertainty 
Step 4: Model complexity and materiality
  - Complexity: what’s the statistical method chosen for the model, for example Logistic Regression vs. Random Forest
  - Materiality: how long the model existed and how often the model was maintained/assessed
Step 5: Assess testing done by Model Owner
  - Sensitivity Testing
  - Benchmarking:
    Actual default vs. Predicted Default model
    LRDR
    OOT
    External source: use similar business entities' DR to assess the level of our DR
Step 6: Replication from Model Validation and Testing
  - In-Sample testing and Out-of-Sample testing (backtesting)
  - Outcome analysis on any differences; may apply:
    HHI to measure concentration of the selected variables
    ANOVA or Kruskal-Wallis test 
    Monte-Carol simulation
    MSE
Step 7: Performance monitoring: with threshold set, and analysis and explanation of breaches
  - Realized Default Rate
  - AUC
  - PSI
