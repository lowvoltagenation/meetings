---
description: "Create meeting preparation notes for a person or company. Searches for information and creates a markdown file with discussion topics."
tools: ["WebSearch", "Write", "Bash"]
---

# Meeting Preparation Workflow

Search for information about $ARGUMENTS and create comprehensive meeting preparation notes including:

1. **Research the person/company:**
   - Background information
   - Current role and responsibilities
   - Recent projects or initiatives
   - Company information (if applicable)

2. **Create discussion topics:**
   - Their work and services
   - Potential collaboration opportunities
   - Industry-specific topics
   - Personal/professional development themes

3. **Generate meeting notes file:**
   - Create a markdown file named after the person/company
   - Include all research findings
   - List potential conversation starters
   - Add relevant links and contact information

4. **Commit to the meetings repository:**
   - Add the file to git
   - Commit with descriptive message
   - Push to GitHub repository

**Usage Examples:**
- `/meeting john.doe@company.com`
- `/meeting "Jane Smith CEO TechCorp"`
- `/meeting "Acme Corporation"`
- `/meeting "sarah.johnson@startup.io tech entrepreneur"`

The command will automatically determine whether the argument is an email, person name, or company name and search accordingly.