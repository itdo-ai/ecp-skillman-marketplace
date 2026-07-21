# ecp-skillman-marketplace

Claude Code plugin marketplace, managed with [ecp-skillman](https://ecp-skillman.itdo.at/).

## Install

### Claude Code

Add this marketplace in Claude Code:

```
/plugin marketplace add itdo-ai/ecp-skillman-marketplace
```

Then install a plugin:

```
/plugin install ecp-main@ecp-skillman-marketplace
/plugin install ecp-empty@ecp-skillman-marketplace
```

### Other agents

These skills also work outside Claude Code (Cursor, Codex, Copilot and others) via [Vercel Labs Skills](https://github.com/vercel-labs/skills):

```bash
npx skills@latest add itdo-ai/ecp-skillman-marketplace
```

## Plugins

Each skill below links to its source. Expand one to read what it does.

> | | |
> |---|---|
> | 🤖👤 | invoked either way: Claude can load it on its own, and you can call it with `/name` |
> | 🤖 | self-invoked by the agent only, hidden from the `/` menu |
> | 👤 | user-invoked only, Claude will not load it on its own |

### ecp-main (v0.1.5)

_No description._

<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/prog-probe-a"><code>prog-probe-a</code></a></summary>

probe

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/prog-probe-b"><code>prog-probe-b</code></a></summary>

probe

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/prog-probe-c"><code>prog-probe-c</code></a></summary>

probe

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/prog-probe-d"><code>prog-probe-d</code></a></summary>

probe

</details>

**imported**

<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/imported/template-skill"><code>template-skill</code></a></summary>

Replace with description of the skill and when Claude should use it.

Source: [github.com/anthropics/skills](https://github.com/anthropics/skills/tree/fa0fa64bdc967915dc8399e803be67759e1e62b8/template)

</details>

**imported/skills**

<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/imported/skills/algorithmic-art"><code>algorithmic-art</code></a></summary>

Creating algorithmic art using p5.js with seeded randomness and interactive parameter exploration. Use this when users request creating art using code, generative art, algorithmic art, flow fields, or particle systems. Create original algorithmic art rather than copying existing artists' work to avoid copyright violations.

Source: [github.com/anthropics/skills](https://github.com/anthropics/skills/tree/fa0fa64bdc967915dc8399e803be67759e1e62b8/skills/algorithmic-art) · [License](https://github.com/anthropics/skills/blob/fa0fa64bdc967915dc8399e803be67759e1e62b8/skills/algorithmic-art/LICENSE.txt)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/imported/skills/ask-matt"><code>ask-matt</code></a></summary>

Ask which skill or flow fits your situation. A router over the skills in this repo.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/ask-matt) · [License](https://github.com/mattpocock/skills/blob/ed37663cc5fbef691ddfecd080dff42f7e7e350d/LICENSE)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/imported/skills/code-review"><code>code-review</code></a></summary>

probe

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/imported/skills/codebase-design"><code>codebase-design</code></a></summary>

probe

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/imported/skills/nested-demo"><code>nested-demo</code></a></summary>

Demonstrates a skill nested inside sub-folders.

</details>

**tools/in-progress**

<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/in-progress/diagnosing-bugs"><code>diagnosing-bugs</code></a></summary>

Diagnosis loop for hard bugs and performance regressions. Use when the user says "diagnose"/"debug this", or reports something broken/throwing/failing/slow.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/diagnosing-bugs)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/in-progress/domain-modeling"><code>domain-modeling</code></a></summary>

Build and sharpen a project's domain model. Use when the user wants to pin down domain terminology or a ubiquitous language, record an architectural decision, or when another skill needs to maintain the domain model.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/domain-modeling)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/in-progress/loop-me"><code>loop-me</code></a></summary>

Grill me about specs for the workflows I want to build, within this workspace.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/in-progress/loop-me)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/in-progress/setup-ts-deep-modules"><code>setup-ts-deep-modules</code></a></summary>

Wire dependency-cruiser into a TypeScript repo so each package is a deep module — implementation hidden in subfolders, reachable only through its entry-point files. User-invoked.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/in-progress/setup-ts-deep-modules)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/in-progress/to-questionnaire"><code>to-questionnaire</code></a></summary>

Turn a decision you can't fully answer into a questionnaire for someone else to fill in.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/in-progress/to-questionnaire)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/in-progress/to-spec"><code>to-spec</code></a></summary>

Turn the current conversation into a spec and publish it to the project issue tracker — no interview, just synthesis of what you've already discussed.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/to-spec)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/in-progress/wayfinder"><code>wayfinder</code></a></summary>

Plan a huge chunk of work — more than one agent session can hold — as a shared map of decision tickets on your issue tracker, and resolve them one at a time until the way to the destination is clear.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/wayfinder)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/in-progress/wizard"><code>wizard</code></a></summary>

