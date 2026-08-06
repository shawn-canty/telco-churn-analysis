The following table defines the schema for the attributes used during analysis.

## Data Dictionary

| Field Name | Description | Data Type | Valid Values / Notes |
| :--- | :--- | :--- | :--- |
| **CustomerID** | Unique alphanumeric identifier for each customer account. | `String` | e.g., *7590-VHVEG* (Primary Key) |
| **Churn** | Indicates if the customer canceled their service within the last month. | `String` | `Yes`, `No` (Target Variable) |
| **Tenure** | Total number of months the customer has been with the company. | `Integer` | `0` to `72` (New accounts standardized to 0) |
| **Contract** | The term length of the customer's current billing contract. | `String` | `Month-to-month`, `One year`, `Two year` |
| **InternetService** | The underlying technology of the customer's internet connection. | `String` | `Fiber optic`, `DSL`, `No` |
| **TechSupport** | Indicates whether the customer subscribes to the premium technical support add-on. | `String` | `Yes`, `No`, `No internet service` |
| **OnlineSecurity** | Indicates whether the customer subscribes to the premium network security add-on. | `String` | `Yes`, `No`, `No internet service` |
| **PaymentMethod** | The primary method used to collect the customer's monthly balance. | `String` | `Electronic check`, `Mailed check`, `Bank transfer (automatic)`, `Credit card (automatic)` |
| **SeniorCitizen** | Demographic indicator of whether the customer is 65 years of age or older. | `Integer` | `1` (Yes), `0` (No) |
