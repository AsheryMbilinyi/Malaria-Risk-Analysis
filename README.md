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

Despite the assumptions made , interesting results emerged especially in which are housing importance features that contributed in determining malaria vulnerability. The classifier's accuracies were not high, 64 % XGBoost was the highest.
The three most important features were as follows :

- Number of rooms for sleeping
- The presence of eaves in the house
- The location of the kitchen

The below pie chart shows the overall feature importancies

![alt text](https://github.com/AsheryMbilinyi/Analysis-of-Malaria-Risk-based-on-Housing-Conditions-in-Sub-Saharan-Africa/blob/master/features_importance.png)

## Discussion

The above features detected by a machine learning algorithm strongly correlate with the ground truth of malaria vulnerability with respect to the houses. For example, the higher the number of eaves the house have means the greater access mosquitoes have to enter the house especially at night. On the other hand, if kitchen is located inside the house mosquitoes faces difficulty due smoke produced by burning woods, while the kitchen outside the house favors mosquitoes.



