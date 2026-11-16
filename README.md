# Agent Marketplace prototypes

Clickable prototypes for the agent side of Marketplace. Every page runs in the browser and has a **Prototype** button (bottom-right) for jumping between screens and states.

## Pages

| Page | What it shows | Link |
| --- | --- | --- |
| Marketplace Home | Agent home page | https://mhuynh-agentsonly.github.io/agent-marketplace/marketplace-home.html |
| Onboarding | Agent onboarding; after the last step it opens the AI interview (Hallo embedded) | https://mhuynh-agentsonly.github.io/agent-marketplace/onboarding-v2.html |
| AI interview (our design) | The Speaking & Writing assessment rebuilt in Marketplace style, with our improvements to Hallo's flow | https://mhuynh-agentsonly.github.io/agent-marketplace/ai-interview.html |
| AI interview (Hallo embedded) | Hallo's own pages as they are today, embedded in Marketplace. Only the button colour changes to Marketplace green | https://mhuynh-agentsonly.github.io/agent-marketplace/ai-interview-hallo.html |
| Skills Center | Skills tests for agents | https://mhuynh-agentsonly.github.io/agent-marketplace/skills-center-agent-v2.html |
| Skills Center + ID verification | Skills tests with the ID check | https://mhuynh-agentsonly.github.io/agent-marketplace/skills-center-agent-idv.html |

## The two AI interview prototypes

The main flow uses the **Hallo embedded** version: onboarding, the Home "AI interview" step and the skills-test gate all open `ai-interview-hallo.html`. `ai-interview.html` stays in the repo as our proposal, and the Hallo page uses its Marketplace login screen.

Both show Hallo's English (US) **Speaking & Writing** assessment. They answer different questions:

- **`ai-interview.html` — what we'd like.** Marketplace's own intro and device check, then Speaking (6 prompts) and Writing (2 prompts) in Marketplace style. No name/email form, an End interview button, warnings that pause instead of restarting, and no forced restart for short answers. Ends on Home, or on the Marketplace login if the agent is signed out.
- **`ai-interview-hallo.html` — what agents get if we embed Hallo.** A copy of Hallo's pages, including its language pickers, mic check, Ready / Set / Go! countdown, "Press to end early" and the "too short, please restart" path. Marketplace adds only its top nav and the green buttons. Name and email come prefilled and locked. Prototype menu: demo camera & mic, question voice, fast timers, signed-out agent, and a Filipino interface (EN ▾ › Filipino or Tagalog).

## Files

- `speaking-assessment-720p.mp4` — Hallo's instruction video, used by `ai-interview-hallo.html`. Keep it next to the HTML file.
- `ai-interview/` — earlier interviewer visual explorations (orbs and 2D).
