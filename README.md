# 🎈 Party Vibe Multi-Agent

> **Enterprise GenAI Celebration & Event Planning Assistant**  
> **Powered by AiShifa** | Architected by **Arshia Nousheen** *(Certified Multi-Agent Developer | Founder & CEO, AiShifa Sovereign Cloud AI)*

---

## 📌 Problem Statement Solved
**Celebration & Event Planner:** A GenAI-powered planning assistant that helps users organize weddings, birthdays, and community events with itemized budgets, phase-by-phase timelines, vendor checklists, and personalized ideas.

---

## 🤖 5-Agent Gemini System Architecture

The core engine utilizes a 5-agent architecture deployed on **Gemini 2.5 Pro** (`gemini-2.5-pro`):

1. **Master Orchestrator Agent:** Parses user constraints, coordinates sub-agent workflows, and validates output accuracy.
2. **Creative Experience Sub-Agent:** Generates bespoke themes, aesthetic palettes, personalized guest engagement concepts, and program highlights.
3. **Financial & Timeline Sub-Agent:** Enforces a deterministic 100% budget allocation and builds pre-event milestones (T-90, T-30, T-7) down to a day-of run-of-show schedule.
4. **Vendor Operations Sub-Agent:** Compiles categorized vendor action items, RFP questions, and priority checklists.
5. **Spatial & Venue Layout Sub-Agent:** Generates seating guidelines, stage placement, and decor layout structures.

---

## 🎨 UI & Branding Specifications
- **Header:** Powered by AiShifa
- **Footer Attribution:** Arshia Nousheen | Certified Multi-Agent Developer | Founder & CEO, AiShifa Sovereign Cloud AI
- **Color Theme:** Dark Glassmorphism (`#0F172A`) with vibrant accents (`#FF3B30`, `#FFCC00`, `#007AFF`, `#34C759`, `#AF52DE`)
- **Multilingual Engine:** Dynamic language detection and mirroring (supports English, Arabic, Hindi, Urdu, Spanish, French, etc.)

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ or Python 3.10+
- Gemini API Key (Google AI Studio)

### Environment Setup
Create a `.env` file in the root directory:
```env
GEMINI_API_KEY=your_gemini_api_key_here
GEMINI_MODEL=gemini-2.5-pro
