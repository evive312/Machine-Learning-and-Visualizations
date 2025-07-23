<h1>Electric Vehicles and Power Outages: Analyzing Correlation and Potential Impact on Infrastructure</h1>

<h2>Description</h2>
This data science project investigates the relationship between electric vehicle registrations, power outage metrics (SAIDI and SAIFI), and political party affiliation across U.S. states from 2016 to 2023. The workflow includes:
<ol>
  <li>Cleaning and merging EV registration and power outage datasets.</li>
  <li>Augmenting with predictors: state nameplate capacity, NERC regional entities, and political affiliation.</li>
  <li>Exploratory visualizations comparing trends in red vs. blue states.</li>
  <li>Building and evaluating binary classification models (Logistic Regression, Random Forest, and various SVM kernels) to predict increases in power outages.</li>
</ol>


<h2>Languages and Libraries Used</h2>
<ul>
  <li><b>Python 3.x</b></li>
  <li><b>pandas</b> (data manipulation)</li>
  <li><b>matplotlib</b>, <b>seaborn</b>, <b>plotly</b> (visualization)</li>
  <li><b>scikit‑learn</b> (machine learning)</li>
</ul>


<h2>Environment Used</h2>
<ul>
  <li><b>Jupyter Notebook</b> (analysis and visualization)</li>
  <li><b>Ubuntu 22.04 / Python 3.9+</b></li>
  <li><b>Excel</b> (initial data cleaning)</li>
</ul>


<h2>Program walk-through:</h2>

  <b>Data Cleaning for EV Registration Dataset</b><br/>
  <img src="https://i.imgur.com/QaBMWQ7.png" height="80%" width="80%" alt="Data Cleaning for EV Registration Dataset"/>
  <br/><br/>
 
  <b>Total SAIDI (2016–2023) by State with Political Leaning</b><br/>
  <img src="https://i.imgur.com/N5OGYOy.png" height="80%" width="80%" alt="SAIDI Analysis Code and Bar Graph"/>
  <br/><br/>

  <b>Average EV Registrations in Red vs. Blue States (2016 vs 2023, Excl. California)
  </b><br/>
  <img src="https://i.imgur.com/WvoGEAm.png" height="80%" width="80%" alt="EV Registration Analysis Code and Plot"/>
  <br/><br/>

  <b>Data Cleaning for Power Outage Dataset</b><br/>
  <img src="https://i.imgur.com/V5rPA7e.png" height="80%" width="80%" alt="Data Cleaning for Outage Dataset"/>
  <br/><br/>

  <b>Machine Learning Model Evaluation Pipeline</b><br/>
  <img src="https://i.imgur.com/yGQDrFI.png" height="80%" width="80%" alt="SAIDI Model Evaluator Code"/>
