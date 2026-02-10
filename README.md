# 🎓 AI-Powered Student Study Assistant

> Multi-agent AI system helping students learn smarter with Azure OpenAI

[![Hackathon](https://img.shields.io/badge/AI%20Dev%20Days-Hackathon%202026-blue)](https://developer.microsoft.com/reactor/)
[![Azure](https://img.shields.io/badge/Azure-OpenAI-0078D4)](https://azure.microsoft.com/en-us/products/ai-services/openai-service)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## 🎯 Problem Statement

Students struggle with overwhelming study materials - long PDFs, dense textbooks, and complex notes. This AI assistant helps students learn more efficiently through intelligent document processing and personalized study aids.

## 💡 Solution

An AI-powered study companion featuring:

- 📄 **PDF Upload & Processing** - Extract and analyze study materials
- 💬 **Intelligent Q&A** - Ask questions, get instant AI-powered answers
- 📝 **Auto Summarization** - Condense long documents into key points
- 🎴 **Flashcard Generator** - Create study flashcards automatically
- 📊 **Quiz Creator** - Generate practice questions from materials

## 🤖 Multi-Agent Architecture

```
┌─────────────────┐
│   Orchestrator  │
└────────┬────────┘
         │
    ┌────┴────┬─────────┬──────────┐
    │         │         │          │
┌───▼───┐ ┌──▼──┐  ┌───▼───┐  ┌──▼───┐
│Summary│ │ Q&A │  │Flashcd│  │ Quiz │
│ Agent │ │Agent│  │ Agent │  │Agent │
└───────┘ └─────┘  └───────┘  └──────┘
```

Each agent specializes in one task, coordinated by the orchestrator.

## 🛠️ Technology Stack

- **Frontend:** React.js / Next.js
- **Backend:** Node.js (Express)
- **AI:** Azure OpenAI Service (GPT-4)
- **Database:** MongoDB
- **Hosting:** Azure App Service + Azure Static Web Apps
- **Tools:** GitHub Copilot, VS Code

## 🚀 Getting Started

### Prerequisites

```bash
- Node.js 18+ installed
- Azure account (free student tier)
- Git installed
```

### Installation

```bash
# Clone the repository
git clone https://github.com/Mr-CKBJX-SPACE/ai-study-assistant.git
cd ai-study-assistant

# Install dependencies (coming soon)
npm install

# Set up environment variables (coming soon)
cp .env.example .env

# Run development server (coming soon)
npm run dev
```

## 📅 Development Timeline

- **Week 1 (Feb 10-16):** Azure setup + Basic chat interface
- **Week 2 (Feb 17-23):** PDF processing + Q&A agent
- **Week 3 (Feb 24-Mar 2):** Multi-agent system (all 4 agents)
- **Week 4 (Mar 3-9):** Azure deployment + polish
- **Week 5 (Mar 10-15):** Testing + documentation + demo video

## 🏆 Hackathon Category

**Build AI Applications & Agents using Microsoft AI Platform and tools**

This project demonstrates:
- ✅ Azure OpenAI integration
- ✅ Multi-agent architecture
- ✅ Production Azure deployment
- ✅ Real-world educational impact

## 👨‍💻 Author

**Muhammad Sufyan Jura**
- BSCS Student, NUML Rawalpindi Campus
- AI Dev Days Hackathon 2026

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details

## 🙏 Acknowledgments

- Microsoft AI Dev Days Hackathon
- Azure OpenAI Service
- GitHub Copilot
- NUML Rawalpindi

---

**⭐ Star this repo if you find it helpful!**

*Built with ❤️ for students, by a student*
