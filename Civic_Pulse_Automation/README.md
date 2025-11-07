# Civic Pulse Outreach Automation — FLAG Internship Exercise

---

## Loom Demo
https://www.loom.com/share/5f80aa9467934cb08a3e42484a83b008

## Overview

This **n8n workflow** automates FLAG’s early-stage outreach to **Texas city and county officials** using data from **MyGovernmentOnline (MGO)** and a curated **Google Sheet of 500 municipal contacts**.

###  Goals
- Identify non-client contacts across Texas  
- Send personalized introduction emails about FLAG’s **Civic Pulse Dashboard**  
- Track engagement and responses automatically  

## Rollout Plan

| Phase | Timeline | Action |
|--------|-----------|---------|
| **Phase 1** | Week 1–2 | Reached out to top **140 priority contacts** (ranked by population and MGO activity). |
| **Phase 2** | Week 3–4 | Review Google Form responses and shortlist interested officials. |
| **Phase 3** | Week 5–6 | Follow up with remaining 360 contacts using improved messaging. |
| **Phase 4** | Week 7–8 | Present engagement dashboard to FLAG leadership showing ROI and lead pipeline. |

**Strategy:**  
The first 140 contacts act as a pilot to validate the message and timing before the statewide rollout.


## Screenshots – Action Plan 1

### N8N Setup
![N8N Setup](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_1/N8N%20SETUP.png)

### Data Retrieval
![Data Retrieval](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_1/Data%20Retrieval.png)

### Filtering the Data
![Filtering the Data](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_1/Filtering%20the%20data.png)

### Gmail Automation
![Gmail Automation](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_1/Gmail%20Automation.png)

### Gmail Inbox
![Gmail Inbox Screenshot](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_1/Gmail%20inbox%20screenshot%20.png)

### Google Form
![Google Form](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_1/Google%20form.png)

### Form Responses
![Form Responses Screenshot](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_1/Form%20Responses%20Screenshot.png)

This serves as the **first working prototype** toward FLAG’s **data-informed business development framework**.

---

## ⚙️ Workflow Summary

| Step | Node | Purpose |
|------|------|----------|
| 1️⃣ | **Manual Trigger** | Starts the workflow when “Execute Workflow” is pressed — ideal for controlled campaign launches. |
| 2️⃣ | **Google Sheets (Dataset Input)** | Pulls data from `Texas_Municipal_Contacts_500.csv` (Sheet: `Civic_Pulse_140`). Each row represents a potential contact. |
| 3️⃣ | **Filter** | Keeps only rows where `ExistingClient = N` — ensures outreach only to new leads. |
| 4️⃣ | **Gmail** | Sends personalized invitations with each contact’s **name**, **county**, and **organization**, including a dynamic Google Form link. |
| 5️⃣ | **Google Sheets (Form Responses)** | Reads responses from the **demo-interest form** to track engagement in real time. |

---

## Budget

| Phase             | Tool/Service                                | Cost Estimate     | Notes                                                  |
|------------------|---------------------------------------------|-------------------|--------------------------------------------------------|
| Prototype (current) | OpenAI API, Gmail, Google Sheets, n8n (free) | $1–2 total        | Single campaign for 500 contacts                       |
| Scaled (future)    | n8n Cloud, OpenAI credits, MailerLite integration | Up to $50/month   | Supports 5K+ contacts and automated tracking           |

## ✉️ Automated Email Example
Hi [First Name],

I came across your work at the [Organization] in [County] County.

We’re building a small analytics prototype called the “Civic Pulse Engine”
that maps permitting and development trends across Texas counties.

Would you be open to a quick 10-minute demo?

👉 [Yes, I'm interested — fill the quick form]

Best,
Uday Dhanush
Data Analytics Intern
Front Line Advisory Group (FLAG)



---

## Impact

- **Audience:** 140+ Texas city/county officials  
- **Automation Goal:** Outreach → Demo Interest → CRM Integration  
- **Expected Outcome:** 50+ engaged leads and 5–10 qualified demo requests  

---


---

### Author
**Venkat Satya Uday Dhanush Karri**  
Business Development & Data Analytics Intern  
**Front Line Advisory Group (FLAG)**  
November 2025


