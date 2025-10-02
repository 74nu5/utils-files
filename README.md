# utils-files
Universal development utility files - A collection of **technology-agnostic** configuration files, templates, and tools that can be adapted to enhance any development workflow, regardless of programming language or framework.

## Repository Structure

```
/
├── copilot/                 # GitHub Copilot related files
│   ├── prompts/            # Custom prompts for GitHub Copilot
│   ├── instructions/       # Copilot instruction files
│   └── modes/             # Copilot Agent mode files
├── mcp/                    # MCP (Model Context Protocol) toolset files
├── editorconfig/           # .editorconfig files for different projects
├── ide-configs/            # IDE configuration exports
│   ├── vscode/            # Visual Studio Code configurations
│   ├── jetbrains/         # JetBrains IDE configurations
│   └── others/            # Other editors (Vim, Sublime, etc.)
└── README.md              # This file
```

## What's Included

### 🤖 GitHub Copilot Files (`copilot/`)
- **Prompts**: **Universal prompts** that can be configured for any project type (web, mobile, desktop, API, etc.)
- **Instructions**: **Technology-agnostic coding standards** and best practices templates adaptable to any programming language
- **Modes**: **Flexible agent workflows** that can be customized for different development methodologies

### 🔧 MCP Toolset Files (`mcp/`)
- Tool configurations for extending Copilot with external capabilities
- Server and client configuration files
- Custom MCP tool implementations

### ⚙️ EditorConfig Files (`editorconfig/`)
- Consistent coding style configurations
- Language and framework-specific formatting rules
- Cross-editor compatibility settings

### 💻 IDE Configuration Exports (`ide-configs/`)
- **VS Code**: Settings, extensions, themes, and snippets
- **JetBrains**: IDE settings, live templates, and color schemes  
- **Others**: Configurations for Vim, Sublime Text, Emacs, and more

## Usage

1. **Browse** the relevant directory for your needs
2. **Configure** the template variables (marked with `{VARIABLE_NAME}`) to match your project
3. **Copy** or import configuration files into your development environment
4. **Customize** the templates by removing irrelevant sections and adding technology-specific content
5. **Follow** the README instructions in each directory for specific setup steps

### 🔧 Configuration Process

Most files in this repository are **templates** with configurable variables:
- Replace `{PROJECT_NAME}` with your actual project name
- Replace `{TECH_STACK}` with your technology stack (React, .NET, Python, etc.)
- Replace `{FRAMEWORK}` with your framework (Next.js, Spring Boot, FastAPI, etc.)
- Remove sections that don't apply to your project
- Add technology-specific patterns and examples

## 🌐 Supported Technologies

These templates have been designed to work with:

### Frontend Frameworks
- React, Vue.js, Angular, Svelte
- Blazor Server/WebAssembly
- Flutter, React Native

### Backend Technologies  
- .NET (ASP.NET Core, Web API, Minimal APIs)
- Node.js (Express, NestJS, Fastify)
- Python (Django, FastAPI, Flask)
- Java (Spring Boot, Quarkus)
- Go, Rust, PHP

### Databases
- SQL: PostgreSQL, MySQL, SQLite, SQL Server
- NoSQL: MongoDB, Redis, DynamoDB
- ORM/ODM: Entity Framework, Prisma, SQLAlchemy, Hibernate

### Cloud & DevOps
- Azure, AWS, Google Cloud
- Docker, Kubernetes
- GitHub Actions, Azure DevOps, Jenkins

## Contributing

Feel free to contribute additional configuration files, templates, or improvements to existing files. Please maintain the directory structure and include appropriate documentation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
