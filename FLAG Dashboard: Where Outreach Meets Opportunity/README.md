# FLAG Dashboard: Where Outreach Meets Opportunity — FLAG Internship Exercise (Action Plan 4)

---

## Live Dashboard  
🔗 [View in Looker Studio](https://lookerstudio.google.com/reporting/c246bc5d-6a09-48a4-a9bf-5cf76f8c50d8)

---

## Demo LOOM for Dashboard  
https://www.loom.com/share/178c6b1afda34de4b866862c439d7518

---

** BUDGET 
$0

---
## Overview  

This Looker Studio dashboard transforms FLAG’s municipal outreach dataset into a **real-time analytics view** of potential clients, conference engagement, and permitting activity across Texas counties.  

It’s designed to help the **Front Line Advisory Group (FLAG)** team visualize patterns within their 500 municipal contact records and prioritize outreach as part of the **Civic Pulse** initiative.

---

## Goals  

- Combine **municipal contact data** and **conference insights** into a single analytical interface.  
- Identify **high-potential counties** based on permit volume, population, and engagement.  
- Demonstrate how public datasets (MGO exports + contact sheets) can evolve into **sales intelligence dashboards**.  
- Support **data-informed marketing** and **conference follow-up strategy** for FLAG.

---

## Dashboard Components  

### **Data Source**
- File: `Texas_Municipal_Contacts_500.xlsx`  
- Sheet Used: `Municipal_Contacts` and `Form_Responses` (demo form entries)  
- Cleaned and uploaded to Google Sheets → connected directly to Looker Studio.

---

### **Key Metrics (Top KPI Cards)**

| Metric | Description |
|---------|--------------|
| 🏙️ Total Municipal Contacts | Total count of Texas city/county officials in the dataset |
| 🌟 New Prospects | Number of officials not yet FLAG clients |
| 🧍‍♂️ Conference Attendees | Officials attending the upcoming MGO conference |
| 📈 Avg Priority Score | Weighted score to identify high-impact leads |
| 💰 Total Estimated Permits / Year | Cumulative potential permit activity |

---

### **Visuals Included**

1️⃣ **Bar Chart – Permits by County**  
→ Highlights which Texas counties report the most activity.  

2️⃣ **Geo Map – Contact Distribution by County**  
→ Displays where FLAG’s contacts are concentrated across Texas.  

3️⃣ **Funnel – Outreach Progress**  
→ Visual representation of overall pipeline: All Contacts → Prospects → Conference Leads.  

4️⃣ **Table – Top 10 Priority Cities**  
→ Combines permit estimates and priority scores to rank outreach targets.  

5️⃣ **Scatter Chart – Population vs Priority Score**  
→ Reveals high-value counties with potential for conversion.  

---

### **Filters for Interactivity**
- County Filter  
- Department Size Filter  
- Conference Attendance (Y/N) Filter  
- Date Range (based on `LastContactDate`)  

---

## 💡 Insights  

- High-permit, high-priority counties can be flagged for **targeted outreach campaigns**.  
- The **Conference Attendee filter** directly supports the **Conference Action Plan** by identifying key cities to approach.  
- The **data-driven outreach** approach strengthens FLAG’s credibility as a **Veteran-Owned, analytics-led consultancy**.  
- The dashboard forms the foundation for an **automated data flow** later through n8n or Azure Data Factory.

---

## Next Steps (Scalable Vision)

| Phase | Timeline | Action |
|--------|-----------|--------|
| **Phase 1** | 0–2 weeks | Demo launch with fake permit data integration |
| **Phase 2** | 2–4 weeks | Sync MGO exports to update the dashboard weekly |
| **Phase 3** | 4–6 weeks | Integrate dashboard links into automated outreach emails |
| **Phase 4** | 6–8 weeks | Present this dashboard + live QR demo at the MGO User Conference |

---

## Bonus Strategy — Client Podcast Idea  

Since FLAG currently has **one existing client**, the plan includes:
- Recording a short **client success podcast** discussing their permitting experience.  
- Embedding the audio snippet or quote in **emails and the conference QR preview page**.  
- Featuring that testimonial during the **conference pitch** alongside the Civic Pulse dashboard.  

This gives the FLAG brand a **human story** — building credibility while showing real impact.

---

## Impact Summary  

- **Audience:** 500 Texas municipal contacts  
- **Tool Stack:** Google Sheets + Looker Studio  
- **Cost:** $0 (prototype stage)  
- **Outcome:** Interactive client intelligence dashboard ready for FLAG marketing and outreach expansion.  

---

## Author  

**Venkat Satya Uday Dhanush Karri**  
Business Development & Data Analytics Intern  
**Front Line Advisory Group (FLAG)**  
November 2025  

---

### Tags  
#DataAnalytics #FLAG #CivicPulse #LookerStudio #DashboardDesign #TexasGovernment #DataDrivenMarketing #PublicSectorInnovation #ProgramManagement #VeteranOwnedBusiness #MGO #AnalyticsForOutreach #InternshipProject #GoogleLooker #DataVisualization #FLAGInternship #BusinessDevelopment #LeadGeneration

---

