The following table defines the schema for the attributes used during analysis.

## Data Dictionary

| Field Name | Description | Data Type |
| :--- | :--- | :--- |
| **CustomerID** | Unique alphanumeric identifier for each customer account. | `String` |
| **Churn** | Indicates if the customer canceled their service within the last month. | `String` |
| **Tenure** | Total number of months the customer has been with the company. | `Integer` |
| **Contract** | The term length of the customer's current billing contract. | `String` |
| **InternetService** | The underlying technology of the customer's internet connection. | `String` |
| **TechSupport** | Indicates whether the customer subscribes to the premium technical support add-on. | `String` |
| **OnlineSecurity** | Indicates whether the customer subscribes to the premium network security add-on. | `String` |
| **PaymentMethod** | The primary method used to collect the customer's monthly balance. | `String` |
| **SeniorCitizen** | Demographic indicator of whether the customer is 65 years of age or older. | `Integer` |
