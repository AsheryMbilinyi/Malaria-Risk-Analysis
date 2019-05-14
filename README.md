# Analysis of Malaria Risk based on Housing Conditions in Sub-Saharan Africa

The goal of this work was to reveal a causal inference on how housing conditions contribute to Malaria vulnerability to the inhabitants in Sub-Saharan Africa.

## Data
Data was collected at Rusinga Island in Western Kenya which includes:-
 - Housing conditions
 - Demographic information
 - Malaria Rapid Diagnostic Test(RDT) for each inhabitant of those houses

## Assumptions

Due to some challenges during the data collection phase, the dataset resulted was of very low quality and therefore a lot of assumptions had to be made for the dataset to be used in Machine Learning task of predicting malaria vulnerability. Some of those assumptions were:

Each house was considered vulnerable if it has more than one inhabitant who tested positive in RDT ( so the actual number of who are positive or negative was ignored).
- The timing at when RDT were tested and house features where recorded were completely ignored since there were recorded inconsistently or missing some information.

## Results

Despite the assumptions made, interesting results emerged especially in which are housing important features that contribute in determining malaria vulnerability. The classifier's accuracies were not high though, 64 % by XGBoost was the highest.

The three most important features in descending order were:-

- Number of rooms for sleeping
- The presence of eaves in the house
- The location of the kitchen

The below pie chart shows the overall feature importancies

![alt text](https://github.com/AsheryMbilinyi/Analysis-of-Malaria-Risk-based-on-Housing-Conditions-in-Sub-Saharan-Africa/blob/master/features_importance.png)

## Discussion

The above features detected by a machine learning algorithm strongly correlate with the ground truth of malaria vulnerability with respect to houses. For example, the higher the number of eaves the house have means the greater access mosquitoes have to enter the house, especially at night. On the other hand, if the kitchen is located inside the house, mosquitoes face difficulty due to smoke produced by burning woods, while the kitchen outside the house favors mosquitoes.



