# WEST NILE VIRUS OUTBREAK PREDICTIONS IN CHICAGO
Project on predicting West Nile Virus outbreaks in Chicago

---
## Summary
Project is based on a Kaggle competition where three years of mosquito trap data was provided and the goal was to determine when and where West Nile Virus would be detected.

Data was used to create probabilities that traps would test postive for west nile virus during certain parts of the year.

Our team took a five step approach to the model:

1. Identify the Problem
- Identify probable time periods when West Nile Outbreak could occur in traps
2. Obtain the Data
- Imbalanced Dataset
3. Clean the Data
- Merge Weather Data
4. Create Model
- Grid Search Base model: Log Reg or ADABoost
5. Evaluate Model
- ROC-AUC Score of 0.77
