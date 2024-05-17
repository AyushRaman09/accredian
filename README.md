## CONCLUSION
<br>The Decision Tree model utilized in this analysis showcases an impressive accuracy of 99.92% and precision of around 70%. However, in fraud detection scenarios, precision holds paramount importance. We prioritize correctly identifying fraudulent transactions over correctly predicting legitimate ones. Failure to achieve high precision could result in innocent individuals being flagged as fraudulent or actual fraud cases slipping through undetected.


<br>The rationale behind opting for Decision Trees, despite the availability of other algorithms, stems from the nature of the dataset, which is highly imbalanced with a vast majority of legitimate transactions compared to a small fraction of fraudulent ones (99.87% to 0.13%). Decision Trees offer a straightforward approach to understanding such data due to their binary decision-making process.


<br>While alternative models like XGBoost, Bagging, Artificial Neural Networks (ANN), and Logistic Regression may yield impressive accuracy rates, they often fall short in achieving satisfactory precision and recall values. Thus, the Decision Tree model stands out as a favorable choice, emphasizing precision in identifying fraudulent activities while maintaining simplicity and interpretability.
