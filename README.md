### ✅ **AI_Email_Automation_Agent**

**`ai-email-agent-barbershop-n8n`**



---

```markdown
# AI Email Agent for Barbershop 🪒📬

This is a smart email automation workflow built using **n8n**, **GPT-4o**, and **Gmail API** — designed to help small businesses like barbershops automatically handle customer emails with clarity, consistency, and a touch of personality.

## ✨ What It Does

- 📥 Detects new emails using Gmail integration
- 🧠 Classifies the email type using a GPT-4o-based Text Classifier (`Consultation`, `Billing`, etc.)
- 🏷️ Applies labels in Gmail to organize the inbox
- ✍️ Automatically drafts a personalized, on-brand response based on the email context
- 💾 Saves the draft inside the original thread (no CRM or new tools required)

## 🧠 Why This Exists

Small business owners juggle way too many things — emails, DMs, bookings, payments — and often don’t have time to reply properly. CRMs can be expensive, bulky, and overkill for a small team.

This lightweight automation helps:
- Keep the inbox clean and labeled
- Respond faster to customers
- Maintain a consistent tone, even at 10PM
- Avoid unnecessary CRM costs

## 🛠️ Tech Stack

- [n8n](https://n8n.io/)
- [OpenAI GPT-4o](https://platform.openai.com/)
- Gmail API
- LangChain (for classification logic)

## 📸 Live Preview

A video walkthrough of the full automation system is included — built and edited using **CapCut**.  
Watch it to see how the workflow moves from trigger → label → reply → draft.

## 📁 Files Included

- `My_workflow_3.json` – The main n8n workflow file  
- Sample image of n8n structure  
- Readme and description  

## 🧪 Example Use Case

Customer emails like:
> *"Can I bring my own clippers and get a discount?"*  
> *"I cut my bangs at 2AM with kitchen scissors..."*  
> *"Make me look like Ryan Reynolds."*

The system will:
- Auto-label these emails  
- Draft replies with a touch of sarcasm or warmth depending on the type  
- Save it for review before sending  

## 🚀 Setup Instructions

1. Import the `.json` file into your n8n instance  
2. Connect Gmail and OpenAI credentials  
3. Set trigger to monitor specific Gmail inbox  
4. Customize prompt tone or label names if needed  
5. Test with real or dummy email inputs

> ⚠️ Make sure you have a working OpenAI API key and Gmail API access configured.

## 📬 License

This project is open-source and free to modify for your own use. Attribution appreciated if you build on it!

---
