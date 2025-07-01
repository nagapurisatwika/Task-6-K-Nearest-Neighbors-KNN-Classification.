# Task-6-K-Nearest-Neighbors-KNN-Classification.
1. Dataset Chosen: I used the **Wine dataset** from `sklearn.datasets` which contains chemical analysis of wines grown in the same region in Italy — it has 3 wine types.

2. Libraries Used: Mostly `scikit-learn`, `pandas`, `matplotlib`, `seaborn`. PCA was used later for 2D plots.

3. Preprocessing: Standardized all the numeric features using `StandardScaler` so that distance calculations work correctly in KNN.

4. Splitting Data: Did an 80-20 split using `train_test_split`.

5. Model Training:Used `KNeighborsClassifier` with `k=3` to start. Then trained the model on the scaled features.

6. Evaluation:Checked accuracy, confusion matrix, and detailed classification report. Helped me understand how well KNN worked for multi-class data.
 
7. Experimenting with K: Tried different values of K from 1 to 20 and plotted an elbow curve to find the sweet spot.

8. Visualization (Bonus): Used PCA to reduce the dataset to 2 dimensions and plotted decision boundaries. This helped me "see" how KNN classified regions in 2D space.

9. Best K Value: Based on the lowest error rate, printed the best K to use.

10. What I Learned: Understood instance-based learning, Euclidean distance, and how K value affects bias/variance. Also learned how to visualize decision boundaries for better intuition.

