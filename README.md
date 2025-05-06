# **🧠 Support Vector Machines (SVM)**

### 📋 Overview

> Load and preprocess a classification dataset .

> Reduce the data to two features for easy visualization.

> Train a Support Vector Machine (SVM) classifier.

> Tune hyperparameters C and gamma using GridSearchCV.

> Visualize the decision boundary in 2D space.

### ⚙️ Steps Involved
**1. Import Libraries**
* Essential Python libraries such as pandas, numpy, matplotlib, sklearn, etc., are imported for data handling, modeling, and visualization.

**2. Data Loading**
* Dataset is loaded into a DataFrame, and features/labels are separated.

**3. Feature Selection**
* Two features are selected to allow 2D plotting of decision boundaries.

**4. Data Scaling**
* StandardScaler is applied to normalize features before training.

**5. Train-Test Split**
* Data is split into training and testing sets using train_test_split.

**6. Hyperparameter Tuning**
* Grid Search (GridSearchCV) is used to find the best values of:

**7. Model Training**
* The best C and gamma found from grid search are used to retrain the SVM model.

**8. Decision Boundary Plotting**
* A mesh grid is created and the trained model is used to predict over this grid.
* To fix plotting errors, string labels are encoded using LabelEncoder.

### 📊 Output
* Best hyperparameters

* Accuracy of the model

* A 2D contour plot showing decision boundaries between classes
