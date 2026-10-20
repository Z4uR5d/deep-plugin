<p align="center">
  <img src="https://github.com/Z4uR5d/deep-plugin/raw/main/assets/logo.svg" alt="Deep Plugin Logo" width="150" />
</p>

# Deep Plugin

A specialized routing and subagent orchestration plugin for Antigravity.

## Contents

- **Skill**: `deep`
  - Routes incoming requests between **Solo** and **Delegation** routines.
  - Delegates coding tasks to `DeepCoder` (`Workspace='inherit'`).
  - Delegates investigation, audit, and root-cause tasks to `DeepInvestigator` (`Workspace='inherit'`).
  - Executes iterative verification cycles using `send_message`.

## Usage

The skill has an empty description to avoid unintended auto-triggering. To activate it in any session, invoke it explicitly:

- Slash command: `/deep <task>`
