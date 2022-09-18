<p align="center">
  
</p>

# ML-Sessions-at-NTL-AP
---
# Day-2 (Topics Covered):
  1. Limitations on K-NN
  2. KD-Tree
  3. Logistic Regression
     * Geometric intutions
     * Sigmoid Function
     * Optimal equation of Logistic Regression
  4. Linear Regression
     * Geometric Intutions
     * Optimal equation of Linear Regressiom
---
[Interview questions on Logistic regression](https://github.com/Amrit-Kumar-Singha/ML-Sessions-at-NTL-AP/blob/main/session2/Logistic%20Regression.docx)

---

Code snippet of Logistic regression
'''python
from sklearn.grid_search import GridSearchCV
from sklearn.linear_model import LogisticRegression

model = GridSearchCV(LogisticRegression(), tuned_parameters, scoring = 'f1', cv=5)
model.fit(X_train, y_train)
'''

