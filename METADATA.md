# Metadata Sheet – Databel Customer Churn Dataset

This metadata sheet describes the structure, dimensions, and measures included in the Databel Telecom customer churn dataset. It is designed to accompany the **Customer Churn Analysis Dashboard** project.

---

## Dataset Overview

- **Source:** Fictional dataset created for churn analysis training
- **Total Records:** 6,687 customers 
- **Total Features:** 30 columns
- **Time Frame:** Static snapshot (no time dimension)
- **Target Variable:** `Churn Label`

---

## Churn Fields

| Column          | Description |
|-----------------|-------------|
| `Customer ID`   | Unique identifier for each customer |
| `Churn Label`   | Indicates if the customer churned: `Yes` or `No` |
| `Churn Category`| Groups multiple churn reasons together for analysis purposes |
| `Churn Reason`  | Specific reason why the customer left |

---

## Demographic Fields

| Column         | Description |
|----------------|-------------|
| `Age`          | Age of the customer |
| `Under 30`     | Indicates if the customer is under 30: `Yes` or `No` |
| `Senior`       | Indicates if the customer is over 65: `Yes` or `No` |
| `Gender`       | The gender of the customer, indicated by “Male”, “Female”  or “Prefer not to say” |

---

## Contract & Group Info

| Column                     | Description |
|----------------------------|-------------|
| `Group`                    | Indicates if the customer is part of a group contract. A group contract offers advantages and is generally cheaper. Contains “Yes” or “No” |
| `Number of Customers in Group` | Count of customers in the group |
| `Contract Type`            | `Month-to-Month`, `One Year`, or `Two Year` |
| `State`                    | Two-letter state code where the customer lives |
| `Payment Method`           | Preferred payment method of the customer indicated with “Credit Card”, “Direct Debit” or “Paper Check” |
| `Phone Number`             | Customer’s phone number |

---

## Subscription & Usage Metrics

| Column                         | Description |
|--------------------------------|-------------|
| `Account Length`              | Number of months the customer has had an account |
| `Local Calls`                 | Count of local calls |
| `Local Mins`                  | Minutes spent on local calls |
| `Intl Calls`                  | Count of international calls |
| `Intl Mins`                   | Minutes spent on international calls |
| `Intl Active`                 | Whether the customer used international calling: `Yes` or `No` |
| `Intl Plan`                   | Indicates if customer has an international calling plan |
| `Extra International Charges`| Charges incurred without an international plan |
| `Unlimited Data Plan`        | Indicates if the customer has free unlimited download capacity with “Yes” or “No”. This premium is reflected in the amount of the monthly charge |
| `Avg Monthly GB Download`    | Average data downloaded per month in GB |
| `Extra Data Charges`         | Contains the extra charges for data downloads for customers who are not on an unlimited plan |
| `Device Protection & Online Backup` | Whether the customer has paid for device protection: `Yes` or `No` |
| `Customer Service Calls`     | Number of calls made to customer service |
| `Monthly Charges`            | Average monthly bill amount |
| `Total Charges`              | Sum of all monthly charges |

---

## Notes
- All columns are either **dimensions** (categorical) or **measures** (numerical).
- There is **no time series element**, so the analysis is limited to one point in time.
- Dataset is well-suited for exploratory analysis and churn prediction modeling.

---

## Related Files
- [📊 Databel Churn Analysis.xlsx](./Databel%20Churn%20Analysis.xlsx)
- [📈 Databel Churn Dashboard.pdf](./Databel%20Churn%20Dashboard.pdf)
- [📄 README.md](./README.md) – Project overview and insights
