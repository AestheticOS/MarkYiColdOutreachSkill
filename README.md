# Mark Yi Cold Outreach

An open, portable Agent Skill for writing short, research-backed, value-first cold outreach.

The skill turns recurring principles from Mark Yi's public posts, replies, examples, and recommended resources into a reusable workflow. It is designed for one-to-one outreach for jobs, startup roles, collaborations, mentorship, and other high-upside opportunities—not bulk campaigns or generic mail merges.

This is an independent synthesis. It is not affiliated with or endorsed by Mark Yi.

## What's inside

- `SKILL.md` — the complete agent instructions
- `SOURCES.md` — source links and provenance
- `LICENSE` — MIT license for this repository's original content

The repository itself is a valid [Agent Skills](https://agentskills.io) directory. Its `SKILL.md` uses only portable standard fields.

## Install

Clone the repository into the personal skill directory for your agent.

### Codex

```bash
git clone https://github.com/AestheticOS/MarkYiColdOutreachSkill.git ~/.agents/skills/mark-yi-cold-outreach
```

### Claude Code

```bash
git clone https://github.com/AestheticOS/MarkYiColdOutreachSkill.git ~/.claude/skills/mark-yi-cold-outreach
```

### Grok Build

```bash
git clone https://github.com/AestheticOS/MarkYiColdOutreachSkill.git ~/.grok/skills/mark-yi-cold-outreach
```

You can also download the repository and copy its folder into the corresponding skills directory.

## Use

Ask the agent to write or revise a cold email. It should activate the skill automatically when the request matches its description. You can also invoke `mark-yi-cold-outreach` explicitly using the skill-command mechanism supported by your agent.

Useful inputs include:

- recipient, role, and company;
- the outcome you want;
- one recent, verifiable reason you chose them;
- something useful you have already made, found, or done for them;
- your strongest relevant proof point;
- the smallest next step you want to request.

If you have no meaningful proof of work or value to offer yet, the skill will identify that gap instead of hiding it behind polished copy.

## Compatibility

The core format follows the open [Agent Skills specification](https://agentskills.io/specification). It is intentionally free of Codex-, Claude-, and Grok-specific frontmatter or tool instructions.

## Attribution

See [SOURCES.md](SOURCES.md). The linked posts and third-party resources remain the property of their respective authors and publishers. The MIT license applies to the original instructional synthesis in this repository, not to linked material.
