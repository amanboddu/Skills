# Skills Repository

A collection of custom skills for Claude Code, designed to extend functionality and provide specialized capabilities for various tasks and domains.

## Overview

This repository maintains reusable skill definitions that can be integrated with Claude Code to enhance its capabilities. Each skill is a self-contained module that provides specialized knowledge or functionality for specific use cases.

## Repository Structure

```
Skills-1/
├── caveman/          # Caveman skill module
│   ├── README.md     # Skill documentation
│   └── SKILL.md      # Skill definition
├── Math1680/         # MATH 1680 Statistics tutor skill
└── README.md         # This file
```

## Available Skills

### 1. Caveman
A custom skill module for specialized tasks.
- **Location**: `caveman/`
- **Type**: Project-specific, gitignored

### 2. Math1680 Tutor
An interactive tutor for UNT MATH 1680 (Elementary Probability and Statistics).
- **Location**: `Math1680/`
- **Type**: Educational
- **Features**: Topic explanations, practice problems, and interactive learning

## Usage

These skills are designed to work with Claude Code. To use a skill:

1. Ensure the skill directory is properly configured in your Claude Code environment
2. Skills are automatically available when working in this repository
3. Reference skills by name when needed during your Claude Code sessions

## Adding New Skills

To add a new skill to this repository:

1. Create a new directory with your skill name
2. Add a `SKILL.md` file with the skill definition
3. (Optional) Add a `README.md` with documentation
4. Commit and push your changes

## Maintenance

This repository is actively maintained to keep skills up-to-date and add new capabilities as needed.

## License

Skills in this repository are for personal use and development purposes.