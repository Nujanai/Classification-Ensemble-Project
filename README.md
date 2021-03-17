# Classification-Ensemble-Project
Ian Lynch
TBANLT 560 – Winter

Project Two

In this Github repository you will find all the related documents for the Ensemble Classification experiment I ran. I used the breast cancer dataset that is available with R Studio.

I ran a total of 7 classification models on this dataset. The classification models that I used for this experiment were: SVM Tuning, Naïve Bayes, Neural Net, Decision Tree, Quadratic Discriminant Analysis, Regularized Discriminant Analysis & Random Forests.  

I collected the results for each classification model and combined them into a data frame. The data frame contained every record in the breast cancer data set and the results that each model had for each record.

I ran a function that selected the majority results for each record in the combined model result data frame. With that, I created a new data set with the majority results and checked the accuracy of the ensemble results against the actual records within the original breast cancer data set.

The final ensemble results hit a 97.95% accuracy! I would say that is quite the successful experiment!

One thing of note, The Random Forests model, was able to predict every single result in the breast cancer dataset, with a 100% accuracy!
