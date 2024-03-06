# Feature Optimization and Model Accuracy Using Particle-Swarm-Optimization (PSO)

In this project, Particle Swarm Optimization (PSO) was applied to a dataset containing approximately 17,000 data points. Basically Particle Swarm Optimization is an optimization algorithm inspired by the collective behavior of birds and fish. In the context of feature selection, PSO is employed to identify a subset of features that maximizes the performance of a machine learning model. Each particle represents a potential feature subset, and the optimization process refines these subsets iteratively. The key observations are outlined below:

## Random Forest

- When trained with all 17,000 features, the accuracy is **88%**.
- Using PSO to select 1,093 features, the accuracy increased to **93%**.

## Support Vector Machine (SVM)

- Training with 17,000 features initially produced a **38% accuracy**.
- Remarkably, using PSO to select 1,093 features resulted in a significant accuracy boost to **98%**.


## Data Privacy Note:
These findings emphasize the importance of feature optimization in enhancing model performance. The dataset used in this project is **not open source** and is kept private. Due to privacy concerns or licensing restrictions, the dataset is not available for public access. The results and insights derived from the analysis are shared here, focusing on the methodology and the impact of feature optimization techniques on model accuracy.

If you have any specific requirements or inquiries regarding the dataset, feel free to contact me at [syedaffan.dev@gmail.com].

Thank you for your understanding.
