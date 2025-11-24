# **Risk Register – Week 06**  
*AI Medical Chatbot Project*

This document records potential risks that may affect the project’s schedule, cost, resources, or outcomes.  
Likelihood (L) and Impact (I) are rated on a scale of **1–5**.

---

## **Risk Register Table**

| **Risk ID** | **Description**                                             | **Category**   | **Likelihood (L)** | **Impact (I)** | **Score (L × I)** | **Response**                     |
|-------------|-------------------------------------------------------------|----------------|--------------------|----------------|-------------------|----------------------------------|
| **R1**      | Dataset incomplete, inaccurate, or not medically verified   | Technical      | 3                  | 5              | 15                | Mitigate (cleaning + validation) |
| **R2**      | NLP model fails to reach required ≥ 85% accuracy            | Technical      | 3                  | 4              | 12                | Mitigate (retraining, tuning)    |
| **R3**      | Delay in team members completing assigned tasks             | Schedule       | 3                  | 3              | 9                 | Mitigate (weekly monitoring)     |
| **R4**      | Interface development takes longer than expected            | Schedule       | 2                  | 3              | 6                 | Mitigate (simplify UI scope)     |
| **R5**      | Unexpected cost from cloud tools or API usage               | Cost           | 2                  | 4              | 8                 | Reduce (limit usage, optimize)   |
| **R6**      | Limited access to required tools (e.g., GPU, libraries)     | Resource       | 3                  | 3              | 9                 | Mitigate (use alternatives)       |
| **R7**      | Team lacks experience in NLP or medical dataset handling    | Resource       | 2                  | 4              | 8                 | Mitigate (training, guidance)    |
| **R8**      | Miscommunication among team members                          | Stakeholder    | 3                  | 2              | 6                 | Improve communication channels   |
| **R9**      | Lecturer/advisor feedback delayed                            | Stakeholder    | 2                  | 3              | 6                 | Escalate early, request updates  |
| **R10**     | Ethical or safety concerns in chatbot responses              | Technical      | 2                  | 5              | 10                | Mitigate (safety rules, filters) |

---

### **Risk Scoring Guide**
- **Low (1–5)**  
- **Medium (6–12)**  
- **High (13–25)**  

---




# **Top Priority Risks (Mitigation Plans)**  
*Sorted by Risk Score (Highest to Lowest)*

Below are the top three highest-score risks identified from the Risk Register along with their mitigation actions, responsible team members, and target deadlines.

---

## **1. R1 – Dataset incomplete, inaccurate, or not medically verified**  
- **Score:** 15  
- **Mitigation Strategy:**  
  - Perform dataset cleaning, remove inconsistencies, and validate all medical information using trusted sources (WHO, Mayo Clinic).  
  - Conduct peer review within the team.  
- **Owner:** Data Analyst  
- **Deadline:** Week 07  

---

## **2. R2 – NLP model fails to reach required ≥ 85% accuracy**  
- **Score:** 12  
- **Mitigation Strategy:**  
  - Retrain the model using optimized hyperparameters and improved preprocessing.  
  - Expand dataset and apply augmentation if needed.  
- **Owner:** AI Developer  
- **Deadline:** Week 08  

---

## **3. R10 – Ethical or safety concerns in chatbot responses**  
- **Score:** 10  
- **Mitigation Strategy:**  
  - Add safety filters and predefined medical disclaimers.  
  - Ensure all responses avoid diagnoses and follow safe-advice guidelines.  
- **Owner:** Team Leader / Documentation Lead  
- **Deadline:** Week 07  

---

*These items should be monitored weekly to prevent negative impact on project timeline and deliverables.*

