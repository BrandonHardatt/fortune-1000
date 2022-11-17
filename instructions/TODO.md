# Final Project 

## Part 1 – Addressing instructor’s comments from Iteration 1 (10 marks)
The team must prepare a report and submit a PDF answering how comments made in iteration 1 were addressed in your second submission. 
- [ ] The document must contain the list of comments made by the instructor and the respective answer with the decisions made by the team. 

## Part 2 – Data scaling pre-assessment (27 marks)
The second part of your project will consist of exploring data scaling techniques. The following tasks must be performed in this part:
- [ ] Explore all data scaling techniques presented in the course and decide which one of them will be removed or kept in your experimental design. 
- [ ] You must create (or refer to previous) plots and/or statistical indicators to justify your decisions.
- [ ] As a way to condense your findings, you may plot the results, side by side, of the original and the data scaling techniques used.
- [ ] Make sure you discuss the figure in-depth enough to justify your decisions.

## Part 3 – Handling missing data and outliers (38 marks)
The third part of your project must advance your pre-processing strategy to handle the missing data and outliers selected in the Iteration 1 (remember that here you have at least two variables for each task, if you have more than that you must handle them as well). Besides, the techniques used in this part must also be combined with the techniques used in Part 2 of this iteration. To receive all marks in this part, you must:
- [ ] Decide a baseline strategy that will be used as a starting experiment where the use of all aforementioned strategies are likely to improve. A baseline strategy could be something as simple as a centrality measure (e.g., mean, median or mode) to replace missing values or upper and lower quartiles to replace outliers.
- [ ] You must create models using the two algorithms for classification or regression discussed in class (e.g., Linear or KNN). You should engineer an experiment where you will be able to decide the best combination Data scaling technique + (Classifier, Regressor) that will lead to a potential best result. Therefore, to assess results, you must rely on data that you know the ground truth. Remember that producing a single experimental result might not give you confidence to make a decision. 
- [ ] You must discuss why you chose the combination. 
- [ ] Don’t forget to justify which evaluation metric you will use to make such a decision. 
- [ ] The quality of your code will be essential to receive full marks in this experiment. 
- [ ] Make sure you optimize your code by generalizing your problem using functions to put your data in a proper pipeline of analysis.
- [ ] Finally, fill the missing data and replace the outliers using the decided (Classifier, Regressor + Data scaling technique). Make sure the rows are properly scaled before you forecast the values.