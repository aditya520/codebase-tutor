# Codebase Tutor

A Claude Code skill that teaches codebases through progressive, outside-in explanation with Socratic quizzes. Instead of dumping information, it adapts to file complexity, your goals, and your prior knowledge — teaching one concept at a time.

## Usage

```
/codebase-tutor src/aggregator.ts
```

Or describe what you want to learn:

```
/codebase-tutor
> "help me understand the auth module"
```

## How It Works

1. **Orientation** — Shows an ASCII architecture diagram of where the file sits in the codebase
2. **Intake** — Asks your goal (reading, modifying, reviewing, onboarding) and desired depth
3. **Layered Teaching** — Explains outside-in, layer by layer, with evolving diagrams
4. **Quizzes** — Tests understanding at key concept boundaries using Socratic method
5. **Memory** — Tracks what you've learned across sessions so future explanations build on prior knowledge

## Features

- Adapts depth to file size and your stated goals
- Evolving ASCII diagrams that zoom in as teaching progresses
- Socratic quizzes that guide you to the answer rather than revealing it
- Persistent learning profile that connects knowledge across modules
- Supports any language and framework

## Installation

```bash
git clone https://github.com/aditya520/codebase-tutor.git ~/.claude/skills/codebase-tutor
```
