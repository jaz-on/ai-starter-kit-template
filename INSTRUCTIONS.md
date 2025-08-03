# AI Starter Kit - Instructions for AI

## Required Reading
Always read `_docs/onboarding.md` first, then select relevant documents.

## Internal Documentation

### Frequently consulted procedures
- `_docs/code-style-guidelines.md` - READ BEFORE ANY CODING
- `_context/current-state.md` - Current project state
- `_context/next-steps.md` - Planned next steps

### Additional procedures
- `_docs/how-to-plan.md` - How to write an implementation plan
- `_docs/refactoring-principles.md` - Refactoring principles
- `_docs/optimization-principles.md` - Optimization principles based on InstaFed analysis

### Project documentation
- `_context/project-brief.md` - Initial brief and objectives
- `README.md` - Main technical documentation

## Internationalization Guidelines Internationalization Guidelines

### Language Preferences for AI Communication

**For code and technical documentation:**
- Use **English** for all code comments, variable names, and technical documentation
- Use **English** for commit messages and pull request descriptions
- Use **English** for API documentation and technical specifications

**For project documentation and context:**
- Use **English** for project briefs, business requirements, and user-facing documentation
- Use **English** for planning documents and project management
- Use **English** for user stories and acceptance criteria
- **Exception**: Use local language (French in our case) for context or documentation if the project is not international or for contributor convenience

**For AI interactions:**
- **Claude/ChatGPT**: Use the language that best matches your project context
- **GitHub Copilot**: Prefer English for code suggestions
- **Cursor AI**: Can work in both languages, but English is more reliable for code generation

### File Language Standards

| File Type | Primary Language | Notes |
|-----------|-----------------|-------|
| README.md | Bilingual (EN/FR) | English first, then French |
| INSTRUCTIONS.md | English | Technical instructions |
| SETUP.md | English | Configuration guides |
| _context/*.md | English | Project context and briefs |
| _docs/*.md | English | Technical documentation |
| Code files | English | Comments and documentation |
| package.json | English | Standard format |
| .gitignore | English | Standard format |

### Best Practices

1. **Consistency**: Choose one language per file type and stick to it
2. **Context**: Use the language that best serves the intended audience
3. **AI Optimization**: Consider which language works best with your AI tools
4. **Documentation**: Keep language choices documented and consistent across the project
5. **Flexibility**: Allow local language for convenience when project is not international

### Migration Guidelines

When converting existing files:
1. Start with the most important files (README, INSTRUCTIONS)
2. Update file headers to indicate language preference
3. Add language indicators in file names if needed (e.g., `README_en.md`, `README_fr.md`)
4. Update all cross-references and links

## Optimization Guidelines (Based on InstaFed Analysis)

### KISS Principle
- **Simplicity first** : Avoid unnecessary complexity
- **Readable code** : Prioritize clarity over cleverness
- **Direct functionality** : Every line of code should have a clear purpose

### Modular Architecture
- **Specialized modules** : EventManager, DOMUtils, ValidationUtils, ErrorHandler
- **Separation of concerns** : Each module has a specific function
- **Reusable components** : Create functions that can be used multiple times

### Performance Optimization
- **Smart cache** : Avoid repeated DOM queries
- **Memory management** : Automatic cleanup of resources
- **Error handling** : Advanced error recovery systems

### Quality Metrics
- **Code size** : Target 25-30% reduction
- **Global functions** : Target 40% reduction
- **DOM queries** : Target 60% reduction
- **Memory usage** : Target 40% reduction
