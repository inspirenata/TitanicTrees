#ML_course_

Here will be homework for Machine Learning course at Yandex 

Home work #1 Titanic Data Task:

1. Upload titanic.csv. 

Draw diagrams (histograms / circular / ...), by which you can compare:
1) the probability of survival for men and women,
2) the probability of survival for passengers of different socio-economic classes (Pclass),
3) the cost of the ticket, depending on the social economic class.

Write what you have learned from these diagrams (for example, "for a Class 1 passenger, the probability of survival was XX% and was higher than that of a 2nd class passenger (YY%)", the more information you can extract from the diagrams, the better it will be)

2. Draw two predictors on one chart. Draw a histogram describing the average probability of surviving depending on sex and social status. For example, it can be a histogram with three column groups (social status division), in which the height of the column corresponds to the average number of survivors, and the color of the column indicates the sex of passengers. Again interpret the results (For example, what is the probability of surviving a woman from the first grade?). Write any two statements in the form of formulas (you need to remember what is the joint and / or conditional probability).

3. Clean the data as you see fit (do not forget about the insidious Sex variable, try not to delete the lines). Extra: Can you use more than 4 columns? For example, it seems that if the child was traveling with his brother / sister, they would not be separated, but they would be put together in a boat and they would survive ...

4. Divide the data into a training and a test sample (or use cross-validation). We will build a decision tree. You need to select a model parameter that, in your opinion, can affect the result, and choose the possible values for it. Comment on your choice. Changing the values of the parameter in the cycle, calculate for each case the exactness, completeness, F-measure (maybe other metrics?). Display the results on the diagram / -ax. Interpret the results. Draw the best tree.

5. Extra: Vary, use grid search.
 -Extra: build a ROC curve and describe its interpretation of what this graph says.

6. Do the same for the Random Forest model. Compare the results.
