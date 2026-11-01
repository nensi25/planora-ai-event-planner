# ✦ PLANORA AI
### Big Moments. Brilliantly Planned.

**An intelligent event-planning platform that transforms celebration ideas into organized, actionable plans.**

<p align="center">
  **Plan Smarter • Spend Wiser • Celebrate Better**
</p>

---

## 🌟 About Planora AI

Planning a wedding, birthday, or community celebration involves multiple decisions, budget constraints, vendor coordination, and deadlines.

**Planora AI brings the entire planning journey into one organized workspace.**

It helps users structure event requirements, manage estimated expenses, track preparation tasks, organize vendors, and explore creative celebration ideas through a modern, interactive interface.

Our mission is to make event planning simpler, smarter, and more accessible for everyone.

## 🚀 Key Features

| Feature | What it does |
|---|---|
| 🧠 Event Blueprint | Create an organized starting plan for an event. |
| 💰 Smart Budget Planner | Manage expense categories and rebalance the budget. |
| 📊 What-If Event Lab | Explore how guest count and catering choices affect estimates. |
| 📅 Interactive Timeline | Add, manage, and complete preparation tasks. |
| 🤝 Vendor Management | Organize vendors and update their booking statuses. |
| 👥 Guest Management | Maintain guest lists and RSVP information. |
| 🎨 Theme Studio | Explore and select celebration themes. |
| ✦ AI Copilot | Get contextual event-planning assistance. |

## 💡 What Makes Planora Different?

### 1. Event What-If Planning
Explore how changes in guest count and catering choices can affect estimated event expenses.

### 2. Budget Awareness
Organize expense categories and rebalance allocations to make better use of the available budget.

### 3. Celebration Blueprint
Turn event requirements into a structured planning starting point.

### 4. One Connected Workspace
Bring event details, budgets, tasks, vendors, guests, and themes together instead of managing them across multiple tools.

## 🖥️ User Experience

- Modern dashboard with dedicated feature pages.
- Sidebar navigation on desktop.
- Mobile-friendly navigation.
- Responsive layouts for different screen sizes.
- Local browser storage for supported planning data.

## 🛠️ Technology Stack

**Frontend**
- HTML5
- CSS3
- JavaScript

**Data Persistence**
- Browser LocalStorage

**AI Direction**
- Contextual event-planning assistance in the demo Copilot.
- Architecture designed to support secure integration with Google Gemini API through a backend.

> **Current implementation note:** The standalone deployed frontend uses local contextual demo responses. It does not currently make live Gemini API calls. Gemini integration is part of the planned development roadmap.

## 🏗️ Application Architecture

```text
                 USER
                   |
                   v
             PLANORA AI UI
                   |
        +----------+----------+
        |          |          |
        v          v          v
     Event      Budget     Timeline
    Blueprint   Planner    Manager
        |          |          |
        +----------+----------+
                   |
                   v
              AI COPILOT
          (Local Demo Logic)
                   |
                   v
             LocalStorage
```

**Future AI architecture:**

```text
Frontend → Secure Backend → Google Gemini API
```

API credentials must remain on the server and must never be exposed in browser JavaScript.

## 🎯 Who Is Planora For?

- Couples planning weddings.
- Families organizing birthdays and anniversaries.
- Communities organizing cultural celebrations.
- Event organizers coordinating multiple activities.
- Anyone looking for a more organized celebration.

## ⚡ Getting Started

### Run Locally

1. Clone the repository:

```bash
git clone https://github.com/nensi25/planora-ai-event-planner.git
```

2. Open the project folder.
3. Double-click `index.html` to launch the application.

No npm installation, Node.js setup, or frontend build process is required.

## 🔐 Security & Privacy Considerations

- Never expose API keys in frontend code.
- Use a secure backend for future AI API integrations.
- Validate user inputs.
- Handle user information responsibly.
- Demo planning data is stored in browser LocalStorage.

## 🏆 Hackathon Evaluation Alignment

| Evaluation Parameter | Planora AI Approach |
|---|---|
| Code Quality | Organized HTML, CSS, and JavaScript files |
| Security | Secure backend integration approach for future AI services |
| Efficiency | Lightweight frontend without unnecessary dependencies |
| Testing | Interactive planning workflows and budget calculations |
| Accessibility | Responsive interface and readable navigation |
| Problem Alignment | Event planning, budgets, timelines, vendors, and personalized ideas |

## 🔮 Future Roadmap

- Live Gemini-powered event planning.
- Personalized AI-generated celebration blueprints.
- Advanced budget optimization.
- AI-generated event moodboards.
- Regional and multilingual celebration recommendations.
- Vendor discovery and comparison.
- Collaborative event planning.
- Event-day assistance and contingency recommendations.

## 🌍 Our Vision

Every celebration deserves thoughtful planning, regardless of its size or budget.

Planora AI combines practical planning tools, intelligent assistance, and creative ideas to help people organize meaningful experiences.

**Because the best celebrations don't happen by accident. They're brilliantly planned.**

---

<p align="center">
  ✦ **PLANORA AI** ✦<br>
  *Big Moments. Brilliantly Planned.*
</p>

**Built with passion for innovation and intelligent experiences.**
