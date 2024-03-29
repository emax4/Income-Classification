# Income-Classification
## Project Objective
The purpose of this project is to predict whether income exceeds $50K/yr based on census data



### Methods Used
* Data Visualization
* Inferential Statistics: t-Test, Chi-square Independence Test
* Machine Learning: Decision Tree, Random Forest, Logisitic Regression
* Predictive Modeling

### Libraries
* Pandas
* matplotlib
* seaborn
* urllib
* scikit-learn
* SciPy

### Data
Also known as "Adult" dataset. The data can be  found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/census+income).

Number of Instances: 48842
Number of Attributes: 14
Missing Values: ? (Yes)

**Continuous Attributes**
1. age:
2. education-num: number of education year
3. fnlwgt: final weight
4. capital-gain: 
5. capital-loss: 
6. hours-per-week:

**Categorical Attributes**

 7. workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, 		Without-pay, Never-worked.
 8. education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
 9. marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
 10. occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
 11. relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
 12. race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
 13. sex: Female, Male.
 14. native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

**Target**
>50K, <=50K.

### Notebook
[GitHub](https://github.com/emax4/Income-Classification/blob/master/Income.ipynb).

[nbviewer](https://nbviewer.jupyter.org/github/emax4/Income-Classification/blob/master/Income.ipynb).


### Model Accuracy
| Model  | Accuracy |
| ------------- | ------------- |
| Logistic Regression  | 82.6% |
| Decision Tree  | 85.3%  |
| Random Forest  | 86.3%  |
