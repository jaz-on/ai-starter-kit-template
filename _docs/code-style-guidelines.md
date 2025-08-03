# Code Style Guidelines - AI Starter Kit

## General Rules
- Use descriptive variable names
- Functions maximum 50 lines
- Single indentation level per function when possible
- Avoid comments that repeat the code

## Naming
- Variables: camelCase
- Functions: camelCase with action verbs
- Constants: UPPER_SNAKE_CASE
- Classes: PascalCase

## File Structure
- Maximum 200 lines per file
- Group imports at the top
- Export at the bottom of the file

## Comments
- Explain the "why", not the "how"
- Use standard language documentation
- Avoid redundant comments

## AI Principles
- Write self-documenting code
- Use explicit names to help AI understand context
- Structure code logically to facilitate AI assistance

## KISS Principle (Keep It Simple, Stupid)
- **Simplicity first** : Avoid unnecessary complexity
- **Readable code** : Prioritize clarity over cleverness
- **Direct functionality** : Every line of code should have a clear purpose
- **Easy maintenance** : Code should be easy to understand and modify

## Modularity and Reusability
- **Specialized modules** : Divide code into coherent logical units
- **Pure functions** : Create reusable and testable functions
- **Composition** : Assemble simple components rather than creating monoliths
- **Separation of concerns** : Each module has a specific function

## Performance Optimizations
- **Smart cache** : Avoid repeated DOM queries
- **Memory management** : Automatic cleanup of resources
- **Optimized rendering** : Minimal visual effects
- **Robust validation** : Data verification

## Error Handling
- **Error types** : NETWORK, VALIDATION, PROCESSING, MEMORY
- **Automatic recovery** based on error type
- **User-friendly messages** : Clear and adapted explanations
- **Detailed logging** for debugging

## Avoid Common Pitfalls
- **Minimal dependencies** : Critically evaluate each dependency
- **Unnecessary complexity** : Simple solutions and appropriate patterns
- **Code obesity** : Short functions and elimination of redundancies
- **Over-engineering** : Prefer native solutions
