# Retention_Rate_PowerBI
## 1.	Introduction
This independent project is to create visualizations for monthly customer retention. The data set was provided by an online application company, containing two files with the transaction records within 6 months.

## 2. Tools and Data Pre-processing
### Python 
Used to pre-process the data. Including the following tasks:
- Divided the data by product line. 
- Performed descriptive analysis
- Excluded the users whose first purchases were not between May – Oct 2020 from the purchase information, namely the purchases.csv file.

### Power BI
Used to further data modeling and visualization. Please refer to next slides for the
visualizations.

Data modeling: 
- Grouped the data by User ID and counted the purchase ID to get how many times each user purchased during May-Oct 2020. The processed tables were named as ”Restaurant_Purchase Times” and ”Retail_Purchase Times”
- Several measures/calculations were created as follow:

| Measures     | Specification                                                                                               
|---------------|:---------------------
| New user kept |To calculate the No. of users who did another purchase after their first purchase on a monthly basis.
| New user lost |To calculate the No. of users who did not purchase after their first purchase during the period.
| New count |To calculate the No. of new user during the period.
| New user kept overview |To calculate the No. of users who did another purchase after their first purchase during the period.


## 3. Visualization

- A donut chart is presenting the percentage of kept and lost users during May – Oct 2020 per product line
