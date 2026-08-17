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

Make sure your artefact:

- follows DEFRA standards for quality, security, and responsible AI
- has a clear owner and support contact
- includes enough documentation for reuse by other teams

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
   LAP-(your AI definition name)\
   For example:
   - LAP-Casework-Agent
   - LAP-Document-Summariser
   - LAP-Inspection-Skill

3. Following the navigation structure please place your LAP specific AI definitions under relevant sections. Please make sure default.html is updated so navigation updates could take place for your definitions:

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

   Any other supporting AI configuration files such as images or docs etc...should go in the repo under assets and link accordingly from your definition documentation

   Please follow same structure in case you have other AI definitions such as Instructions, Prompts and Skills

4. Create a Pull Request (PR) and once it is reviewed, please kindly merge your changes into the repository. You may need contributor access to the repo, please contact the Owners/Contributors of the [DEFRA AI config examples repository](https://github.com/DEFRA/defra-ai-config-examples) or Contact "neil.davies@defra.gov.uk" as the Program Manager for LAP programme or "AICapabilitiesEnablement@defra.gov.uk" for both contributor access to the review and have your PR reviewed.

## Review and approval

Before merge, reviewers should confirm:

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

- [Current available AGENTS conforming to DEFRA standards](https://defra.github.io/defra-ai-config-examples/pages/agents/)
- [Current available INSTRUCTIONS conforming to DEFRA standards](https://defra.github.io/defra-ai-config-examples/pages/instructions/)
- [Current available PROMPTS conforming to DEFRA standards](https://defra.github.io/defra-ai-config-examples/pages/prompts/)
- [Current available SKILLS conforming to DEFRA standards](https://defra.github.io/defra-ai-config-examples/pages/skills/)
