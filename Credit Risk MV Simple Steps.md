In consideration of both OSFI and Basel IV, in combination with updates from SR 26-2

Step 1: Evaluate Methodology on Definition of Default: 
  - How this was defined, what methodology was used for BRR (borrower risk rating) and DR estimation
  - Whether the methodology is comparable to OSFI requirements and whether it is reasonable for products. 
  - Consider fraudulent borrowers and withdrawals and the impact of the defaults
    
Step 2: Data quality requirement assessment:  
  - Does the development sample contain a representative range of economic conditions
  - Does the model use external data, and how were they used
  - Percentage of the missing data in each variable and impact on model

Step 3: Margins of conservatism (MoC): consideration of uncertainties that may produce unestimated risks to the model; examples may include data uncertainty or regrade uncertainty 

Step 4: Model complexity and materiality
  - Complexity: what’s the statistical method chosen for the model, for example, Logistic Regression vs. Random Forest
  - Materiality: how long the model existed and how often the model was maintained/assessed
    
Step 5: Assess testing done by Model Owner
  - Sensitivity Testing:
    Validate the rationale for creating scenarios to mimic the matrix that potentially covers the unavailable historical data (eg. OOT), and consider if the selected scenarios are appropriate
  - Stress testing: 
    Similarly, validate the rationale for the impact on the PD curve with extreme changes, and consider if the selected scenarios are appropriate
  - Outcome Analysis Assessment:
    Actual default vs. Predicted Default model, LRDR assessment 
  - Benchmarking:
    a. External source: average PDs on comparable business  
    b. Assess alternative modelling approach, eg. one exponential function vs. two exponential functions PD
    
Step 6: Replication from Model Validation and Testing
  - Replication: cohort population, LRDR, MoC, Regrade Matrix, PD curve, model performance
  - Testing:
    a. IF the Sensitivity Testing and Stress Testing were not conducted, consider conducting these tests with a risk-based approach 
    b. In-Sample testing and Out-of-Sample testing (backtesting)
    c. Outcome analysis on any differences. The following may apply:
    	HHI to measure rating concentration of the selected variables
   		Monte-Carol simulation to provide upper and lower bounds on proposed PDs
    	Recent period calibration test
    
Step 7: Performance monitoring: with threshold set, and analysis and explanation of breaches, inlcuding Realized Default Rate, AUC, and PSI
