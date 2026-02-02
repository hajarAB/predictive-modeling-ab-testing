<h1>💳 Credit Scoring – Machine Learning Project</h1>

<h2>🎯 Objective</h2>
<p>
The goal of this project is to develop a machine learning model capable of predicting a customer's
creditworthiness (<b>good / bad credit</b>) based on financial and socio-demographic data, in a context
close to real-world banking applications.
</p>

<p>This project demonstrates my ability to:</p>
<ul>
  <li>Structure an end-to-end data science project</li>
  <li>Build clean and reusable machine learning pipelines</li>
  <li>Compare multiple models</li>
  <li>Handle class imbalance effectively</li>
  <li>Deploy a model through an interactive user interface</li>
</ul>

<h2>🧠 Business Problem</h2>
<p>
In the credit approval process, poor decisions can lead to:
</p>
<ul>
  <li><b>Financial losses</b> (false positives)</li>
  <li><b>Lost opportunities and customer dissatisfaction</b> (false negatives)</li>
</ul>
<p>
The objective is therefore to build a <b>robust, interpretable, and reliable model</b> that supports
decision-making rather than replacing it.
</p>

<h2>📊 Data</h2>
<ul>
  <li><b>Dataset:</b> German Credit Dataset</li>
  <li><b>Size:</b> 1,000 customers</li>
  <li><b>Features:</b> Numerical and categorical variables</li>
  <li><b>Target variable:</b>
    <ul>
      <li>1 → Creditworthy customer</li>
      <li>0 → Non-creditworthy customer</li>
    </ul>
  </li>
</ul>

<p>The dataset includes information such as:</p>
<ul>
  <li>Credit amount and duration</li>
  <li>Banking history</li>
  <li>Employment status</li>
  <li>Personal and demographic situation</li>
</ul>

<h2>🔍 Data Science Workflow</h2>

<h3>1️⃣ Exploratory Data Analysis</h3>
<ul>
  <li>Distribution analysis</li>
  <li>Class imbalance investigation</li>
  <li>Understanding business-related variables</li>
</ul>

<h3>2️⃣ Data Preprocessing</h3>
<ul>
  <li>Feature / target separation</li>
  <li>scikit-learn pipelines</li>
  <li>Standardization of numerical features</li>
  <li>One-Hot Encoding of categorical variables</li>
</ul>

<h3>3️⃣ Modeling</h3>
<p>Trained and compared models:</p>
<ul>
  <li>Logistic Regression (interpretable baseline)</li>
  <li>Random Forest</li>
  <li>Gradient Boosting</li>
  <li>Logistic Regression with SMOTE (class imbalance handling)</li>
</ul>

<h2>📈 Evaluation</h2>
<ul>
  <li>Accuracy</li>
  <li>Precision / Recall / F1-score</li>
  <li>Confusion matrices</li>
  <li>Performance comparison across models</li>
</ul>

<p>
👉 <b>Random Forest</b> was selected as the final model for its strong balance between performance and stability.
</p>

<h2>🔎 Interpretability</h2>
<ul>
  <li>Feature importance analysis</li>
  <li>Identification of key factors influencing credit decisions</li>
</ul>
<p>
The approach prioritizes <b>business understanding and interpretability</b> over raw performance alone.
</p>

<h2>🖥️ Deployment (Proof of Concept)</h2>
<ul>
  <li>Development of an interactive interface using <b>Gradio</b></li>
  <li>Simulation of customer credit scenarios</li>
  <li>Real-time predictions with probability scores</li>
</ul>

<p>
➡️ This deployment reflects an <b>industry-oriented Proof of Concept</b>.
</p>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li>Python</li>
  <li>pandas, numpy</li>
  <li>scikit-learn</li>
  <li>imbalanced-learn (SMOTE)</li>
  <li>matplotlib</li>
  <li>gradio</li>
</ul>

<h2>📷 Interface Preview</h2>
<p>
Below is a preview of the interactive Gradio interface used to simulate customer credit scenarios
and generate real-time predictions.
</p>

<img src="images/interface.png" alt="Credit Scoring Interface" width="800"/>
