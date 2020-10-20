# DATA_ANALYST_Nutrition_Data_OC
Data Analysis project part of the DATA SCIENTIST curriculum of Openclassrooms

### by Jérôme d'Harveng


## Dataset

> For this analysis, we started from a food database (320772 lines,162 features) with there **nutritional specifications**.
> First, we had to familiarize ourselves with the subject, by reading some specialized articles. 
> This helped us orient the beginning of the study and eliminate a large number of redundant variables and understand
> the importance of the _nutrition grade_.

> **Questions Analysed**: After inspecting and cleaning this dataset, we focused on the nutritional advantages and disadvantages of different types of food.

## Limitations
> To run this analysis, some limitations are important to be mentioned as for example no Machine
Learning, Inferential Statistics or Statistical Tests were used.


## Summary of Findings

> After analysing the cleaned dataset, some observations could be made thanks to our exploration study.
> Throughout our analysis, we performed several visualizations to better understand the data and support our presentation to communicate our results. (cfr ppt)
>
> We could observe that most aliments have nutrition grade « d ». After the **feature
> selection**, we could focus on the **_energy level_**, the _fat level_, the _carbohydrates_ and the _salt level_. As **feature  engineering** (related to the information we found during pre-lecture on the subject), we added a ratio between the _saturated fats and the total fats_, in order to differentiate fats coming form oils, margarines and fresh cream.

>Additionnaly  most healthy aliments (with nutrition grades: a and b) have:
>- a lower level of energy [kJ/100g] (median < 448 kJ/100g)
>- a lower level of saturated fats (median < 20%)
>- a lower level of carbohydrates (median < 13g/100g)
>- a lower level of salt (median < 0.46 g/100g)

> Some other nutriments as _proteins_ aren't specific to a particular **nutrtion grade** 
