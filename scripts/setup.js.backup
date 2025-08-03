#!/usr/bin/env node

// scripts/setup.js
const fs = require('fs');
const path = require('path');

console.log('🤖 Configuration AI Starter Kit Template');
console.log('=====================================\n');

// Vérifier si les dossiers de configuration existent
const configDirs = [
  '.ai-config/examples/cursor-rules',
  '.ai-config/examples/vscode-settings',
  '.ai-config/examples/windsurf-rules'
];

console.log('📁 Vérification de la structure...');
configDirs.forEach(dir => {
  if (fs.existsSync(dir)) {
    console.log(`✅ ${dir}`);
  } else {
    console.log(`❌ ${dir} - À créer`);
  }
});

console.log('\n🚀 Prochaines étapes :');
console.log('1. Choisir votre IDE (Cursor, VS Code, Windsurf)');
console.log('2. Copier la configuration depuis .ai-config/examples/');
console.log('3. Modifier _context/project-brief.md avec votre projet');
console.log('4. Commencer à développer !');

console.log('\n📚 Documentation :');
console.log('- SETUP.md : Guide de configuration');
console.log('- _docs/onboarding.md : Guide d\'intégration');
console.log('- _context/project-brief.md : Brief du projet');

console.log('\n✨ Template prêt à l\'emploi !'); 