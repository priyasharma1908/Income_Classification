# Income Classification

**The data contains number of people in column (fnlwgt) belonging to various segments described below**

1. age: the age of an individual: Integer greater than 0
   
2. workclass: a general term to represent the employment status of an individual: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.   

3. fnlwgt: final weight. In other words, this is the number of people the census believes the entry represents: Integer greater than 0    

4. education: the highest level of education achieved by an individual: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-cdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.    

5. education num: the highest level of education achieved in numerical form: Integer greater than 0

6. marital status: marital status of an individual. Married | civ spouse corresponds to a civilian spouse | Married AF spouse is a spouse in the Armed Forces: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.

7. occupation: the general type of occupation of an individual: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

8. relationship: represents what this individual is relative to others. For example an individual could be a Husband. Each entry only has one relationship attribute and is somewhat redundant with marital status. We might not make use of this attribute: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.

9. race: Descriptions of an individual’s race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black. 

10. sex: the biological sex of the individual: Male, Female 

11. capital gain: capital gains for an individual: Integer greater than or equal to 0  

12. capital loss: capital loss for an individual: Integer greater than or equal to 0  

13. hours per week: the hours an individual has reported to work per week: continuous 

14. country of origin for an individual: United¬States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican¬Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad &Tobago, Peru, Hong, Holand¬Netherlands. 

15. the label: whether or not an individual makes more than USD 50,000 annually: <=50k, >50k