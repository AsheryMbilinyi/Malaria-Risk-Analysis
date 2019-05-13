# Analysis of Malaria Risk based on Housing Conditions in Sub-Saharan Africa

The goal of this work was to reveal a causal inference on how housing conditions in Sub-Saharan Africa contributes in Malaria vulnerability to the inhabitants.

## Data
Data was collected at Rusinga Island in Western Kenya which includes:-
 - Housing conditions
 - Demographic informations
 - Malaria Rapid Diagnostic Test(RDT) for each inhabitants of those houses

## Assumptions

Due to some challenges during data collection phase, the dataset resulted was of very low quality and therefore alot of assumptions has to be made for the dataset to used in the Machine Learning task of predicting malaria vulnerability. Some of those assumptions were

- Each house where considered vulnerable if it has more than one inhabitant who tested positive in RDT ( so the actual number of who are a positive or negative was ignored).
- The timing at when these RDT was tested and house features where recorded was completely ignored since there were recorded inaccurately or missing.

## Results

Despite the assumptions made , interesting results emerged especially in which are housing importance features that contributed in determining malaria vulnerability. The accuracy of classifiers was not high, 64 % achieved by XGBoost was the highest.
3 most important features were :

- Number of rooms for sleeping
- The presence of eaves in the house
- The location of the kitchen






