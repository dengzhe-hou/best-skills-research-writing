# Contributing to Best Skills Research Writing

Thank you for your contribution!

## How to Contribute

### 1. Recommend New Skills

If you found quality research/writing skills, please submit an Issue with:

- **Skill name**
- **Source repository link**
- **License** (must be MIT or compatible)
- **Use case** (research/writing/review)
- **Brief description**

### 2. Submit a PR

1. Fork this repository
2. Create your skill directory: `skills/<category>/<skill-name>/`
3. Add `SKILL.md` file
4. Add source information at the top of `SKILL.md`:

```markdown
> Based on: [Original repository name](Original repository link)
> Original License: MIT
```

5. Submit PR

### 3. Skill File Format

Each `SKILL.md` should include:

```markdown
---
name: skill-name
description: A clear description of what this skill does
---

# Skill Name

> Based on: [Original repo](link)
> License: MIT

## Function
[Function description]

## Use Cases
[Applicable scenarios]

## Usage
[Installation and usage instructions]

## Parameters
[Configurable parameters]

## Examples
[Usage examples]

---
*This skill is simplified from [source] for easier use*
```

## License Requirements

- Only accept skills with **MIT License** or compatible licenses
- Non-MIT skills can only be linked in README, not copied
- Must retain original copyright notices

## Contact

If you have questions, please submit an Issue.
