# 🤖 AI-Powered Product Owner Automation

### Automating Backlog Creation from Scanned Sprint Notes using n8n + GPT-5 + Jira Cloud

---

## 📘 Overview
This project demonstrates an end-to-end automation pipeline that transforms **handwritten Product Owner notes** or **sprint planning documents** into structured **Jira Epics and Stories**.

### 🧩 Key Components
- **n8n Workflow Orchestration**
- **GPT-5 Vision (OCR + LLM context extraction)**
- **Jira Cloud API**
- **Google Drive Integration** for note upload
- **Slack (optional)** for story review loop

---

## ⚙️ How It Works
1. A Product Owner uploads scanned notes to Google Drive.  
2. n8n triggers a workflow to:
   - Extract text using GPT-5 Vision
   - Normalize the note
   - Convert to Epic + Stories JSON
   - Create Jira issues via API  
3. Stories appear automatically under the correct Epic in Jira.

---

## 🚀 Business Value
| Metric | Manual | Automated |
|--------|--------|-----------|
| Story Creation Time | 15 min/story | < 1 min/story |
| Sprint Planning | 6 hrs | 1 hr |
| Annual Time Saved | — | ~250–300 hrs/team |
| ROI | — | $15K–$20K per team/year |

---

## 📂 Repository Structure


---

## 🧠 Future Enhancements
- Add **voice note processing** (from meetings)  
- Integrate **Confluence RAG assistant**  
- Add **predictive sprint planning**

---

## 🪪 License
MIT License — free to use, fork, and adapt.
