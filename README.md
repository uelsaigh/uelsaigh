# Hi, I'm Usama 👋  
### Automation Architect | AI Systems Integrator

I design and build **reliable automation systems** that connect AI, workflows, and data to real-world business operations.

My work focuses on:
- Eliminating manual operational bottlenecks
- Designing fault-tolerant workflows
- Integrating AI agents into production environments

---

## 🔥 Featured Projects

### 🤖 AI Lead Qualification Engine  
🔗 **The full project:** https://github.com/uelsaigh/n8n_sms_bot  

**Stack:** `n8n` • `OpenAI GPT-4o` • `PostgreSQL` • `Twilio` • `Airtable`

An autonomous SMS receptionist that qualifies inbound service leads in real time.  
The system replaces manual intake by using a **verification loop** to ensure data accuracy before triggering business alerts and hand-offs.

#### Key Engineering Highlights
- **Persistent Memory:** PostgreSQL-backed session manager maintains conversation context across asynchronous SMS exchanges.
- **Logic Branching:** Parallel execution paths separate customer-facing dialogue from internal system signals (`[[SUMMARY_COMPLETE]]`).
- **Automated Hand-off:** Real-time Airtable sync and priority email alerts for “Ready-to-Quote” leads.

<p align="center">
  <a href="https://github.com/uelsaigh/n8n_sms_bot">
    <img src="https://raw.githubusercontent.com/uelsaigh/n8n_sms_bot/main/assets/workflow_overview.png" width="900" alt="AI Lead Gen Workflow">
  </a>
  <br>
  <i>Click the image to view the full technical case study and documentation.</i>
</p>

---

### ⚙️ Lead Capture & Logging Automation (Foundational Ops System)  
🔗 **The full project:** https://github.com/uelsaigh/lead-capture-automation  

**Stack:** `Zapier` • `Google Forms` • `Google Sheets`

A production-ready lead intake system designed for marketing agencies to ensure **zero missed inquiries** and **clean, auditable data**.

This project demonstrates how I approach **reliability, schema design, and operational clarity** before layering on AI or advanced logic.

#### Key Engineering Highlights
- **Deterministic Intake:** One row per submission with enforced schema consistency.
- **Data Hygiene:** Field normalization and formatting to prevent downstream CRM issues.
- **Operational Transparency:** Timestamped records and audit-friendly storage.

<p align="center">
  <a href="https://github.com/uelsaigh/lead-capture-automation">
    <img src="https://raw.githubusercontent.com/uelsaigh/lead-capture-automation/main/assets/intake-form.png" width="300" alt="Lead Capture Form">
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/uelsaigh/lead-capture-automation">
    <img src="https://raw.githubusercontent.com/uelsaigh/lead-capture-automation/main/assets/zapier-overview.png" width="500" alt="Zapier Workflow">
  </a>
</p>

<p align="center">
  <a href="https://github.com/uelsaigh/lead-capture-automation">
    <img src="https://raw.githubusercontent.com/uelsaigh/lead-capture-automation/main/assets/sample-spreadsheet.png" width="900" alt="Lead Logging Spreadsheet">
  </a>
</p>

👉 **Why this project matters:**  
Before AI systems can be effective, businesses need **clean inputs, reliable workflows, and clear sources of truth**.  
This project reflects how I design systems from the ground up.

---

## 🧠 How I Think About Automation
I don’t treat automation as “connecting tools.”

I treat it as:
- Designing **systems**, not scripts
- Handling edge cases before they break production
- Choosing the *simplest* architecture that can scale
- Making workflows observable, auditable, and maintainable

AI is layered **after** reliability — not before it.

---

## 🛠️ Technical Stack

**Automation & Orchestration**
- n8n, Zapier, Webhooks

**AI & LLM Systems**
- OpenAI API, Prompt Engineering, Agentic Workflows

**Data & Backend**
- PostgreSQL (Supabase), Airtable, Google Sheets
- REST APIs

---

## 📬 Get in Touch
If you’re looking to:
- Automate business-critical workflows
- Integrate AI into real operations
- Replace fragile manual processes with robust systems

Feel free to reach out or explore the project repositories above.
