# Context Bundle

This is the single entry point for reconstructing project context. AI tools and humans should start here.

## Project Snapshot

- Name: See `project.yaml`
- Summary: See `project.yaml`
- Stage: See `project.yaml`
- Last updated: 2025-10-26

## Core Documents

- Vision: ./vision.md
- Architecture: ./architecture.md
- Roadmap: ./roadmap.md
- Tasks: ./tasks.md
- Decisions (ADRs): ./decisions/
- Specs: ./specs/
- Change log: ./CHANGELOG.md
- Data docs: ./data/

## How to Use with AI

- Load this file and all linked docs as context for the AI session.
- Use the system prompt in `../prompts/ai_system_prompt.md`.
- After a session, log it in `./ai_sessions/` and reference this context bundle version.

## First-time flow (new projects)

Run prompts in this order to establish a solid foundation:

1. Product Vision → `../prompts/product_vision_prompt.md`
2. User Stories → `../prompts/user_stories_prompt.md`
3. Tech Stack → `../prompts/tech_stack_prompt.md`
4. Data Schemas → `../prompts/data_schema_prompt.md`

Then record ADRs and Specs as needed under `./decisions/` and `./specs/`.

## Current Focus

- High-level goal: REPLACE_ME
- Key risks: REPLACE_ME
- Next milestone: REPLACE_ME (date)

## Recent Decisions

- See ADRs in `./decisions/`. Highlight the latest:
  - ADR-0001: Chosen architecture style

## Recent Sessions

- See `./ai_sessions/`. Latest: 2025-10-26-session-001.md