Generate an interactive bash wizard that walks a human through a manual procedure — third-party setup, a one-off migration, an A→B state transition — opening URLs, capturing values, confirming each step, and writing .env files and GitHub Actions secrets.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/in-progress/wizard)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/in-progress/writing-beats"><code>writing-beats</code></a></summary>

Writing, exploit — assemble raw material into a journey of beats, grounding each term before a beat leans on it.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/in-progress/writing-beats)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/in-progress/writing-fragments"><code>writing-fragments</code></a></summary>

Writing, explore — mine raw fragments, no structure yet.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/in-progress/writing-fragments)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/in-progress/writing-shape"><code>writing-shape</code></a></summary>

Writing, exploit — shape raw material into an article, paragraph by paragraph.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/in-progress/writing-shape)

</details>

**tools/misc**

<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/misc/batch-grill-me"><code>batch-grill-me</code></a></summary>

A relentless interview that asks every frontier question at once, round by round.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/in-progress/batch-grill-me)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/misc/claude-handoff"><code>claude-handoff</code></a></summary>

Hand the current conversation off to a fresh background agent that picks up the work immediately.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/in-progress/claude-handoff)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/misc/git-guardrails-claude-code"><code>git-guardrails-claude-code</code></a></summary>

Set up Claude Code hooks to block dangerous git commands (push, reset --hard, clean, branch -D, etc.) before they execute. Use when user wants to prevent destructive git operations, add git safety hooks, or block git push/reset in Claude Code.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/misc/git-guardrails-claude-code)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/misc/grill-with-docs"><code>grill-with-docs</code></a></summary>

A relentless interview to sharpen a plan or design, which also creates docs (ADR's and glossary) as we go.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/grill-with-docs)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/misc/implement"><code>implement</code></a></summary>

Implement a piece of work based on a spec or set of tickets.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/implement)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/misc/improve-codebase-architecture"><code>improve-codebase-architecture</code></a></summary>

Scan a codebase for deepening opportunities, present them as a visual HTML report, then grill through whichever one you pick.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/improve-codebase-architecture)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/misc/migrate-to-shoehorn"><code>migrate-to-shoehorn</code></a></summary>

Migrate test files from `as` type assertions to @total-typescript/shoehorn. Use when user mentions shoehorn, wants to replace `as` in tests, or needs partial test data.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/misc/migrate-to-shoehorn)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/misc/prototype"><code>prototype</code></a></summary>

Build a throwaway prototype to answer a design question. Use when the user wants to sanity-check whether a state model or logic feels right, or explore what a UI should look like.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/prototype)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/misc/research"><code>research</code></a></summary>

Investigate a question against high-trust primary sources and capture the findings as a Markdown file in the repo. Use when the user wants a topic researched, docs or API facts gathered, or reading legwork delegated to a background agent.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/research)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/misc/resolving-merge-conflicts"><code>resolving-merge-conflicts</code></a></summary>

Use when you need to resolve an in-progress git merge/rebase conflict.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/resolving-merge-conflicts)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/misc/scaffold-exercises"><code>scaffold-exercises</code></a></summary>

Create exercise directory structures with sections, problems, solutions, and explainers that pass linting. Use when user wants to scaffold exercises, create exercise stubs, or set up a new course section.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/misc/scaffold-exercises)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/misc/setup-matt-pocock-skills"><code>setup-matt-pocock-skills</code></a></summary>

Configure this repo for the engineering skills — set up its issue tracker, triage label vocabulary, and domain doc layout. Run once before first use of the other engineering skills.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/setup-matt-pocock-skills)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/misc/setup-pre-commit"><code>setup-pre-commit</code></a></summary>

