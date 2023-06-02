# Erdos-2023_Project
A classification project trying to predict whether a direct marketing campaign of a Portuguese bank will result in a deposit. 

## Team Members:

1. Drew D. Ash, Assistant Professor, Albion College, Dash@albion.edu
2. Laura Brade, Assistant Professor, Albion College, Lbrade@albion.edu
3. Jamie Kimble, Graduate Student, Michigan State University, Kimblej2@msu.edu
4. Erdos Institute, Data Science Bootcamp 2023, Team 11

## Data:

Our dataset is from the UCI Machine Learning webpage: https://archive.ics.uci.edu/ml/datasets/Bank+Marketing


### Column Representation:
#### Bank client data
- **age:** numeric
- **job:** type of job ( takes values type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
- **marital:** marital status (takes values 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
- **education:** level of education (takes values 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
- **default:** has credit in default? (takes values 'no','yes','unknown')
- **houseing:** has housing loan? (takes values 'no','yes','unknown')
- **loan:** has personal loan? (takes values 'no','yes','unknown')
#### Related with the last contact of the current campaign:

- **contact:** contact communication type (takes values 'cellular','telephone')
- **month:** last contact month of year (takes values 'jan', 'feb', 'mar', ..., 'nov', 'dec')
- **day_of_week:** last contact day of the week (takes values 'mon','tue','wed','thu','fri')
- **duration:** last contact duration, in seconds (numeric). Important note ( from contributing authors of the dataset): this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

#### Other attributes:
- **campaign:** number of contacts performed during this campaign and for this client (numeric, includes last contact)
- **pdays:** number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
- **previous:** number of contacts performed before this campaign and for this client (numeric)
- **poutcome:** outcome of the previous marketing campaign (takes values: 'failure','nonexistent','success')
#### Social and economic context attributes
- **emp.var.rate:** employment variation rate - quarterly indicator (numeric)
- **cons.price.idx:** consumer price index - monthly indicator (numeric)
- **cons.conf.idx:** consumer confidence index - monthly indicator (numeric)
- **euribor3m:** euribor 3 month rate - daily indicator (numeric)
- **nr.employed:** number of employees - quarterly indicator (numeric)

## Repsoitory Structure
- **Data Folder**- Contains the raw data .csv corresponding file next .txt document.
- **Erdos_Project** - Contains .ipynb files for data exploration, creating and testing files, and data visualizations.
- **Presentation** - Contains the slide deck for the presentation of our findings and recommendations.
