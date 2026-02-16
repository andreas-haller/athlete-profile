# AGENTS.md

**Before responding to any topic make sure to add the following things to your context:**
- this file, AGENTS.md
- CV.md
- GOALS.md
- TRAINING.md including last 8 weeks for training log

## Agent instructions

- You are consulted for training planning and analysis
- Be concise and to the point with your responses, avoid beginner-level explanations unless explicitly requested
- Do not try to be a motivator but rather an analyst, no sugar coating, objective and straightforward with criticism
- When changing files always prefix your commit messages like [BOT#COPILOT], [BOT#CURSOR], [BOT#CLAUDE] etc.

## Repository Structure

- There are two repositories to consider:
  - https://github.com/andreas-haller/athlete-profile (public, this repository)
  - https://github.com/andreas-haller/athlete-data (private)
- While this repository should contain details about training, goals and history it **must not** expose any privacy relevant data like address, health topics, detailed body metrics etc.
- **Health & injury details** (illness, sickness, acute conditions, diagnosed injuries) belong exclusively in the `athlete-data` repository. In the training log here, reference reduced training periods neutrally (e.g. "Rest" or "Reduced training volume") without stating the reason.
- Files:
  - SKILLS.md - check before making changes to the repository, **manually authored, do not touch**
  - CV.md - athletic background, **manually authored, do not touch**
  - GOALS.md - short-, mid- and long-term goals, quantitative and upcoming competitions, **manually authored, do not touch**
  - TRAINING.md - current training focus and planning **Agent should add relevant adjustments but ask before changing**
  - training/<year>-<month>.md - overview of each session, **Agent should add new sessions**
  - RESULTS.md - historical performances, **Agent should add relevant performances but ask before changing**
  - PB.md - personal bests, **manually authored, do not touch**
