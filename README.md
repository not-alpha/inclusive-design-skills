# Inclusive Design Skills

Agentic skills for designing accessible, inclusive products — from cognitive accessibility to adaptive interfaces, inclusive research, and accessibility decision-making.
**40 skills** and **18 commands** across **6 plugins**.

Works with any AI coding agent that supports the SKILL.md format: [Claude Code](https://docs.anthropic.com/en/docs/claude-code), [OpenAI Codex](https://openai.com/index/codex/), [Gemini CLI](https://github.com/google-gemini/gemini-cli), [Cursor](https://www.cursor.com), and others.

## Why This Exists

Every accessibility skill set that exists today is engineer-facing. They audit code, check WCAG compliance, validate ARIA attributes, and flag contrast ratios. They treat accessibility as a technical implementation problem that gets caught at the end.

This collection operates **before code**. It shapes decisions about information architecture, language, interaction patterns, cognitive demands, and inclusion — the design layer that determines whether something is genuinely usable, not just technically compliant.

Accessibility isn't a code review. It's a design commitment.

## Plugins

| Plugin | Skills | Commands | Description |
| --- | --- | --- | --- |
| [cognitive-accessibility](cognitive-accessibility) | 8 | 3 | Design for how people actually think: cognitive load, plain language, wayfinding, focus, memory, and error recovery. |
| [inclusive-interaction](inclusive-interaction) | 7 | 3 | Design multi-modal interactions that adapt to how people move, perceive, and communicate. |
| [accessible-content](accessible-content) | 7 | 3 | Structure content that works for screen readers, cognitive differences, and diverse literacy levels. |
| [inclusive-personas](inclusive-personas) | 6 | 3 | Build user stories, personas, and scenarios that include disability from the start. |
| [adaptive-interfaces](adaptive-interfaces) | 6 | 3 | Design systems that respect user preferences and adapt to individual needs. |
| [accessibility-decisions](accessibility-decisions) | 6 | 3 | Document, communicate, and maintain accessibility decisions across teams and time. |

## Quick Start

### Claude Code

Install a single plugin:

```
claude install github:Owl-Listener/inclusive-design-skills/cognitive-accessibility
```

Install all plugins:

```
claude install github:Owl-Listener/inclusive-design-skills
```

### Other Tools

Skills use the universal SKILL.md format. Copy the skill folders into your tool's skills directory, or reference them directly from this repo. Each SKILL.md file works as a standalone instruction set.

For manual use without a coding agent: open any SKILL.md file, copy the contents, and paste it as context at the start of a conversation with any AI assistant. The frameworks and decision criteria work regardless of the tool.

## What Are Skills and Commands?

- **Skills** are domain knowledge units (nouns). They teach your AI agent about a specific aspect of inclusive design — like assessing cognitive load, writing plain language content, or designing forgiving error flows.
- **Commands** are workflows (verbs). They chain multiple skills together to accomplish a task — like running a full cognitive accessibility review or generating an inclusive persona set.

## All Commands

| Command | Plugin | Description |
| --- | --- | --- |
| `/cognitive-accessibility:review` | cognitive-accessibility | Run a full cognitive accessibility review of a flow or interface. |
| `/cognitive-accessibility:simplify` | cognitive-accessibility | Simplify content and interactions to reduce cognitive load. |
| `/cognitive-accessibility:assess-load` | cognitive-accessibility | Assess cognitive load across a multi-step process. |
| `/inclusive-interaction:audit` | inclusive-interaction | Audit an interface for multi-modal interaction support. |
| `/inclusive-interaction:design-flow` | inclusive-interaction | Design an interaction flow with inclusive input and output options. |
| `/inclusive-interaction:keyboard-review` | inclusive-interaction | Review keyboard navigation and focus management. |
| `/accessible-content:review` | accessible-content | Review content for accessibility across cognitive and literacy levels. |
| `/accessible-content:rewrite` | accessible-content | Rewrite content in plain language while preserving meaning. |
| `/accessible-content:structure` | accessible-content | Structure content for screen reader and assistive technology use. |
| `/inclusive-personas:generate` | inclusive-personas | Generate a diverse, inclusive persona set for a product. |
| `/inclusive-personas:audit-stories` | inclusive-personas | Audit user stories for disability inclusion. |
| `/inclusive-personas:scenario-map` | inclusive-personas | Map inclusive usage scenarios across ability spectrums. |
| `/adaptive-interfaces:specify` | adaptive-interfaces | Specify adaptive behaviour for an interface. |
| `/adaptive-interfaces:preference-audit` | adaptive-interfaces | Audit respect for user preferences (motion, contrast, colour scheme). |
| `/adaptive-interfaces:responsive-review` | adaptive-interfaces | Review responsive and flexible layout for accessibility. |
| `/accessibility-decisions:document` | accessibility-decisions | Document accessibility decisions and tradeoffs for a feature. |
| `/accessibility-decisions:review` | accessibility-decisions | Review and surface undocumented accessibility assumptions. |
| `/accessibility-decisions:handoff` | accessibility-decisions | Generate an accessibility decision handoff for engineering. |

## Who This Is For

- **Designers** who want to build accessibility into their process, not bolt it on after.
- **Product managers** who need to make informed accessibility tradeoffs.
- **Content strategists** who write for diverse cognitive and literacy levels.
- **Researchers** who want to include disability in their work from the start.
- **Engineers** who want design-informed accessibility guidance, not just code linting.
- **Anyone** building products used by humans in the full range of human experience.

## Grounding

The cognitive accessibility plugin is grounded in the [W3C Cognitive and Learning Disabilities Accessibility Task Force (COGA)](https://www.w3.org/WAI/cognitive/) guidelines — the most authoritative framework for cognitive accessibility that exists. Other plugins draw on WCAG 2.2, inclusive design methodology, and disability studies research.

These skills encode design judgment, not just compliance rules. They help you make better decisions, not just pass audits.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding new skills, commands, and plugins.

We particularly welcome contributions from people with lived experience of disability. Nothing about us without us.

## Related

This collection is a companion to the [Designer Skills Collection](https://github.com/Owl-Listener/designer-skills) — 63 skills for design craft from research to delivery. Use them together.

## License

MIT — see [LICENSE](LICENSE).
