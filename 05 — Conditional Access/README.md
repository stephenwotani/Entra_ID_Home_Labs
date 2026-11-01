# Microsoft Entra ID: Conditional Access

## 📌 Project Overview
This project demonstrates Conditional Access policies in Microsoft Entra ID, implementing identity-driven access controls based on users, devices, locations, applications, and authentication requirements.

## 🎯 Objectives
- Understand Conditional Access architecture.
- Create and configure access policies.
- Enforce MFA through Conditional Access.
- Explore location-based restrictions.
- Block legacy authentication.
- Evaluate policy behavior safely.

## 🛠️ Technologies Used
- Microsoft Entra ID
- Conditional Access
- Microsoft Entra Admin Center

## ⚙️ Implementation

1. Reviewed Conditional Access policy configuration.
2. Created a test Conditional Access policy.
3. Selected appropriate users and groups.
4. Configured target cloud applications.
5. Required MFA for selected users.
6. Explored blocking legacy authentication.
7. Configured location-based conditions where applicable.
8. Used report-only mode and What If for policy evaluation.
9. Tested policy behavior with designated test accounts.

## 📸 Screenshots

### Conditional Access Policy Creation
<img width="1917" height="912" alt="creating conditional access policies" src="https://github.com/user-attachments/assets/b83754c1-e5c4-456f-b2ec-a410e69acc7b" />


### Policy Conditions
<img width="1917" height="905" alt="conditional access" src="https://github.com/user-attachments/assets/a7b07025-cdc5-430a-b7c2-ada0070d1705" />


### Grant Controls
<img width="1917" height="922" alt="conditional access policies grant" src="https://github.com/user-attachments/assets/e99482cc-cca6-4fd9-a558-912d011d5fdd" />



## 🧪 Testing & Validation
- Reviewed policy configuration.
- Evaluated policy using What If.
- Examined report-only results.
- Verified intended access behavior using test accounts.

## 🔐 Security Considerations
- Exclude emergency access accounts appropriately.
- Test policies before enforcement.
- Avoid accidental tenant-wide lockouts.
- Apply MFA and least privilege.
- Review policy impact regularly.

## 📚 Key Learnings
Learned how Conditional Access supports Zero Trust by evaluating access requests and enforcing context-aware security controls.

## ⚠️ Licensing
Conditional Access generally requires Microsoft Entra ID P1 or an eligible licensing bundle.
