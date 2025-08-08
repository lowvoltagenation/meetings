# Meetings Repository

This repository contains meeting preparation notes and documentation.

## Custom Slash Commands

### `/meeting` Command

Automatically research and prepare meeting notes for any person or company.

**Usage:**
```bash
/meeting john.doe@company.com
/meeting "Jane Smith CEO TechCorp"  
/meeting "Acme Corporation"
/meeting "sarah.johnson@startup.io tech entrepreneur"
```

**What it does:**
1. Searches for information about the person/company
2. Creates comprehensive meeting prep notes
3. Generates discussion topics and conversation starters
4. Saves as markdown file and commits to repository

**Setup:**
The command is located in `.claude/commands/meeting.md` and is automatically available when using Claude Code in this project.

## Meeting Notes

- [Ike Ubasineke - Grow or Die Club](ike-ubasineke-meeting.md)

## Installation

To use the `/meeting` command in other projects, copy `.claude/commands/meeting.md` to your project's `.claude/commands/` directory, or for global access, copy it to `~/.claude/commands/`.