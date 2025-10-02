# Copilot Instruction Files

This directory contains **universal instruction templates** that define coding standards, best practices, and guidelines adaptable to any programming language and technology stack.

## 📂 File Types

- **Universal Templates**: Generic coding standards with configurable variables
- **Multi-Language Support**: Instructions that work across C#, JavaScript, Python, Java, Go, Rust, etc.
- **Framework-Agnostic**: Patterns applicable to React, .NET, Spring Boot, Django, etc.
- **Architecture-Independent**: Works with microservices, monoliths, serverless, etc.

## 🔧 Configuration Guide

### Step 1: Choose Your Template
- `copilot-instructions.md` - Comprehensive coding standards and best practices

### Step 2: Configure Variables
Replace the configuration section variables:
```
{PROJECT_NAME} → "MyAwesomeApp"
{TECH_STACK} → "React TypeScript" | ".NET" | "Python FastAPI" | "Java Spring Boot"
{ARCHITECTURE_TYPE} → "SPA" | "Microservices" | "Monolith" | "Serverless"
{DATABASE_TYPE} → "PostgreSQL" | "MongoDB" | "SQLite" | "DynamoDB"
{AUTH_PROVIDER} → "Auth0" | "Azure AD" | "Firebase Auth" | "JWT"
```

### Step 3: Customize Content
- **Keep** sections relevant to your technology
- **Remove** irrelevant technology-specific examples
- **Add** your team's specific conventions
- **Adjust** coding standards to your preferences

## 🌐 Technology Examples

| Technology Stack | Configuration Example |
|------------------|------------------------|
| **React SPA** | `{TECH_STACK}` = "React TypeScript"<br/>`{UI_FRAMEWORK}` = "React"<br/>`{BUILD_COMMAND}` = "npm run build" |
| **.NET API** | `{TECH_STACK}` = ".NET"<br/>`{ARCHITECTURE_TYPE}` = "Clean Architecture"<br/>`{DATABASE_TYPE}` = "Entity Framework" |
| **Python ML** | `{TECH_STACK}` = "Python"<br/>`{UI_FRAMEWORK}` = "Jupyter + Streamlit"<br/>`{TESTING_FRAMEWORK}` = "pytest" |
| **Java Enterprise** | `{TECH_STACK}` = "Java Spring Boot"<br/>`{DATABASE_TYPE}` = "JPA + PostgreSQL"<br/>`{BUILD_COMMAND}` = "mvn clean install" |