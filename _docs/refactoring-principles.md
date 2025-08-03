# Principes de refactoring - AI Starter Kit

## Single Responsibility Principle (SRP)
Chaque fonction, classe ou module doit avoir une seule raison de changer.
Les grandes fonctions avec des commentaires inline doivent être décomposées en petites fonctions bien nommées.

## Don't Repeat Yourself (DRY)
Éviter la duplication de code. Extraire les parties communes dans des fonctions réutilisables.

## You Aren't Gonna Need It (YAGNI)
Ne pas implémenter de fonctionnalités tant qu'elles ne sont pas nécessaires.

## Keep It Simple, Stupid (KISS)
Privilégier les solutions simples et compréhensibles.

## Refactoring avec IA
- Demander à l'IA d'identifier les code smells
- Utiliser l'IA pour proposer des refactorings
- Garder le contrôle des décisions architecturales importantes

## Refactoring continu
- Refactoriser régulièrement lors du développement
- Ne pas attendre que le code soit "parfait"
- Utiliser les tests pour sécuriser les refactorings

## Signaux d'alarme
- Fonctions de plus de 50 lignes
- Code dupliqué
- Variables mal nommées
- Commentaires qui expliquent ce que fait le code