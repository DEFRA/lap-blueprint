---
layout: "@lap/layouts/BaseLayout.astro"
title: How to add your LAP AI Artefacts to our LAMAI's AI Directory
order: 5
---

# How to add your LAP AI artefacts to the LAMAI AI Directory

Register LAP-specific AI definitions in the shared directory so other teams can discover, reuse, and govern them consistently.

## What you're trying to do

You want to add one or more LAP AI definitions, such as agents, prompts, skills, or instructions, to the DEFRA AI configuration examples repository and have them reviewed for publication.

## Who this is for

Primary audience:

- engineers and AI artefact developers creating LAP AI definitions
- delivery leads coordinating publication and governance
- repository contributors reviewing new directory entries

## Before you start

Before adding a LAP-specific AI agent to the LAMAI Agent Directory, the agent and its supporting solution must comply with DEFRA’s AI Agent Playbook standards and governance requirements.

This includes demonstrating that the agent is designed using the appropriate AI approach, has completed the required AI readiness and assurance checks, follows DEFRA’s Responsible Design Principles, adheres to the Technical Delivery Guidance, and has appropriate governance, ownership, risk management, and oversight arrangements in place.

Teams are responsible for ensuring their agent is lawful, secure, ethical, transparent, and subject to meaningful human oversight before it is registered within LAMAI. Evidence of compliance with these requirements should be available as part of the onboarding and approval process.

### Required guidance

- [Software Development Standards](https://defra.github.io/software-development-standards/guides/github_copilot/)
- [Right Approach](https://github.com/DEFRA/defra-ai-agents/blob/main/playbook/pages/getting-started/right-approach.md)
- [AI Checklist](https://github.com/DEFRA/defra-ai-agents/blob/main/playbook/pages/getting-started/ai-checklist.md)
- [Responsible Design Principles](https://github.com/DEFRA/defra-ai-agents/blob/main/playbook/pages/getting-started/responsible-design-principles.md)
- [Technical Delivery Guidance](https://github.com/DEFRA/defra-ai-agents/blob/main/playbook/pages/getting-started/technical-delivery-guidance.md)
- [Governance and Oversight](https://github.com/DEFRA/defra-ai-agents/blob/main/playbook/pages/getting-started/governance-oversight.md)

## Submission process

1. Clone the [DEFRA AI config examples repository](https://github.com/DEFRA/defra-ai-config-examples).

2. Ensure that all new definitions follow the LAP naming convention:\
   `LAP-(your AI definition name)`\
   For example:
   - LAP-Casework-Agent
   - LAP-Document-Summariser
   - LAP-Inspection-Skill

3. Following the navigation structure, place your LAP-specific AI definitions under the relevant sections. Update `default.html` so navigation updates include your definitions:

   ```ascii
   Agents
   ├── ...
   └── LAP Implementations
       ├── GitHub Copilot
       ├── your agent
       ├── Claude
       ├── Speckit
       ├── OpenAI
       └── Other
   ```

   Any supporting AI configuration files, such as images or documentation, should go in the repository under assets and be linked from your definition documentation.

   Follow the same structure for other AI definitions such as instructions, prompts, and skills.

4. Create a pull request (PR). Once reviewed, merge your changes into the repository. If you need contributor access or a review, contact the owners/contributors of the [DEFRA AI config examples repository](https://github.com/DEFRA/defra-ai-config-examples), Neil Davies (Programme Manager for LAP) at neil.davies@defra.gov.uk, or AICapabilitiesEnablement@defra.gov.uk.

## Review and approval

Before merging, reviewers should confirm:

- standards and governance checks are complete
- documentation is clear and complete
- ownership and support details are included
- naming and placement follow repository conventions

## Who to contact

- Delivery lead (process coordination)
- Engineering lead (repository contribution support)
- AICapabilitiesEnablement@defra.gov.uk (governance and approval support)

## Related links

- [AI Directory - Agents](https://defra.github.io/defra-ai-config-examples/pages/agents/)
- [AI Directory - Instructions](https://defra.github.io/defra-ai-config-examples/pages/instructions/)
- [AI Directory - Prompts](https://defra.github.io/defra-ai-config-examples/pages/prompts/)
- [AI Directory - Skills](https://defra.github.io/defra-ai-config-examples/pages/skills/)

## Agents, Instructions, Skills, Prompts

- [Current agents conforming to DEFRA standards](https://defra.github.io/defra-ai-config-examples/pages/agents/)
- [Current instructions conforming to DEFRA standards](https://defra.github.io/defra-ai-config-examples/pages/instructions/)
- [Current prompts conforming to DEFRA standards](https://defra.github.io/defra-ai-config-examples/pages/prompts/)
- [Current skills conforming to DEFRA standards](https://defra.github.io/defra-ai-config-examples/pages/skills/)
