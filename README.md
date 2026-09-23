# Day 6 & Lab 6 — Privacy and Safe AI Prompting in Aviation

## 📌 Overview

This lab focuses on **privacy protection, Personally Identifiable Information (PII), data minimisation, and safe prompt design** when using AI in aviation management.

The activity demonstrates how sensitive passenger, employee, medical, financial, and travel information should be protected before being provided to an AI system. It also highlights the importance of using placeholders, verifying policy information, and completing human review before sending AI-generated communication.

---

## 🎯 Objectives

* Identify personal and sensitive information in aviation-related prompts.
* Understand different levels of data classification.
* Identify privacy risks associated with AI prompts.
* Replace real personal information with safe placeholders.
* Apply data minimisation principles.
* Create safe and professional AI prompts.
* Avoid sharing passwords, medical information, payment details, and unnecessary PII.
* Verify policy and operational information before using AI-generated content.
* Understand the importance of human review.

---

## 🔐 Privacy Risk Identification

The lab identifies several types of sensitive information that should not be unnecessarily included in AI prompts:

| Information         | Risk                           | Safe Action              |
| ------------------- | ------------------------------ | ------------------------ |
| Name                | Personal information           | Replace with placeholder |
| Passport/Aadhaar    | Sensitive identity information | Remove                   |
| Mobile/Email        | Contact information            | Remove                   |
| Booking Reference   | Travel information             | Replace with placeholder |
| Flight/Date         | Travel information             | Use placeholders         |
| Medical Details     | Sensitive information          | Remove                   |
| Card Details        | Financial information          | Remove                   |
| Compensation Claims | Policy-related                 | Verify                   |
| Delivery Promises   | Unsupported information        | Verify                   |

The activity demonstrates that sensitive information should be removed or replaced before creating an AI prompt.

---

## 🛡️ Safe Prompt Design

A safe prompt was created for a delayed-baggage situation.

The prompt uses:

* Passenger name
* `[FLIGHT NUMBER]`
* No personal, medical, or payment information
* No unsupported compensation promises
* No unsupported delivery-time promises
* Verification of policy and baggage-status information

This approach reduces privacy risks while still allowing AI to generate useful professional communication.

### Example Safe Prompt

```text
Draft a professional email to Harikrishan regarding delayed baggage on [FLIGHT NUMBER].
Apologise for the inconvenience and direct the passenger to the authorised
customer-service channel. Do not include personal, medical or payment
information. Do not promise compensation or delivery time. Verify all policy
and status information.
```

---

## ⚖️ Unsafe vs Safe AI Prompts

### Unsafe Prompt

* Contains personally identifiable information.
* May contain medical information.
* May contain financial information.
* Can include unsupported promises.
* Creates unnecessary privacy risks.

### Safe Prompt

* Uses placeholders.
* Removes sensitive information.
* Avoids unnecessary PII.
* Requires policy and status verification.
* Requires human review before final communication.

---

## 📂 Data Classification

The lab classifies aviation information according to its sensitivity:

| Data                          | Classification |
| ----------------------------- | -------------- |
| Advertisement                 | Public         |
| Airport Address               | Public         |
| Flight Schedule               | Public         |
| Staff Schedule                | Internal       |
| Passenger Satisfaction Report | Confidential   |
| Booking Reference             | Confidential   |
| Passport Number               | Restricted     |
| Payment Information           | Restricted     |
| Employee Password             | Restricted     |
| Security Procedure            | Restricted     |
| Baggage Policy                | Public         |
| Medical Request               | Restricted     |

This classification helps determine what information can be safely used and what information requires stronger protection.

---

## 🚨 PII Protection Challenge

The lab identifies common examples of information that should be removed or protected:

* Name + mobile number + booking reference → Remove or replace.
* Name + flight + medical condition → Remove sensitive details.
* Name + employee ID + password → Never share passwords.
* Name + card/bank details + booking reference → Remove financial information.

---

## ✍️ Safe Prompt Examples

### 1. Flight Cancellation

```text
Draft a cancellation email using Harikrishan and [FLIGHT NUMBER].
Do not include personal information.
```

### 2. Passenger Assistance

```text
Draft a professional assistance response without mentioning medical details.
```

### 3. Employee Security Incident

```text
Draft an internal security incident report using placeholders.
Never include passwords.
```

### 4. Refund Request

```text
Draft a refund response using placeholders.
Do not include card or bank details.
```

These examples demonstrate how prompts can remain useful while reducing unnecessary exposure of sensitive information.

---

## 📉 Data Minimisation

**Data minimisation** means using only the information that is necessary for the task.

### Unnecessary Information

Examples include:

* Age
* Address
* Passport number
* Phone number
* PNR

### Minimum Required Information

For a basic passenger communication task, the lab identifies:

* Passenger name
* Verified delay information
* Desired tone

Additional booking, compensation, and contact information should only be added through authorised systems when necessary.

---

## 🧳 Practical Aviation Scenario

### Situation

**Baggage Delay**

### Possible PII

* Passenger name
* Booking reference
* Flight number
* Medical information
* Contact information

### Safe Approach

Use placeholders such as:

```text
Harikrishan
[BOOKING REFERENCE]
[FLIGHT NUMBER]
```

The baggage status and compensation policy should be verified before producing the final communication, followed by human review.

---

## 🧠 Key Learnings

* **PII** is information that can identify a person.
* Passport, Aadhaar, medical, payment, and booking information require protection.
* Booking references can expose travel-account information.
* Placeholders help protect real personal information.
* Data minimisation reduces unnecessary privacy exposure.
* Medical information is private health information.
* Passwords should never be shared in AI prompts.
* AI-generated outputs may contain errors and require review.
* When unsure about sensitive information, it should not be uploaded without checking with an authorised person.

---

## 🔄 Safe AI Workflow

```text
Identify Information
        ↓
Classify Data
        ↓
Remove Sensitive Information
        ↓
Use Placeholders
        ↓
Create Safe Prompt
        ↓
Verify Policy & Status
        ↓
Human Review
        ↓
Final Communication
```

---

## 🛠️ Skills Demonstrated

* AI privacy awareness
* PII identification
* Data classification
* Prompt engineering
* Data minimisation
* Safe AI communication
* Aviation information handling
* Risk identification
* Policy verification
* Human-in-the-loop review

---

## 👨‍🎓 Student Information

**Name:** Harikrishan
**Course:** BBA Aviation Management
**University:** Chitkara University
**Roll No.:** 2520996525
**Lab:** Day 6 & Lab 6

---

## 📌 Conclusion

This lab demonstrates that effective AI use in aviation requires more than creating a good prompt. Sensitive information must first be identified, classified, minimised, and protected. Placeholders can be used instead of real personal data, while policy and operational information should be verified through authorised systems.

The final AI-generated communication should undergo **human review before being sent**, particularly when passenger privacy, compensation, medical information, financial information, or operational details are involved.

**Core Principle:**

> **Protect the data → Minimise the information → Verify the facts → Review the AI output → Communicate safely**
# day6
