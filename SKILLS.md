# Anti-Gravity Agent Skills Catalog

This catalog contains skills integrated from the [antigravity-skills](https://github.com/rmyndharis/antigravity-skills) repository, curated to support the Anti-Gravity Development Protocol.

## Skills by Protocol Capability

### 🏗️ For Ripple (Dependency Awareness)

| Skill | Purpose |
|-------|---------|
| [`architect-review`](skills/architect-review/SKILL.md) | System architecture reviews and design validation |
| [`architecture-decision-records`](skills/architecture-decision-records/SKILL.md) | Documenting architectural decisions as ADRs |

### 📝 For Anti-Gravity Coding Standards

| Skill | Purpose |
|-------|---------|
| [`code-refactoring-refactor-clean`](skills/code-refactoring-refactor-clean/SKILL.md) | Code refactoring and clean code principles |
| [`code-review-ai-ai-review`](skills/code-review-ai-ai-review/SKILL.md) | AI-powered code review workflows |

### 🧠 For Echo (Structural Memory)

| Skill | Purpose |
|-------|---------|
| [`context-manager`](skills/context-manager/SKILL.md) | Context engineering and knowledge management |
| [`reference-builder`](skills/reference-builder/SKILL.md) | Creating technical references and documentation |
| [`code-documentation-doc-generate`](skills/code-documentation-doc-generate/SKILL.md) | Automated code documentation |

### ⚡ For Pulse (Velocity Monitor)

| Skill | Purpose |
|-------|---------|
| [`error-detective`](skills/error-detective/SKILL.md) | Error pattern detection across logs and code |

### ✅ For Autonomous Verification

| Skill | Purpose |
|-------|---------|
| [`tdd-orchestrator`](skills/tdd-orchestrator/SKILL.md) | Test-driven development workflows |

### 🔄 For Atomic Momentum Checkpoints

| Skill | Purpose |
|-------|---------|
| [`git-pr-workflows-git-workflow`](skills/git-pr-workflows-git-workflow/SKILL.md) | Git workflow and PR management |

---

## How Skills Work

Hermes Agent automatically activates relevant skills based on context. When you request:
- "Review this architecture" → Activates `architect-review`
- "Refactor this code" → Activates `code-refactoring-refactor-clean`
- "Debug this error" → Activates `error-detective`

## Adding More Skills

To add more skills from antigravity-skills, run:

```bash
# Find available skills
curl -s https://raw.githubusercontent.com/rmyndharis/antigravity-skills/main/CATALOG.md

# Or browse the repo directly
https://github.com/rmyndharis/antigravity-skills/tree/main/skills
```

Total skills available: **305**  
Currently integrated: **10** (core set)
