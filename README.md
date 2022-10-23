# titanic-survivial-prediction

Project Description 📄

❄️ Built a decision tree model for the famous Titanic dataset to
predict whether a passenger will survive the shipwreck or not.

##### Jupyter Notebook: (https://github.com/shiv0112/titanic-survivial-prediction/blob/master/notebooks/titanic-decision-tree.ipynb)

## Data:

Data name: Titanic Dataset

```
DATASET specs
NAME: titanic3
TYPE: Census
SIZE: 1309 Passengers, 14 Variables

DESCRIPTIVE ABSTRACT:
The titanic3 data frame describes the survival status of individual passengers on the
Titanic.
The titanic3 data frame does not contain information for the crew, but it does contain
actual and estimated ages for almost 80% of the passengers.

VARIABLE DESCRIPTIONS
Pclass Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
survival Survival (0 = No; 1 = Yes)
name Name
sex Sex
age Age
sibsp Number of Siblings/Spouses Aboard
parch Number of Parents/Children Aboard
ticket Ticket Number
fare Passenger Fare (British pound)
cabin Cabin
embarked Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

SPECIAL NOTES
Pclass is a proxy for socio-economic status (SES)
1st ~ Upper; 2nd ~ Middle; 3rd ~ Lower
Age is in Years; Fractional if Age less than One (1)
If the Age is estimated, it is in the form xx.5
Fare is in Pre-1970 British Pounds ()
Conversion Factors: 1 = 12s = 240d and 1s = 20d

```

I trained this model using Decision Tree:

#### The Accuracy of the model:

![Alt text](https://github.com/shiv0112/titanic-survivial-prediction/blob/master/screenshots/accuracy.png)

#### Roc AUC curve

![Alt text](https://github.com/shiv0112/titanic-survivial-prediction/blob/master/screenshots/roc.png)

#### The comparison of Actual value and predicted value by our model

![Alt text](https://github.com/shiv0112/titanic-survivial-prediction/blob/master/screenshots/compare.png)

### Index page of Website:

![Alt text](https://github.com/shiv0112/titanic-survivial-prediction/blob/master/screenshots/1.png)

### Data Input from user:

![Alt text](https://github.com/shiv0112/titanic-survivial-prediction/blob/master/screenshots/2.png)

## Finally prediction displayed:

![Alt text](https://github.com/shiv0112/titanic-survivial-prediction/blob/master/screenshots/final.png)

### What I learnt from this project:

-->Classification using Decision Tree

-->How we can use GridSearch CV to select best parameters for model

-->Dummy variable trap does not affect decision tree