Set up Husky pre-commit hooks with lint-staged (Prettier), type checking, and tests in the current repo. Use when user wants to add pre-commit hooks, set up Husky, configure lint-staged, or add commit-time formatting/typechecking/testing.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/misc/setup-pre-commit)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/misc/tdd"><code>tdd</code></a></summary>

Test-driven development. Use when the user wants to build features or fix bugs test-first, mentions "red-green-refactor", or wants integration tests.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/tdd)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/misc/to-tickets"><code>to-tickets</code></a></summary>

Break a plan, spec, or the current conversation into a set of tracer-bullet tickets, each declaring its blocking edges, published to the configured tracker — edges as text in one file per ticket locally, or native blocking links on a real tracker.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/to-tickets)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/misc/triage"><code>triage</code></a></summary>

Move issues and external PRs through a state machine of triage roles — categorise, verify, grill if needed, and write agent-ready briefs.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/engineering/triage)

</details>

**tools/personal**

<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/personal/edit-article"><code>edit-article</code></a></summary>

Edit and improve articles by restructuring sections, improving clarity, and tightening prose. Use when user wants to edit, revise, or improve an article draft.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/personal/edit-article)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/personal/obsidian-vault"><code>obsidian-vault</code></a></summary>

Search, create, and manage notes in the Obsidian vault with wikilinks and index notes. Use when user wants to find, create, or organize notes in Obsidian.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/personal/obsidian-vault)

</details>

**tools/productivity**

<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/productivity/grill-me"><code>grill-me</code></a></summary>

A relentless interview to sharpen a plan or design.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/productivity/grill-me)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/productivity/grilling"><code>grilling</code></a></summary>

Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'grill' trigger phrases.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/productivity/grilling)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/productivity/handoff"><code>handoff</code></a></summary>

Compact the current conversation into a handoff document for another agent to pick up.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/productivity/handoff)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/productivity/teach"><code>teach</code></a></summary>

Teach the user a new skill or concept, within this workspace.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/productivity/teach)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/productivity/writing-great-skills"><code>writing-great-skills</code></a></summary>

Reference for writing and editing skills well — the vocabulary and principles that make a skill predictable.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/productivity/writing-great-skills)

</details>

**tools/skills**

<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/skills/design-an-interface"><code>design-an-interface</code></a></summary>

Generate multiple radically different interface designs for a module using parallel sub-agents. Use when user wants to design an API, explore interface options, compare module shapes, or mentions "design it twice".

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/deprecated/design-an-interface)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/skills/qa"><code>qa</code></a></summary>

Interactive QA session where user reports bugs or issues conversationally, and the agent files GitHub issues. Explores the codebase in the background for context and domain language. Use when user wants to report bugs, do QA, file issues conversationally, or mentions "QA session".

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/deprecated/qa)

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-main/skills/tools/skills/request-refactor-plan"><code>request-refactor-plan</code></a></summary>

Create a detailed refactor plan with tiny commits via user interview, then file it as a GitHub issue. Use when user wants to plan a refactor, create a refactoring RFC, or break a refactor into safe incremental steps.

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/deprecated/request-refactor-plan)

</details>
<details>
<summary>👤 <a href="plugins/ecp-main/skills/tools/skills/ubiquitous-language"><code>ubiquitous-language</code></a></summary>

Extract a DDD-style ubiquitous language glossary from the current conversation, flagging ambiguities and proposing canonical terms. Saves to UBIQUITOUS_LANGUAGE.md. Use when user wants to define domain terms, build a glossary, harden terminology, create a ubiquitous language, or mentions "domain model" or "DDD".

