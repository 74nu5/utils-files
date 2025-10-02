# EditorConfig Files

This directory contains **universal `.editorconfig` templates** that can be customized for any programming language, framework, and development team preferences.

## 🎯 About EditorConfig

EditorConfig ensures consistent coding styles across different editors and IDEs by defining formatting rules that work universally:

- **Indentation**: Spaces vs tabs, indentation size
- **Line Endings**: Unix (LF), Windows (CRLF), or Mac (CR)
- **Character Encoding**: UTF-8, UTF-16, etc.
- **Whitespace**: Trailing whitespace and final newline handling
- **File Extensions**: Language-specific rules

## 📁 Template Organization

- **`general.editorconfig`**: Universal template with configurable sections for any language
- **Technology-Specific Sections**: Pre-configured rules for popular languages and frameworks
- **Customizable Variables**: Easy-to-modify settings for team preferences

## 🔧 Configuration Process

1. **Copy** `general.editorconfig` to your project root as `.editorconfig`
2. **Enable/Disable** sections based on your technology stack:
   ```ini
   # Uncomment sections you need:
   # [*.cs]          # C# files
   # [*.{js,ts}]     # JavaScript/TypeScript files  
   # [*.py]          # Python files
   # [*.java]        # Java files
   ```
3. **Customize** settings to match your team preferences:
   - Indent size: 2, 4, or 8 spaces
   - Line endings: `lf`, `crlf`, or `cr`
   - Trailing whitespace: `true` or `false`

## 🌐 Supported Languages & Frameworks

### Programming Languages
- **C#**: .NET, ASP.NET Core, Blazor, WPF
- **JavaScript/TypeScript**: React, Vue, Angular, Node.js
- **Python**: Django, FastAPI, Flask, Jupyter notebooks
- **Java**: Spring Boot, Maven, Gradle projects
- **Go**: Standard Go projects and modules
- **Rust**: Cargo projects and workspaces
- **PHP**: Laravel, Symfony, WordPress

### Configuration Files
- **JSON**: Package.json, tsconfig.json, etc.
- **YAML**: Docker Compose, GitHub Actions, Kubernetes
- **XML**: Maven POM, MSBuild, Android layouts
- **Markdown**: Documentation, README files

## ✨ Benefits

- **Cross-Editor Compatibility**: Works with VS Code, JetBrains IDEs, Vim, Sublime Text
- **Team Consistency**: Ensures all developers use the same formatting rules
- **CI/CD Integration**: Automated style checking in build pipelines
- **Language Agnostic**: One file covers multiple languages in polyglot projects