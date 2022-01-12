# Bank_marketing_campaign_exploration_and_visualisation
Data exploration and visualization project on bank_marketing_campaign dataset using python
Data Exploration and Visualization Project on Bank Marketing Campaign using Python 
<p> By Yogesh Sachdeva, Ayushi Arora and Kriti Suri </p>
INTRODUCTION 
The data is related with direct marketing campaigns of a banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).

Objectives of the Project 
1) To explore the dataset for understanding the variables

2) To perform the data cleaning

3) To do the Data Visualization

4) Conclusions
5) <h2> Dataset Information </h2>

**Ai. bank client data:  <br>

1 - age: (numeric) <br>
2 - job: type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown') <br> 
3 - marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)  <br> 
4 - education: (categorical: primary, secondary, tertiary and unknown)  <br>
5 - default: has credit in default? (categorical: 'no','yes','unknown')  <br>
6 - housing: has housing loan? (categorical: 'no','yes','unknown')  <br>
7 - loan: has personal loan? (categorical: 'no','yes','unknown')  <br>
8 - balance: Balance of the individual.  <br>

**Aii. Related with the last contact of the current campaign:  <br>

8 - contact: contact communication type (categorical: 'cellular','telephone')  <br>
9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')  <br>
10 - day: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')  <br>
11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.  <br>

**Aiii. other attributes:  <br>

12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact) <br> 
13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)  <br>
14 - previous: number of contacts performed before this campaign and for this client (numeric)  <br>
15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')  <br>

**Output variable (desired target):  <br>
21 - y - has the client subscribed a term deposit? (binary: 'yes','no')  <br>
