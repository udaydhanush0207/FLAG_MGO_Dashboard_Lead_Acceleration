# Civic Pulse Outreach Automation — FLAG Internship Exercise

---

## Loom Demo
📹 [View Demo on Loom](#) *(Add link here once uploaded)*

## Overview

This **n8n workflow** automates FLAG’s early-stage outreach to **Texas city and county officials** using data from **MyGovernmentOnline (MGO)** and a curated **Google Sheet of 500 municipal contacts**.

###  Goals
- Identify non-client contacts across Texas  
- Send personalized introduction emails about FLAG’s **Civic Pulse Dashboard**  
- Track engagement and responses automatically  

## 📸 Screenshots – Action Plan 1

### ⚙️ N8N Setup
![N8N Setup](FLAG_MGO_Dashboard_Lead_Acceleration/Screenshots/Action_Plan_1/N8N_SETUP.png)

### 🔍 Data Retrieval
![Data Retrieval](FLAG_MGO_Dashboard_Lead_Acceleration/Screenshots/Action_Plan_1/Data_Retrieval.png)

### 🧹 Filtering the Data
![Filtering the Data](FLAG_MGO_Dashboard_Lead_Acceleration/Screenshots/Action_Plan_1/Filtering_the_data.png)

### 📤 Gmail Automation
![Gmail Automation](FLAG_MGO_Dashboard_Lead_Acceleration/Screenshots/Action_Plan_1/Gmail_Automation.png)

### 📥 Gmail Inbox
![Gmail Inbox Screenshot](FLAG_MGO_Dashboard_Lead_Acceleration/Screenshots/Action_Plan_1/Gmail_inbox_screenshot.png)

### 📝 Google Form
![Google Form](FLAG_MGO_Dashboard_Lead_Acceleration/Screenshots/Action_Plan_1/Google_form.png)

### 📋 Form Responses
![Form Responses Screenshot](FLAG_MGO_Dashboard_Lead_Acceleration/Screenshots/Action_Plan_1/Form_Responses_Screenshot.png)


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

- **Audience:** 500+ Texas city/county officials  
- **Automation Goal:** Outreach → Demo Interest → CRM Integration  
- **Expected Outcome:** 50+ engaged leads and 5–10 qualified demo requests  

---


---

### Author
**Venkat Satya Uday Dhanush Karri**  
Business Development & Data Analytics Intern  
**Front Line Advisory Group (FLAG)**  
November 2025


