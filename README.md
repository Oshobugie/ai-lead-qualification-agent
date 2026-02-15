# AI Lead Qualification Agent 🤖

### 🚀 Project Overview
This project is an automated "digital gatekeeper" designed to solve the "Human Bottleneck" in sales. Instead of manually reviewing every form submission, this agent uses **Google Gemini 2.5 Flash** to instantly evaluate leads in under 5 seconds.

It filters prospects based on specific business rules (e.g., Budget > $1,000) and routes them accordingly, ensuring sales teams only focus on high-intent opportunities.

---

### 🛠️ Tech Stack & Tools
* **Orchestration:** Make.com & Pabbly Connect (Cross-platform implementation)
* **AI Engine:** Google Gemini 2.5 Flash (Contextual decision making)
* **Database:** Google Sheets
* **Frontend:** Google Forms
* **Communication:** Gmail (Automated personalized responses)

---

### ⚙️ The Workflow Logic
The system operates on a "Trigger → Process → Router → Action" model:

1.  **Capture:** A user submits a query via Google Forms, which logs data into **Google Sheets**.
2.  **Analyze:** The AI analyzes the lead's "Budget" and "Industry" against a $1,000 threshold.
3.  **Route:**
    * **path_qualified:** If the lead meets criteria, they receive a "Next Steps" email.
    * **path_unqualified:** If they don't meet criteria, they receive a polite rejection email with a specific reason.
4.  **Log:** The system records the decision reasoning back to the database for transparency.

![Workflow Diagram](<img width="1282" height="607" alt="image" src="https://github.com/user-attachments/assets/bf2c901e-1766-41e4-a391-195f4c455b9e" />


---

### 📊 Platform Comparison: Make.com vs. Pabbly
I built this agent on *both* platforms to test viability. Here is my technical breakdown:

| Feature | Pabbly Connect | Make.com |
| :--- | :--- | :--- |
| **Architecture** | Linear (Step-by-step) | Visual Canvas (Bubble-based) |
| **Logic Handling** | Simple "If/Else" | Advanced Routers & Branching |
| **Cost Efficiency** | Internal tasks are free | "Operation" based (Credit intensive) |
| **Best For** | Linear, straightforward automations | Complex logic with multiple paths |

---

### 📈 Key Results
* **Zero Latency:** Reduced lead response time from hours to <5 seconds.
* **100% Automation:** Completely removed manual data entry for the qualification phase.
* **Consistency:** Removed human bias from the vetting process.
