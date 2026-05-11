# Gemini CLI Skill: LLM Coding Guidelines

## Credits

This skill is a Gemini CLI adaptation of the guidelines found in the repository `forrestchang/andrej-karpathy-skills`. The principles are based on industry-standard workflows and observations shared by [Andrej Karpathy](https://twitter.com/karpathy) regarding LLM coding behaviors.

Original source: [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills)

## Description

This repository provides a specialized skill for the Gemini CLI agent. It implements a set of behavioral guidelines designed to enforce senior-level engineering standards, prioritize simplicity, and ensure surgical code modifications.

These instructions are specifically tuned to reduce common LLM mistakes such as speculative coding, unnecessary abstractions, and unrelated refactoring.

## Installation

You have two options for installing this skill depending on your needs.

### Option 1: User Scope (Global)

Install this skill once to make it available across all your projects and sessions.
   ```bash
   gemini skills install llm-coding-guidelines.skill --scope user
   ```

### Option 2: Workspace Scope (Local)

Install this skill only for the current project directory.
   ```bash
   gemini skills install llm-coding-guidelines.skill --scope workspace
   ```

## Usage
After installation, open an interactive Gemini CLI session and execute the command: 

```bash
/skills reload   
```

Once reloaded, you can activate the guidelines by instructing the agent to activate the llm-coding-guidelines skill.

## License

This project is open-source and available under the MIT License.
