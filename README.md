# n8n Workflows & Agentic AI Automation Suite

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI%20Agents-LangChain%20%26%20MCP-412991?style=for-the-badge&logo=openai&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.style=for-the-badge)

A curated collection of production-ready **n8n workflows**, **multi-agent architectures**, **MCP (Model Context Protocol) servers**, and enterprise automation solutions designed for Sales Development, RevOps, Financial Portfolio Assistant, Voice AI, and personal productivity.

---

## 📂 Repository Structure

All directories strictly follow `kebab-case` naming conventions, and workflow definitions are formatted in `snake_case`:

```
n8n-workflows/
├── amplify/
│   ├── account-executive/
│   │   ├── deal_recording_sub_agent.json
│   │   └── demo_booking_sub_agent.json
│   ├── automation-workflows/
│   │   ├── drive_pdf_processor.json
│   │   ├── drive_upload_notifications.json
│   │   └── web_search_ai_agent.json
│   ├── business-development/
│   │   ├── business_development_manager.json
│   │   ├── revops_prospecting_sub_agent.json
│   │   └── sdr_sub_agent.json
│   └── mcp/
│       ├── sales_prospecting_mcp_server.json
│       └── sales_prospecting_sub_agent.json
└── personal/
    ├── ai-builder/
    │   ├── agentic_rag.json
    │   ├── ai_agent_using_gemini_api_key.json
    │   ├── ai_email_draft_generator.json
    │   ├── ai_notification_agent.json
    │   ├── ai_stock_portfolio_assistant.json
    │   ├── ai_voice_assistant_n8n_orchestrated.json
    │   ├── data_ingest.json
    │   ├── elevenlabs_portfolio_assistant.json
    │   ├── equity_portfolio_rebalancer.json
    │   ├── introduction_workflow.json
    │   ├── quirky_stock_assistant.json
    │   ├── slack_ai_chatbot.json
    │   └── telegram_ai_chatbot.json
    └── n8n-masterclass/
        ├── agentic-ai/
        │   ├── gmail_ai_support_assistant.json
        │   ├── google_calendar_ai_agent.json
        │   └── telegram_ai_assistant.json
        ├── automations/
        │   ├── form_automation.json
        │   └── real_estate_automation.json
        └── n8n-foundations/
            ├── ai_agents_basics.json
            ├── api_basics.json
            ├── core_node_types_overview.json
            ├── json_basics.json
            └── send_test_email_via_gmail.json
```

---

## ⚡ Feature Highlights

### 🚀 Amplify Enterprise Suite
- **Business Development Manager Orchestrator**: Multi-agent framework delegating lead prospecting, CRM deal creation, and outreach to specialized sub-agents.
- **MCP Server Integration**: Sales prospecting tools exposed via Anthropic Model Context Protocol (MCP) server endpoints.
- **Account Executive Suite**: Automated demo booking with Google Calendar availability checks and CRM deal recording.
- **Document & PDF Processing**: Automatic Google Drive monitoring, text extraction, and Slack notification pipelines.

### 🧪 Personal AI Experiments & Masterclass
- **Agentic RAG & Gemini AI**: Vector store query retrieval and Google Gemini model integration.
- **Voice AI & ElevenLabs**: Speech synthesis and voice-controlled n8n orchestration.
- **Financial Assistants**: Portfolio rebalancing algorithms, equity data ingest, and stock market assistants.
- **Chatbots**: Multi-platform AI conversational agents for Slack and Telegram.
- **n8n Foundations**: Modular tutorials covering JSON manipulation, REST APIs, Gmail integration, and n8n core node types.

---

## 📥 How to Import Workflows into n8n

1. **Clone the repository**:
   ```bash
   git clone https://github.com/raghhavv03/n8n-workflows.git
   cd n8n-workflows
   ```

2. **Import via n8n UI**:
   - Open your n8n web instance.
   - Click **Workflows** -> **Import from File**.
   - Select any `.json` file from `amplify/` or `personal/`.

3. **Configure Credentials**:
   - Supply required API keys (OpenAI, Gemini, ElevenLabs, Slack, Google Workspace, Telegram, CRM) in your n8n credentials panel.

---

## 🛠️ Prerequisites

- **n8n Version**: `v1.0.0` or higher
- **Node.js**: `v18+` (if running n8n locally)
- **API Keys**: OpenAI / Anthropic / Google Gemini API access for AI sub-agent nodes.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
