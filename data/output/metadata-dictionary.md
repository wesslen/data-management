# Metadata Dictionary

| Required Field | Field Description | Field Format |
|---|---|---|
| Critical Data Element Name | Unique identifier for the data element using underscores between words (e.g., Cash_Balance) | string |
| Business Description | Non-technical explanation of what the data element represents for business users | string |
| Technical Description | Detailed technical definition of the data element including any specific calculation rules or business logic | string |
| Source System | Name and details of the system where the data originates (e.g., SAP, Banking Portal) | string |
| Data Format | Technical format of the data element (e.g., string, float, int) | string |
| Calculation/Formula | Excel formula or description of calculation if derived, 'Non-calculated' if direct value | string |
| Update Frequency | How often the data element should be updated (e.g., Daily, Weekly, Monthly, Real-time) | string |
| Data Owner | Role responsible for accuracy and maintenance of the data element | string |
| Data Steward | Role responsible for day-to-day quality and accessibility of the data element | string |
| Data Classification | Security classification level (e.g., Public, Internal, Confidential, Restricted) | string |
| Validation Rules | Business rules and constraints that the data element must satisfy | string |
