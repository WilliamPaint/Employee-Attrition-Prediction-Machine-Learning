<h1>Predicting Employee Attrition Using Machine Learning</h1>
<img width="769" height="445" alt="image" src="https://github.com/user-attachments/assets/ee20ff97-44d7-4b0a-b9b4-1bccb9bdaefc" />


<div style="margin:12px 0 18px 0;">
  <span style="background:#0f172a;color:#fff;padding:6px 10px;border-radius:6px;font-size:13px;font-weight:600;">
    Machine Learning
  </span>
  <span style="background:#1f2937;color:#fff;padding:6px 10px;border-radius:6px;font-size:13px;font-weight:600;margin-left:6px;">
    HR Analytics
  </span>
  <span style="background:#111827;color:#fff;padding:6px 10px;border-radius:6px;font-size:13px;font-weight:600;margin-left:6px;">
    Classification • Model Evaluation
  </span>
</div>

<hr/>

<div style="background:#f3f4f6;padding:8px 12px;border-left:5px solid #2563eb;margin:18px 0 10px 0;">
  <strong>Overview</strong>
</div>

<p>
  This project applies supervised machine learning techniques to predict employee attrition
  using the IBM HR Analytics dataset. The objective is not only to identify employees at
  higher risk of leaving, but also to uncover the workplace factors that drive voluntary
  turnover and translate model results into actionable HR strategies.
</p>

<p>
  Six classification models were trained, evaluated, and compared, with emphasis on
  handling class imbalance and balancing predictive performance with interpretability
  for real-world HR decision-making.
</p>

<div style="background:#f3f4f6;padding:8px 12px;border-left:5px solid #eab308;margin:18px 0 10px 0;">
  <strong>Data</strong>
</div>

<ul>
  <li>IBM HR Analytics Dataset</li>
  <li>1,470 employees and 35 variables</li>
  <li>Attrition rate: ~16% (highly imbalanced classification problem)</li>
</ul>

<div style="background:#f3f4f6;padding:8px 12px;border-left:5px solid #16a34a;margin:18px 0 10px 0;">
  <strong>Modeling Approach</strong>
</div>

<ul>
  <li>Logistic Regression (interpretable baseline)</li>
  <li>Decision Tree</li>
  <li>Random Forest</li>
  <li>Gradient Boosting</li>
  <li>Support Vector Machine (RBF)</li>
  <li>Neural Network (MLP)</li>
</ul>

<p>
  Models were evaluated using accuracy, precision, recall, F1-score, ROC AUC,
  confusion matrices, and ROC curves, with particular attention to minimizing false
  negatives (missed leavers).
</p>

<div style="background:#f3f4f6;padding:8px 12px;border-left:5px solid #db2777;margin:18px 0 10px 0;">
  <strong>Key Results</strong>
</div>

<ul>
  <li><strong>Best model:</strong> Logistic Regression</li>
  <li>Accuracy: ~88%</li>
  <li>Highest recall and ROC AUC (~0.82)</li>
  <li>Best balance between performance and interpretability</li>
</ul>

<p>
  Tree-based models and SVM achieved strong accuracy but missed many true attrition cases,
  while Logistic Regression provided more reliable detection of employees at risk.
</p>

<div style="background:#f3f4f6;padding:8px 12px;border-left:5px solid #22c55e;margin:18px 0 10px 0;">
  <strong>Key Drivers of Attrition</strong>
</div>

<ul>
  <li>Overtime and frequent business travel</li>
  <li>Limited career progression (years since last promotion)</li>
  <li>Job role and workload pressure</li>
  <li>Lower job and environment satisfaction</li>
</ul>

<div style="background:#f3f4f6;padding:8px 12px;border-left:5px solid #06b6d4;margin:18px 0 10px 0;">
  <strong>HR Recommendations</strong>
</div>

<ul>
  <li>Monitor and reduce excessive overtime exposure</li>
  <li>Strengthen career progression and promotion pathways</li>
  <li>Rotate or reduce frequent travel demands</li>
  <li>Improve engagement and satisfaction through feedback and recognition</li>
  <li>Provide structured support for early-career employees</li>
</ul>

<div style="background:#f3f4f6;padding:8px 12px;border-left:5px solid #7c3aed;margin:18px 0 10px 0;">
  <strong>Files</strong>
</div>

<ul>
  <li><code>/notebooks/</code> – Python code for preprocessing, modeling, and evaluation</li>
</ul>

