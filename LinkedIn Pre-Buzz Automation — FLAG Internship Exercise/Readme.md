# LinkedIn Pre-Buzz Automation — FLAG Internship Exercise

**Loom Demo**
*(Add your Loom link here once recorded)*

---

## Overview

This **n8n workflow** powers FLAG’s **pre-conference LinkedIn automation** for the upcoming **MyGovernmentOnline (MGO) User Conference**.
It automatically generates post ideas, LinkedIn-ready captions, hashtags, and image prompts based on FLAG’s civic-tech themes — turning hours of manual prep into minutes.

This demo shows how FLAG can use **AI + automation** to build buzz, share progress, and highlight product updates before the event.

---

## Goals

* Auto-generate content around FLAG’s civic-tech impact
* Prepare multiple pre-conference LinkedIn posts
* Suggest visuals and hashtags optimized for engagement
* Demonstrate scalable content workflows powered by **n8n** and **OpenAI**

---

## Rollout Plan

| Phase   | Action                                                                              |
| ------- | ----------------------------------------------------------------------------------- |
| Phase 1 | Build base workflow and generate 3 sample LinkedIn posts.                           |
| Phase 2 | Store post outputs in Google Sheets for tracking and editing.                       |
| Phase 3 | Add OpenAI image generation node for visuals.                                       |
| Phase 4 | Connect to Twitter (placeholder) for auto-posting and later extend to LinkedIn API. |

**Strategy:**
Use a **pre-buzz automation engine** to establish FLAG’s presence ahead of the MGO Conference, with AI-assisted consistency and creativity.

---

## Screenshots – Action Plan 2

### n8n Workflow Overview  
![n8n Workflow](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_2/n8n%20workflow.png)

### Topic Generator Node  
![Topic Generator Node](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_2/Topic%20Generator%20Node.png)

### Hashtag Generator Node  
![Hashtag Generator Node](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_2/Hashtag%20Generator%20Node.png)

### Image Prompt Generator  
![Image Prompt Generator](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_2/Image%20prompt%20Generator.png)

### OpenAI Node  
![OpenAI Node](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_2/OPEN%20AI%20NODE.png)

### Output Demo  
![Output Demo](https://github.com/udaydhanush0207/FLAG_MGO_Dashboard_Lead_Acceleration/raw/main/Screenshots/Action_Plan_2/Output%20demo.png)
---

## ⚙️ Workflow Summary

| Step | Node                                      | Purpose                                                                                                   |
| ---- | ----------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| 1️⃣  | **Manual Trigger**                        | Starts the workflow — perfect for manual demo runs.                                                       |
| 2️⃣  | **OpenAI (Topic Generator)**              | Suggests 3–5 civic-tech content ideas based on FLAG’s product and target audience.                        |
| 3️⃣  | **OpenAI (Post Creator)**                 | Generates a polished LinkedIn post with emojis, tone, and structure suitable for professional engagement. |
| 4️⃣  | **OpenAI (Hashtag Optimizer)**            | Creates relevant and trending hashtags to improve reach.                                                  |
| 5️⃣  | **OpenAI (Image Prompt Node)**            | Crafts a descriptive prompt for image generation.                                                         |
| 6️⃣  | **Merge Node**                            | Combines all outputs into a single message bundle.                                                        |
| 7️⃣  | **Google Sheets / Twitter (Demo Output)** | Saves or posts the content — acts as proof of the automation’s capability.                                |

---

## Budget

| Phase               | Tool/Service                                      | Cost Estimate  | Notes                                  |
| ------------------- | ------------------------------------------------- | -------------- | -------------------------------------- |
| Prototype (current) | OpenAI API, n8n (self-hosted), Twitter API (demo) | ~$0–$2         | One-time testing run                   |
| Scaled (future)     | n8n Cloud, OpenAI Pro models, LinkedIn API access | ~$20–$50/month | Continuous post scheduling & analytics |

---

## ✨ Sample Output

**Post Title**

> Empowering Local Governments Through Data

**LinkedIn Captions**

> We’re gearing up for the MGO User Conference this December!
> FLAG’s mission is simple — help Texas cities and counties unlock insights from permit data to make smarter, faster decisions.
> From dashboards to automation, we’re showing how data transparency can reshape civic operations.
> Stay tuned for live demos and behind-the-scenes updates!

**Suggested Image Prompt**

> A clean data dashboard showcasing city permit analytics on a laptop at a conference booth.

**Hashtags**

> #GovTech #SmartCities #FLAG #DataAnalytics #MGOConference #Automation #CivicInnovation

---

## Impact

**Audience:** Civic leaders, public works officials, planners
**Automation Goal:** Idea Generation → Post Creation → Visual Prompt → Engagement Tracking
**Expected Outcome:** Consistent pre-conference buzz and a replicable workflow for future marketing automation

---

## Author

**Venkat Satya Uday Dhanush Karri**
Business Development & Data Analytics Intern
Front Line Advisory Group (FLAG)
November 2025

---
