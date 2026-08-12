## Prototype for SME Borrower Journey

https://irisbuild25.github.io/creditflow-app/

### **Key Features for SME Borrower Journey**

| **Feature** | **Description** | **Rationale** |
| --- | --- | --- |
| **Loan Application Submission** | Mechanism for SME borrowers to submit financing requests with application ID, business identification, loan parameters, supporting documents, and bank account details | Entry point to the borrower journey; creates data foundation for risk assessment; satisfies MAS KYC requirements under Securities and Futures Act |
| **Loan Decision & Offer Presentation** | Process that evaluates borrower information and delivers approval (with terms) or rejection within 4 hours (for preliminary decision) | Delivers both core USPs—speed (4-hour decision vs. 2-5 weeks at banks) and robust AI/ML scoring; satisfies CMI 27/2018 due diligence disclosure requirements |
| **Offer Acceptance** | Mechanism for borrowers to review loan terms and formally commit via explicit acceptance action | Captures contractual commitment enabling disbursement; builds trust through transparency; satisfies MAS informed consent requirements |

### **How to Test**

1. **Screen 1**: Adjust the loan slider, scroll through the form sections, then click Submit Application
2. **Screen 2**: Watch the pending state (3 seconds), then review the approved offer details
3. **Screen 3**: Check all 4 boxes, then click Confirm & Accept Loan

### **Notes**

There are a few intentional simplifications on the prototype: No form validation, Instant approval after 3 seconds, No actual file upload, Static offer terms
