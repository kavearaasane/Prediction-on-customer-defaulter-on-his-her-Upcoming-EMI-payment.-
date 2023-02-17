# Prediction-on-customer-defaulter-on-his-her-Upcoming-EMI-payment.-
<h1>Table of Contents</h1>
<li><a href="#overview">Overview</a></li>
<li><a href="#moti">Motivation</li>
<li><a href="#tech">Technical aspects</li>
<li><a href="#inst">Installation</li>
<li><a href="#dir"> Directory tree </h>
<li><a href="#to">To do</li>
<li><a href="#tech">Technologies Used</li>
<li><a href="dep">Deployment </li>
<li><a href="#credit">Credits</li>
<h id="#overview"><b>OVERVIEW</h></b>
<p id="overview">
Prediction of customer defaulting on upcoming EMI payment involves using data analytics and machine learning techniques to analyze customer data and predict the likelihood of the customer defaulting on their loan payment.
This type of analysis is commonly used in the banking and financial sector to assess the creditworthiness of borrowers and to minimize the risk of default.
 </p>
<h id="#moti"><b>Motivation</b></h>
<p id="moti">As a business, it is essential to ensure timely payment of EMIs to maintain financial stability and credibility. The ability to predict customer defaulters on upcoming EMI payments can help businesses take proactive measures to prevent financial losses.By using data analytics and machine learning techniques, businesses can analyze customer behavior patterns and identify potential defaulters
</p>
<h  id="#tech"> <b> Technical aspects</b></h>
<p id="tech"> This project is divided into three parts :<br>
       <br> 1.Cleaning up the data.
       <br> 2.Choose an appropriate algorithm such as logistic regression, decision trees, or random forest for classification.<br>
            3.Model training to predict customer default
 </p>
<h id="#inst"><b> Installation </b></h>
<p id="inst">The Code is written in Python 3.7. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip.</p>
<pre>pip install -r requirements.txt</pre>
<h id="#dir"><b> Directory Tree </b> </h>
<p id="dir"><code>├── app 
│&nbsp;&nbsp; ├── __init__.py

│&nbsp;&nbsp; ├── main.py
│&nbsp;&nbsp; ├── model
│&nbsp;&nbsp; ├── static
│&nbsp;&nbsp; └── templates
├── config
│&nbsp;&nbsp; ├── __init__.py
├── processing
│&nbsp;&nbsp; ├── __init__.py
├── requirements.txt
├── runtime.txt
├── LICENSE
├── Procfile
├── README.md
└── wsgi.py
</code></p>
<h id="#to"><b> To Do </b></h>
<p id="to">1.Data collection: Collect data on past customer loan repayment behavior, including loan amount, duration, interest rate, and repayment history.<br>
2.Data cleaning: Clean the data and remove any irrelevant or missing information.<br>
3.Feature engineering: Create new features such as average payment delay, loan amount to income ratio, and credit score.<br>
4.Model selection: Choose an appropriate algorithm such as logistic regression, decision trees, or random forest for classification.<br>
5.Model training: Train the model using historical data to predict customer default.<br>
6.Model evaluation: Evaluate the model's performance using metrics such as accuracy, precision, recall, and F1 score.<br>
7.Predict customer default: Use the model to predict customer default for upcoming EMI payments. 
<br>
</p>
<h id="#tech"><b>Technologies Used</b></h>
<p id="tech">
<img src=https://user-images.githubusercontent.com/109030811/211580911-db9ff5ae-b7a5-4f3e-88b9-7eda2d7e4b43.png>
<br>
<br>
<img src=https://user-images.githubusercontent.com/109030811/219567622-297b4780-717c-49a1-a280-dd24900697fd.png>
 </p>
</h>
<br>
<h id="#dep"><b>Deployment </b></h> 
<p>
Gradio provides a convenient way to deploy machine learning models through its web-based user interface.
<br>
 <img src=https://user-images.githubusercontent.com/109030811/219566620-9f51d4b6-2437-46b8-adb3-4faa878fcfa2.png>
<p>
 </h>
 <h id="#credit"><b>Credits</b>
<p id="credit">
       <b>Kaggle</b>-This project wouldn't have been possible without this site. It saved my enormous amount of time while collecting the data.</p>