Source: [github.com/mattpocock/skills](https://github.com/mattpocock/skills/tree/ed37663cc5fbef691ddfecd080dff42f7e7e350d/skills/deprecated/ubiquitous-language)

</details>

### ecp-empty (v0.1.2)

_No description._

<details>
<summary>🤖👤 <a href="plugins/ecp-empty/skills/architecture-decisions"><code>architecture-decisions</code></a></summary>

ALWAYS Execute this skills before deciding any technical/architectural matter, to avoid reintroducing already-solved issues.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/caveman"><code>caveman</code></a></summary>

Ultra-compressed communication mode. Use when user says "caveman mode" or invokes /caveman.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/color-architect"><code>color-architect</code></a></summary>

Generates strategic color palettes. Use when creating or updating app color schemes, theming, or brand colors.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/create-agent-skills"><code>create-agent-skills</code></a></summary>

Expert guidance for Claude Code Skills. Use when working with SKILL.md files, authoring new skills, improving existing skills, or understanding skill structure.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/diagnose"><code>diagnose</code></a></summary>

Disciplined diagnosis loop for hard bugs and performance regressions. Reproduce → minimise → hypothesise → instrument → fix → regression-test. Use when user says "diagnose this" / "debug this", reports a bug, says something is broken/throwing/failing, or describes a performance regression.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/favicon-generator"><code>favicon-generator</code></a></summary>

Generate professional-quality favicons. Trigger when you need favicons, app icons, or browser tab icons.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/generate-app-names"><code>generate-app-names</code></a></summary>

Generates strategic product and application names using linguistic engineering. Trigger when invoked with /generate-app-names

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/grill-me"><code>grill-me</code></a></summary>

Interview the user relentlessly about a plan or design until reaching shared understanding, resolving each branch of the decision tree. Use when user wants to stress-test a plan, get grilled on their design, or mentions "grill me".

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/grill-with-docs"><code>grill-with-docs</code></a></summary>

Grilling session that challenges your plan against the existing domain model, sharpens terminology, and updates documentation (CONTEXT.md, ADRs) inline as decisions crystallise. Use when user wants to stress-test a plan against their project's language and documented decisions.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/improve-codebase-architecture"><code>improve-codebase-architecture</code></a></summary>

Find deepening opportunities in a codebase, informed by the domain language in CONTEXT.md and the decisions in docs/adr/. Use when the user wants to improve architecture, find refactoring opportunities, consolidate tightly-coupled modules, or make a codebase more testable and AI-navigable.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/init-agent-project"><code>init-agent-project</code></a></summary>

Bootstraps a project for AI-agent usage in any agent.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/mcp-builder"><code>mcp-builder</code></a></summary>

Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact with external services through well-designed tools. Use when building MCP servers to integrate external APIs or services, whether in Python (FastMCP) or Node/TypeScript (MCP SDK).

</details>
<details>
<summary>🤖👤 <a href="plugins/ecp-empty/skills/micro-spec"><code>micro-spec</code></a></summary>

Turn a project idea into a minimal, on-point SPEC.md (caveman style — least text, max info). Use when the user runs /micro-spec or asks to spec out / document a project idea.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/minimalist-web-design"><code>minimalist-web-design</code></a></summary>

Designs and reviews minimalist, editorial-feeling web interfaces to a 2026 standard — distinctive layouts, extreme typographic hierarchy, restrained-but-bold color, strict performance budgets, and motion/SVG developer handoff. Use when designing a landing page or marketing site, auditing an existing design for generic "visual recycling," or preparing animated SVGs (e.g. GSAP DrawSVG) for developer handoff.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/og-image-creator"><code>og-image-creator</code></a></summary>

Smart OG image generation that studies your codebase, understands routes and brand identity, then creates contextually appropriate Open Graph images using Playwright and React components.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/prototype"><code>prototype</code></a></summary>

Build a throwaway prototype to flush out a design before committing to it. Routes between two branches — a runnable terminal app for state/business-logic questions, or several radically different UI variations toggleable from one route. Use when the user wants to prototype, sanity-check a data model or state machine, mock up a UI, explore design options, or says "prototype this", "let me play with it", "try a few designs".

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/seo-optimizer"><code>seo-optimizer</code></a></summary>

Comprehensive SEO optimization for web applications. Use when asked to improve search rankings, add meta tags, create structured data, generate sitemaps, optimize for Core Web Vitals, or analyze SEO issues. Works with Next.js, Astro, React, and static HTML sites.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/tdd"><code>tdd</code></a></summary>

Test-driven development with red-green-refactor loop. Use when user wants to build features or fix bugs using TDD, mentions "red-green-refactor", wants integration tests, or asks for test-first development.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/teach"><code>teach</code></a></summary>

Teach the user a new skill or concept, within this workspace.

</details>
<details>
<summary>👤 <a href="plugins/ecp-empty/skills/zoom-out"><code>zoom-out</code></a></summary>

Tell the agent to zoom out and give broader context or a higher-level perspective. Use when you're unfamiliar with a section of code or need to understand how it fits into the bigger picture.

</details>

---

_Generated by [ecp-skillman](https://ecp-skillman.itdo.at/)._
