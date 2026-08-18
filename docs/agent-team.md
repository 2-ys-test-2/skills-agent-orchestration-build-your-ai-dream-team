# Agent team

- Orchestrator — Claude Opus 4.7 (copilot): coordinates Planner, Coder, and Designer; definition: .github/agents/orchestrator.agent.md
- Planner — Claude Opus 4.7 (copilot): researches the codebase and produces implementation plans; definition: .github/agents/planner.agent.md
- Coder — GPT-5.5 (copilot): writes and validates code, creates runnable app support for Project Pulse; definition: .github/agents/coder.agent.md
- Designer — Gemini 3.1 Pro (copilot): handles UI/UX, accessibility, and visual design for the dashboard; definition: .github/agents/designer.agent.md

Work will be coordinated using the GitHub Copilot CLI running in a Codespace.