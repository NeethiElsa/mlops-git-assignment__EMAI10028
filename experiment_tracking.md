## Manual Experiment Tracking Table

| Experiment ID | Model Type     | Hyperparameters | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUC Score | 
|--------------------|---------------------|------------------------|----------------------------|-------------------------|----------------------|--------------|---------------|
| EXP-01| Decision Tree classifier    | default | Done(Removing the NA values,Scaling) | All features selected except year.| 70/30 | 0.84 | 0.89 | 
| EXP-02| Decision Tree classifier    | random_state=42,criterion="entropy",max_depth=6,min_samples_split=20,min_samples_leaf=10| Done(Removing the NA values,Scaling) | All features selected except year.| 80/20| 0.84 | 0.92 | 