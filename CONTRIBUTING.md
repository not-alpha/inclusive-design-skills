# Contributing to Inclusive Design Skills

Thank you for helping make AI tools more inclusive. Here's how to contribute.

## Principles

1. **Nothing about us without us.** Contributions grounded in lived experience of disability are especially valued.
2. **Design before compliance.** Skills should help people make better design decisions, not just pass audits.
3. **Plain language.** Write skills the way you'd explain something to a smart colleague who isn't a specialist.
4. **Model-agnostic.** Skills should work with any AI agent that supports the SKILL.md format. Don't reference specific model names in skill instructions.

## Adding a Skill

1. Fork the repo
2. Create a folder inside the relevant plugin: `plugin-name/skills/your-skill-name/`
3. Add a `SKILL.md` file with frontmatter (`name`, `description`) and instructions
4. Test it with at least two different AI coding agents
5. Open a pull request with a description of what the skill does and why it's needed

### Skill Structure

```
plugin-name/
  skills/
    your-skill-name/
      SKILL.md
      references/          (optional — deeper reference material)
        your-reference.md
```

### SKILL.md Format

```markdown
---
name: your-skill-name
description: "What this skill does and when it should activate. Be specific about trigger phrases and contexts."
---

# Instructions start here

Write clear, structured instructions that an AI agent can follow.
Use numbered steps, examples, and decision criteria.
```

## Adding a Command

Commands live in the plugin's `skills/` directory alongside regular skills. They chain multiple skills into a workflow and are prefixed with the plugin namespace (e.g., `/cognitive-accessibility:review`).

## Reporting Issues

If a skill gives bad advice, misrepresents an accessibility guideline, or could cause harm, please open an issue. Accessibility errors aren't just bugs — they're barriers for real people.

## Code of Conduct

Be respectful. Be constructive. Remember that accessibility work affects real lives. We don't tolerate ableism, condescension, or dismissiveness toward disability experience.
