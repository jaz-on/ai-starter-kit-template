# 🤖 Configuration IA pour le développement

## 🎯 Choisissez votre configuration

### IDEs populaires

#### Cursor IDE (recommandé pour l'IA)
```bash
# Copier la configuration Cursor
cp -r .ai-config/examples/cursor-rules/ .cursor/rules/
```
- ✅ Intelligence artificielle intégrée
- ✅ Compréhension de contexte multi-fichiers
- ✅ Configuration avec fichiers `.mdc`

#### VS Code + Copilot
```bash
# Copier la configuration VS Code
cp -r .ai-config/examples/vscode-settings/ .vscode/
```
- ✅ Large écosystème d'extensions
- ✅ GitHub Copilot intégré
- ✅ Configuration avec `settings.json`

#### Windsurf (nouveau)
```bash
# Adapter selon votre configuration Windsurf
# Voir .ai-config/examples/windsurf-rules/
```

### LLMs populaires

#### Claude (Anthropic)
- Lire `_context/` comme contexte
- Utiliser `INSTRUCTIONS.md` comme guide
- Excellent pour planification et architecture

#### ChatGPT (OpenAI)  
- Adapter les prompts dans `_context/`
- Peut lire les fichiers du projet
- Bon pour debugging et optimisation

#### GitHub Copilot
- Utilise la documentation comme contexte automatiquement
- Suggestions inline dans l'IDE
- Intégration native avec VS Code

## 🚀 Configuration rapide

### Étape 1 : Choisir l'IDE
Copiez la configuration de votre IDE depuis `.ai-config/examples/`

### Étape 2 : Adapter le contexte
Modifiez `_context/project-brief.md` avec votre projet

### Étape 3 : Commencer à développer
Votre IA aura accès à toute la documentation structurée !