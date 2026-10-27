# Learn As You Build

**Build with AI. Understand what you ship.**

`learn-as-you-build` is an agent skill that helps developers learn while building real projects with AI coding assistants.

Instead of blindly accepting generated code, the skill encourages you to understand architectural decisions, review changes, investigate bugs, and retain the concepts you learn.

## Features

- **Teach while coding:** Get concise explanations of new concepts and APIs.
- **Small, understandable changes:** Break larger implementations into manageable steps.
- **Predict before you code:** Build your understanding by predicting which files or logic will change.
- **Persistent learning notes:** Maintain a project-level `LEARNING_NOTES.md` file.
- **Honest code review:** Understand trade-offs, edge cases, and root causes.
- **Self-testing:** Review concepts through short questions and rebuild exercises.
- **Adjustable learning intensity:** Choose `easy`, `medium`, `hard`, or `just do it`.

## Installation

### Antigravity

1. Download or clone this repository.
2. Copy `skills/learn-as-you-build/` into your project's `.agents/skills/` directory.
3. Open the project in Antigravity.
4. Ask the agent to use `learn-as-you-build` on a small coding task.
5. Verify that it explains relevant concepts and maintains `LEARNING_NOTES.md`.

### Skills CLI

Once tested with the repository and supported agent targets:

```bash
npx skills add YOUR_GITHUB_USERNAME/learn-as-you-build
```

Follow the CLI prompts and check the installation location for your agent.

## Usage

Try prompts such as:

- "Implement this feature and teach me as we build."
- "Use hard mode. Let me write the core logic."
- "Explain the concepts introduced in this diff."
- "Quiz me on what I learned today."
- "Help me rebuild this feature without AI."

You can change the learning intensity with `easy`, `medium`, `hard`, or `just do it`.

## How it works

The skill provides instructions to an AI coding agent. It does not independently execute code or guarantee that every instruction will be followed. Behavior varies by agent, model, task, and project context.

## Testing and limitations

- Antigravity: [add tested version and results]
- Other agents: [list only after testing]
- Known issues: [document observed limitations]

This project is experimental. Review generated code and learning notes for accuracy.

## Contributing

Bug reports, reproducible examples, suggestions, and pull requests are welcome. See `CONTRIBUTING.md`.

## License

MIT. See `LICENSE`.