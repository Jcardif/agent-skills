# Agent Skills

A collection of skills for AI agents. Skills are packaged instructions and scripts that extend agent capabilities.

Skills follow the [Agent Skills](https://agentskills.io/) format.

## Available Skills

### markdownlint

Lint and fix Markdown files for style and consistency using markdownlint-cli2. Provides comprehensive linting with 47+ rules, auto-fix capabilities, and flexible configuration.

**Use when:**

- Creating or editing Markdown files
- Checking markdown quality and consistency
- The user asks to lint or fix markdown
- Reviewing documentation

**Features:**

- linting rules (heading style, line length, trailing spaces, blank lines, HTML detection)
- Auto-fix for about half of common issues
- Project-level config files and inline HTML comment directives
- Glob patterns for batch processing
- Rule customization (enable/disable, configure parameters, warning/error levels)

### scientific-paper

Write and edit scientific and academic papers in LaTeX following rigorous research methodology. Covers the complete research lifecycle from problem formulation through publication-ready output.

**Use when:**

- Writing research papers or academic papers
- Editing LaTeX documents or .tex files
- Working on abstracts, literature reviews, methodology sections
- Creating theorems, proofs, or citations
- The user asks to write, edit, expand, structure, or review academic content

**Features:**

- 6-phase research methodology workflow (Problem Formulation → Literature Review → Methodology → Development → Analysis → Writing)
- LaTeX standards with proper packages, theorem environments, mathematical notation
- PhD-level rigor: every claim substantiated, explicit assumptions, acknowledged limitations
- Quality standards: active voice, present/past tense rules, rigorous citation practices
- Mathematical typesetting: proper operator definitions, notation consistency, numbered equations
- Reproducibility focus: detailed methodology, explicit parameters, verifiable results

## Installation

```bash
npx skills add Jcardif/agent-skills
```

## Usage

Skills are automatically available once installed. The agent will use them when relevant tasks are detected.

**Examples:**

```txt
Lint my README.md file
```

```txt
Help me write a research paper on machine learning
```

```txt
Review this LaTeX document for proper mathematical notation
```

## Skill Structure

Each skill contains:

- `SKILL.md` - Instructions for the agent (required)
- `scripts/` - Helper scripts for automation (optional)
- `references/` - Supporting documentation (optional)
- `assets/` - Templates and resources (optional)

For more information about Agent Skills:

- [Agent Skills Open Standard](https://agentskills.io/)
- [Equipping Agents for the Real World](https://claude.com/blog/equipping-agents-for-the-real-world-with-agent-skills)

## License

See [LICENSE](LICENSE) for details.
