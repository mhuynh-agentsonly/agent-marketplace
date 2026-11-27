# Agent Marketplace prototypes

Clickable prototypes for the agent side of Marketplace. Every page runs in the browser and has a **Prototype** button (bottom-right) for jumping between screens and states.

## Pages

| Page | What it shows | Link |
| --- | --- | --- |
| Marketplace Home | Agent home page | https://mhuynh-agentsonly.github.io/agent-marketplace/marketplace-home.html |
| Onboarding | Agent onboarding; after the last step it opens the AI interview (Hallo embedded) | https://mhuynh-agentsonly.github.io/agent-marketplace/onboarding-v2.html |
| AI interview (Hallo embedded) | Hallo's own pages as they are today, embedded in Marketplace. Only the button colour changes to Marketplace green | https://mhuynh-agentsonly.github.io/agent-marketplace/ai-interview-hallo.html |
| Skills Center | Skills tests for agents | https://mhuynh-agentsonly.github.io/agent-marketplace/skills-center-agent-v2.html |

## AI interview prototype

`ai-interview-hallo.html` shows Hallo's English (US) **Speaking & Writing** assessment embedded in Marketplace: a copy of Hallo's own pages, including its language pickers, mic check, Ready / Set / Go! countdown, "Press to end early" and the "too short, please restart" path. Agents open it from the Skills Center's AI interviews tab. Prototype menu: demo camera & mic, question voice, fast timers, signed-out agent, and a Filipino interface (EN ▾ › Filipino or Tagalog).

## Files

- `speaking-assessment-720p.mp4` — Hallo's instruction video, used by `ai-interview-hallo.html`. Keep it next to the HTML file.
- `ai-interview/` — earlier interviewer visual explorations (orbs and 2D).
