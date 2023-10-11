Precision-Recall Curve:
To assess precision and recall, you can plot a Precision-Recall curve.

python
Copy code
from sklearn.metrics import precision_recall_curve
precision, recall, thresholds = precision_recall_curve(y_true, model.predict_proba(X_test)[:, 1])

plt.plot(recall, precision)
plt.xlabel('Recall')
plt.ylabel('Precision')
plt.show()

<!---
6382801957/6382801957 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
