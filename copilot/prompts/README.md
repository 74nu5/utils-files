# GitHub Copilot Prompts

This directory contains **universal prompt templates** for GitHub Copilot that can be configured for any technology stack and development scenario.

## 📁 File Organization

- **Universal Templates**: Prompts with configurable variables for any technology
- **Workflow-Specific**: Prompts for User Stories, Bug Fixes, Feature Development
- **Methodology-Agnostic**: Works with Agile, Scrum, Kanban, or any development process

## 🔧 Configuration Process

1. **Copy** the template file (e.g., `Start-US.prompt.md`)
2. **Configure** all variables in the header:
   - `{PROJECT_NAME}` → Your project name
   - `{TECH_STACK}` → Your technology (React, .NET, Python, etc.)
   - `{UI_TECHNOLOGY}` → Your UI framework
   - `{DATABASE_TYPE}` → Your database
3. **Customize** sections relevant to your project
4. **Remove** irrelevant sections
5. **Save** as your project-specific prompt

## 🎯 Example Configurations

- **React SPA**: `{TECH_STACK}` = "React TypeScript", `{UI_TECHNOLOGY}` = "React"
- **.NET API**: `{TECH_STACK}` = ".NET", `{DATABASE_TYPE}` = "PostgreSQL"
- **Python ML**: `{TECH_STACK}` = "Python", `{UI_TECHNOLOGY}` = "Jupyter Notebooks"