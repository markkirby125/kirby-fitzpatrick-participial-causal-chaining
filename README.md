# kirby-fitzpatrick-participial-causal-chaining

Use trailing participial phrases to document deterministic causality and side effects in systems architecture and post-mortems.

---
## Attribution & Provenance

* **Original Framework Author**: William Fitzpatrick
* **YouTube Channel**: [William Fitzpatrick | Writer Science](https://www.youtube.com/@WriterScience)
* **Source Lecture**: "Expert Writing Patterns that Keep Readers Hooked"
* **Direct Video URL**: https://www.youtube.com/watch?v=n1CrHXxcfbA
---

## Overview

The **Participial Causal Chaining** skill replaces ambiguous "which leads to" or comma-splices with precise trailing participial phrases (`..., causing the event loop to starve`) to document deterministic causality and runtime side effects in distributed systems.

## Quick Installation & Universal Setup

Add this skill directly to your coding assistant by pasting the **Magic Prompt** below into your agent chat:

```markdown
@agent Install the "kirby-fitzpatrick-participial-causal-chaining" skill:
1. Ensure ~/.gemini/config/skills, ~/.cursor/skills, ~/.codeium/windsurf/skills, ~/.grok/skills, ~/.kimi-code/skills, and ~/.reasonix/skills exist.
2. Clone https://github.com/markkirby125/kirby-fitzpatrick-participial-causal-chaining.git to ~/.agents/skills/kirby-fitzpatrick-participial-causal-chaining.
3. Symlink ~/.agents/skills/kirby-fitzpatrick-participial-causal-chaining to all local AI app skill directories.
```

## Core Patterns

- **Comma + Participle Nexus**: Replace coordinate linkers with active `-ing` participles.
- **Dangling Modifier Prevention**: Ensure the sentence subject performs the causal action.
- **Multi-Stage Causal Stacking**: Chain up to two causal stages sequentially.
