# ⚡ n8n Automation Workflows (`n8n-automation-workflows`)

Welcome to the **n8n Automation Workflows** repository! This collection features production-ready and experimental [n8n](https://n8n.io/) workflow JSON files designed to automate daily routines, cyber intelligence gathering, social media management, and advanced multi-agent AI systems.

---

## 📁 Included Workflows

Here is an overview of the automation JSON files currently available in this repository:

### 🤖 AI Systems & Agentic Workflows
* **`AI Swarm - Multi Agent System.json`**  
  An advanced setup implementing an AI Swarm pattern where multiple AI agents collaborate to execute complex, multi-step tasks dynamically.
* **`n8n + AI agents.json`**  
  Core implementation connecting n8n workflows with AI agent architectures to perform reasoning, decision-making, and execution.
* **`n8n + claude code.json`**  
  Integrates Claude (Anthropic) for code generation, review, and automation tasks directly within n8n logic.
* **`Personal_Chat_Bot.json`**  
  A custom conversational AI bot interface configured to manage personal queries, route commands, and streamline personal productivity.

### 🛡️ Cyber Security & News Aggregation
* **`Cyber Security News.json`**  
  Automates fetching, filtering, and summarizing daily cybersecurity developments and threat intelligence.
* **`Cyber Security News and Command.json`**  
  Combines cybersecurity news fetching with automated action/command execution based on specific threat triggers.
* **`Cyber_News_Notes.json`**  
  Extracts cybersecurity updates and formats them directly into concise notes for documentation or team sharing.

### 📲 Social Media & Content Distribution
* **`Twitter_Post.json`**  
  Automates drafting, scheduling, and publishing posts directly to Twitter/X.
* **`Youtube_Video_Post.json`**  
  Handles notifications, cross-platform promotion, or post-upload workflows for new YouTube video releases.

### 🛠️ Daily Utilities & Monitoring
* **`Weather Update.json`**  
  Schedules and delivers automated weather reports (e.g., via email, Telegram, or Discord) to help plan your day.
* **`Website status workflow.json`**  
  Monitors website uptime and health status, sending real-time alerts if a service goes down.

---

## 🚀 How to Use These Workflows

1. **Prerequisites:**
   * An operational instance of **n8n** (Cloud or Self-Hosted via Docker/npm).
   * Required API credentials (e.g., OpenAI, Anthropic, Twitter/X, Telegram, Email provider) depending on the workflow.

2. **Importing into n8n:**
   * Open your n8n canvas dashboard.
   * Click on the **`+ New Workflow`** button (or open an existing one).
   * Open the top-right menu (`...`) and click **`Import from File`** (or press `Ctrl+O` / `Cmd+O`).
   * Select the `.json` file of the workflow you want to import from this repository.

3. **Configuration:**
   * Update the placeholder credentials in node settings (e.g., API keys, webhooks, database connections).
   * Activate the workflow toggle in n8n.

---

## 🔮 Future Additions

This repository is continuously updated with new automation blueprints. Planned future categories include:
- Extended AI Orchestrators & RAG Pipelines
- Email & Calendar Scheduling Automation
- Financial & Crypto Market Trackers
- Cloud Infrastructure Monitoring Hooks

---

## 🤝 Contributing & License

Feel free to fork this repository, submit pull requests, or open issues if you have suggestions or fixes for any workflow.

Distributed under the **MIT License**. See `LICENSE` for more information.
