# Healthcare Claims Analysis

This project explores healthcare claims data using Python and pandas in a Google Colab notebook.  

It links **claim headers**, **line-level procedures**, and **diagnosis codes** to answer questions about providers, payers, diagnoses, procedures, and places of service.

## Data Sources

The analysis uses three related CSV files:

- **Diagnosis file (Dataset 1)**  
  Contains diagnosis-level information including:
  - `ProspectiveClaimId`
  - `CodeValue` (ICD-10 diagnosis code)
  - etc

- **Header file (Dataset 2)**  
  Contains claim-level information including:
  - `ProspectiveClaimId`
  - `BillingProviderNPI`, `BillingProvFirstName`, `BillingProvLastName`
  - `PrimaryPayerName`, `PrimaryPayerCode`
  - `PlaceOfService`
  - etc

- **Line file (Dataset 3)**  
  Contains line-level service information including:
  - `ProspectiveClaimId`
  - `HCPCS`
  - `Units`
  - `Charges`
  - etc

---

## How to Run the Notebook

1. Clone this repository:
   git clone <https://github.com/adesai2003/claims-analysis.git>

2. Install requirements.txt

3. Run all cells