## Dataset Description

This project uses a dataset related to direct marketing campaigns of a banking institution.  
The campaigns were conducted via phone calls to promote a bank term deposit. In many cases, clients were contacted multiple times to determine whether they would subscribe to the product.

The objective is to predict whether a client will subscribe to a term deposit (`yes` or `no`) based on demographic, financial, and campaign-related features.

---

## Dataset Files

- `train.csv` – Training dataset containing features and target variable  
- `test.csv` – Test dataset containing features only  
- `sample_submission.csv` – Sample submission file showing the required prediction format  

⚠️ The dataset files are not included in this repository due to licensing and academic restrictions.

---

## Input Features

1. **last_contact_date** – Date of last contact  
2. **age** – Age of the client (numeric)  
3. **job** – Type of job (categorical)  
4. **marital** – Marital status (married, divorced, single)  
5. **education** – Education level (unknown, primary, secondary, tertiary)  
6. **default** – Has credit in default? (yes/no)  
7. **balance** – Average yearly balance in euros (numeric)  
8. **housing** – Has housing loan? (yes/no)  
9. **loan** – Has personal loan? (yes/no)  
10. **contact** – Communication type (unknown, telephone, cellular)  
11. **duration** – Duration of last contact in seconds (numeric)  
12. **campaign** – Number of contacts during the current campaign (numeric)  
13. **pdays** – Days since last contact in a previous campaign (-1 if not contacted)  
14. **previous** – Number of contacts before the current campaign  
15. **poutcome** – Outcome of the previous campaign (unknown, other, failure, success)

---

## Target Variable

16. **target** – Whether the client subscribed to a term deposit  
- `yes` – Subscribed  
- `no` – Not subscribed  

---

## Source
- Dataset sourced from **Kaggle – Bank Marketing Dataset**
- Used strictly for academic and learning purposes
