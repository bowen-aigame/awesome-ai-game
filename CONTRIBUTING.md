# Contribution Guidelines

Thank you for helping make this the best resource for AI games on the internet! 🎮✨

## Quality Standards

Before submitting, make sure your entry meets **all** of these criteria:

1. **Games only.** This list curates playable AI games — development tools, middleware, asset generators, and frameworks are out of scope.
2. **AI is core, not garnish.** The game must use AI (LLMs, world models, generative systems, or landmark game AI) as a central mechanic — not just "we used AI to make some icons."
3. **Available today.** It must be playable or a public research demo. No vaporware, waitlist-only landing pages, or announced-but-unreleased titles.
4. **Actively maintained.** Abandoned projects (no updates in 18+ months, dead links, shut-down servers) don't qualify, unless listed under *Hall of Fame* or *Milestones* for historical significance.
5. **Notable.** It should have meaningful traction, press coverage, an award, or genuine technical novelty.

## Entry Format

Follow the existing style exactly:

```markdown
- [Name](https://link/) 🔥🆓 - One-sentence description ending with a period.
```

- **Link** to the official website, Steam page, or GitHub repository — not a review or news article.
- **Description** is one sentence, in English, sentence case, ending with a period. Describe what makes it interesting; don't paste marketing copy.
- **Badges** (optional, in this order): 🔥 trending · 🆓 free · 💰 paid · 🧪 beta/research · 📜 open source.
- Add the entry to the **correct category**, preserving the existing ordering convention of the section.
- One entry per pull request unless entries are closely related.

## How to Submit

1. **Search [existing entries](README.md) and [open PRs](../../pulls)** to avoid duplicates.
2. Fork the repository and create a branch: `add/<game-name>`.
3. Add your entry following the format above.
4. Run the linter locally if possible: `npx awesome-lint`.
5. Open a pull request with the title `Add <Name>` and briefly explain **why it belongs** in the list.

## Removing or Updating Entries

PRs that remove dead projects, fix links, or improve descriptions are just as valuable as additions. For removals, state the reason (e.g., service shut down, repository archived).

## Self-Promotion

You may submit your own project **if** it meets the quality standards. Disclose that it's yours in the PR description. Quality speaks for itself — undisclosed self-promotion gets closed.

## Code of Conduct

By participating, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
