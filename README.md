# AI Starter Kit Template

Generic template for AI-assisted development.


> **Note:** This repository is maintained by a French developer. For practical reasons, most files are in English, but the template is designed to support both English and French projects. See [INTERNATIONALIZATION.md](INTERNATIONALIZATION.md) for detailed language guidelines.
---

## 📋 Table of Contents

- [AI Starter Kit Template](#ai-starter-kit-template)
  - [📋 Table of Contents](#-table-of-contents)
- [English Version](#english-version)
  - [🚀 Quick Start](#-quick-start)
  - [📁 Project Structure](#-project-structure)
  - [🤖 AI-Assisted Development](#-ai-assisted-development)
    - [IDEs](#ides)
    - [LLMs](#llms)
  - [📚 Documentation](#-documentation)
  - [🛠 Features](#-features)
  - [🎯 Usage](#-usage)
    - [Creating a new project](#creating-a-new-project)
    - [Cursor configuration](#cursor-configuration)
    - [VS Code configuration](#vs-code-configuration)
  - [🤝 Contributing](#-contributing)
  - [📚 References](#-references)
    - [Primary source](#primary-source)
  - [📄 License](#-license)
- [Version Française](#version-française)
  - [🚀 Démarrage rapide](#-démarrage-rapide)
  - [📁 Structure du projet](#-structure-du-projet)
  - [🤖 Développement assisté par IA](#-développement-assisté-par-ia)
    - [IDEs](#ides-1)
    - [LLMs](#llms-1)
  - [📚 Documentation](#-documentation-1)
  - [🛠 Fonctionnalités](#-fonctionnalités)
  - [🎯 Utilisation](#-utilisation)
    - [Création d'un nouveau projet](#création-dun-nouveau-projet)
    - [Configuration Cursor](#configuration-cursor)
    - [Configuration VS Code](#configuration-vs-code)
  - [🤝 Contribution](#-contribution)
  - [📚 Références](#-références)
    - [Source principale](#source-principale)
  - [📄 Licence](#-licence)

---

# English Version

Generic template for AI-assisted development.

## 🚀 Quick Start

1. **Use this template** : Click "Use this template" on GitHub
2. **Choose your configuration** : See `SETUP.md`
3. **Configure your IDE** : Copy from `.ai-config/examples/`
4. **Start developing** !

## 📁 Project Structure

```
ai-starter-kit/
├── .ai-config/             # Configurations for different IDEs
│   └── examples/           # Examples Cursor, VS Code, Windsurf
├── _docs/                  # Project documentation
├── _plans/                 # Implementation plans
├── _context/              # Context for AI
├── src/                   # Source code
├── INSTRUCTIONS.md        # Instructions for AI
└── SETUP.md              # Configuration guide
```

## 🤖 AI-Assisted Development

This template is optimized to work with :

### IDEs
- **Cursor** (recommended) - Integrated AI
- **VS Code + Copilot** - Large ecosystem
- **Windsurf** - New AI player

### LLMs
- **Claude** - Excellent for architecture
- **ChatGPT** - Versatile and accessible
- **GitHub Copilot** - Native integration

## 📚 Documentation

- [`SETUP.md`](SETUP.md) : Configuration guide
- [`_docs/onboarding.md`](_docs/onboarding.md) : Integration guide
- [`_context/project-brief.md`](_context/project-brief.md) : Project brief

## 🛠 Features

- ✅ Universal project structure
- ✅ Multi-IDE configurations
- ✅ AI-optimized documentation
- ✅ Standardized workflow
- ✅ Plan templates
- ✅ Persistent context management

## 🎯 Usage

### Creating a new project
```bash
gh repo create my-project --template jaz-on/ai-starter-kit-template --private --clone
cd my-project
```

### Cursor configuration
```bash
cp -r .ai-config/examples/cursor-rules/ .cursor/rules/
```

### VS Code configuration
```bash
cp -r .ai-config/examples/vscode-settings/ .vscode/
```

## 🤝 Contributing

This template is generic and adaptable. Feel free to :
- Propose new IDE configurations
- Improve documentation
- Add plan examples
- Share your adaptations

## 📚 References

### Primary source
This template is inspired by ["Vibe Coder sur Visual Studio Code avec Copilot"](https://www.alsacreations.com/tuto/lire/1956-Vibe-Coder-sur-Visual-Studio-Code-avec-Copilot.html) (post in French) by the Alsacréations team, a structured and proven methodology for AI-assisted development.

## 📄 License

MIT - Use freely for your projects !

---

# Version Française

Template générique pour le développement assisté par intelligence artificielle.

## 🚀 Démarrage rapide

1. **Utiliser ce template** : Cliquer sur "Use this template" sur GitHub
2. **Choisir votre configuration** : Voir `SETUP.md`
3. **Configurer votre IDE** : Copier depuis `.ai-config/examples/`
4. **Commencer à développer** !

## 📁 Structure du projet

```
ai-starter-kit/
├── .ai-config/             # Configurations pour différents IDEs
│   └── examples/           # Exemples Cursor, VS Code, Windsurf
├── _docs/                  # Documentation du projet
├── _plans/                 # Plans d'implémentation
├── _context/              # Contexte pour l'IA
├── src/                   # Code source
├── INSTRUCTIONS.md        # Instructions pour l'IA
└── SETUP.md              # Guide de configuration
```

## 🤖 Développement assisté par IA

Ce template est optimisé pour travailler avec :

### IDEs
- **Cursor** (recommandé) - IA intégrée
- **VS Code + Copilot** - Large écosystème
- **Windsurf** - Nouveau player IA

### LLMs
- **Claude** - Excellent pour l'architecture
- **ChatGPT** - Polyvalent et accessible
- **GitHub Copilot** - Intégration native

## 📚 Documentation

- [`SETUP.md`](SETUP.md) : Guide de configuration
- [`_docs/onboarding.md`](_docs/onboarding.md) : Guide d'intégration
- [`_context/project-brief.md`](_context/project-brief.md) : Brief du projet

## 🛠 Fonctionnalités

- ✅ Structure projet universelle
- ✅ Configurations multi-IDEs
- ✅ Documentation optimisée IA
- ✅ Workflow standardisé
- ✅ Templates de plans
- ✅ Gestion de contexte persistant

## 🎯 Utilisation

### Création d'un nouveau projet
```bash
gh repo create mon-projet --template jaz-on/ai-starter-kit-template --private --clone
cd mon-projet
```

### Configuration Cursor
```bash
cp -r .ai-config/examples/cursor-rules/ .cursor/rules/
```

### Configuration VS Code
```bash
cp -r .ai-config/examples/vscode-settings/ .vscode/
```

## 🤝 Contribution

Ce template est générique et adaptable. N'hésitez pas à :
- Proposer de nouvelles configurations IDE
- Améliorer la documentation
- Ajouter des exemples de plans
- Partager vos adaptations

## 📚 Références

### Source principale
Ce template s'inspire de ["Vibe Coder sur Visual Studio Code avec Copilot"](https://www.alsacreations.com/tuto/lire/1956-Vibe-Coder-sur-Visual-Studio-Code-avec-Copilot.html) par l'équipe Alsacréations, une méthodologie structurée et éprouvée pour le développement assisté par IA.

## 📄 Licence

MIT - Utilisez librement pour vos projets !

---
*Template créé pour optimiser le développement assisté par IA*
