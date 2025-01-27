# Prediction of Breast cancer using data collected from anthropometric measurements and blood analysis indicators.

The project's main deliverable consists of two parts - an Exploratory Data Analysis and Machine Learning report. 
The data is derived from an open-access journal website for cancer research (https://www.biomedcentral.com/).

With a total of 9 feature variables (Age, BMI, Glucose, Insulin, Resistin, Adiponectin, MCP, HOMA),the goal is to predict if the patient has Breast cancer.

The aforementioned blood analysis indicators, when combined with age and BMI, are considered to deliver highly accurate predictions by highlighting metabolic and inflammatory imbalances. Elevated glucose and insulin levels, along with a high HOMA index, often indicate insulin resistance, a known contributor to cancer progression. Resistin and MCP-1, markers of inflammation, have been associated with tumor growth and metastasis, while low adiponectin levels correlate with increased cancer risk due to reduced anti-inflammatory effects. Studies show that integrating these biomarkers with age—a key risk factor—and BMI, which impacts hormone regulation, significantly enhances diagnostic models.

To start the analysis, data quality and distribution are examined. That is followed by exploring the categorical data and performing basic cluster analysis to determine whether an unsupervised Machine learning algorithm can be applied to predict results.
As assumed, the Machine Learning part focuses on the application of supervised learning algorithms (Logistic regression and Support Vector Machines) from sklearn Python library as the target label is present for each observation.
More on the process and results can be seen in https://github.com/gabriela0099/Breast-cancer-prediction/blob/main/Breast%20cancer%20prediction%20report.pdf.

