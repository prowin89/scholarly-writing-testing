# scholarly-writing

**A Claude Skill for end-to-end scholarly manuscript authoring — journal papers, theses, systematic reviews.**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](<a href="https://github.com/prowin89/Scholarly-Writing">Scholarly writing </a> © 2026 by <a href="https://github.com/prowin89">Prowin</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">)
[![Version](https://img.shields.io/badge/version-0.1.0-blue.svg)](https://github.com/prowin89/scholarly-writing/releases)
[![Built for Claude](https://img.shields.io/badge/built%20for-Claude-orange.svg)](https://claude.ai)

Guides Claude through the full arc of scholarly authoring — framing a contribution, extracting and synthesising literature, theorising, drafting, self-critiquing, running a pre-submission audit, and responding to reviewers — under two non-negotiable commitments: **evidence integrity** (no fabricated source, statistic, or attribution) and **construct integrity** (one defined construct keeps one label throughout the manuscript).

Built for doctoral candidates, researchers targeting Q1 journals, and reviewers who want a rigorous second pair of eyes.

---

## Install

### Option A — Claude Code (recommended)

```bash
/plugin marketplace add prowin89/scholarly-writing
/plugin install scholarly-writing@the-ai-prof
```

The skill activates automatically when Claude detects a scholarly task.

### Option B — Claude.ai web (Pro / Team / Enterprise)

1. Download [`SKILL.md`](plugins/scholarly-writing/skills/scholarly-writing/SKILL.md) from this repo.
2. In Claude.ai → **Settings → Capabilities → Skills → Upload**.

### Option C — Manual folder copy (Claude Desktop / any local setup)

Copy the folder `plugins/scholarly-writing/skills/scholarly-writing/` into:

- macOS / Linux: `~/.claude/skills/`
- Windows: `%USERPROFILE%\.claude\skills\`

Restart Claude or run `/reload-plugins`.

---

## Usage

The skill exposes eight operating modes. Trigger any of them with natural prompts:

| Mode | Example prompt |
|---|---|
| **PLAN** | "Frame the contribution of this paper. Target: *Journal of Marketing*." |
| **ANALYZE** | "Extract constructs, definitions, methods, and findings from these 12 PDFs." |
| **SYNTHESIZE** | "Organise the extracted knowledge into consensus, contradictions, and gaps." |
| **SYNTHESIS BUILD** | "Build a process model of the phenomenon from the synthesis." |
| **THEORIZE** | "Develop hypotheses linking Construct X to Construct Y. Check the mechanism." |
| **DRAFT** | "Draft the Theory section. 800 words. Tight, evidenced, no puffery." |
| **CRITIQUE** | "Stress-test the argument. Find the three weakest claims." |
| **REVISE** | "Rewrite the Discussion. Tighten every paragraph. Keep terminology locked." |
| **QA** | "Run the pre-submission audit. Flag every unverified citation and construct drift." |

Modes chain naturally — a single request may run `PLAN → ANALYZE → SYNTHESIZE → THEORIZE → DRAFT → QA`, or `CRITIQUE → REVISE`.

Full taxonomy, worked examples, and structure templates are inside [`SKILL.md`](plugins/scholarly-writing/skills/scholarly-writing/SKILL.md).

---

## Design commitments

Two rules are load-bearing across every mode:

1. **Evidence integrity.** No fabricated source, finding, quotation, DOI, page number, or statistic. Every claim is attributed to a verified source; anything unverified is flagged, never asserted.
2. **Construct integrity.** One defined construct keeps one label throughout the manuscript. No drift, no synonym-swapping mid-argument.

These are not stylistic preferences. They are the substrate that separates a manuscript worth submitting from one that only looks credible.

---

## Cite this skill

If this skill contributed to work you're submitting or publishing, please cite it.

**Plain text:**

> The AI Prof. (2026). *scholarly-writing: A Claude Skill for end-to-end scholarly manuscript authoring* (Version 0.1.0) [Software]. https://github.com/prowin89/scholarly-writing

**BibTeX:**

```bibtex
@software{aiprof_scholarly_writing_2026,
  author  = {{The AI Prof}},
  title   = {scholarly-writing: A {Claude} {Skill} for end-to-end scholarly manuscript authoring},
  year    = {2026},
  version = {0.1.0},
  url     = {https://github.com/prowin89/scholarly-writing}
}
```

A [`CITATION.cff`](CITATION.cff) file is included — GitHub renders a "Cite this repository" button, and reference managers (Zotero, Mendeley) parse it natively.

---

## Contributing

Issues and pull requests welcome. Before submitting a PR, validate the plugin structure:

```bash
claude plugin validate .
```

---

## License

Released under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You are free to share, adapt, and build on this skill — including commercially — provided attribution is preserved.

---

## Author

Built and maintained by **The AI Prof** — an academic personal-brand project on rigorous, AI-augmented scholarly practice.
