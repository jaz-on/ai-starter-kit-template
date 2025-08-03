# How to Write an Implementation Plan

## What is an Implementation Plan?
A detailed implementation plan for a complex feature, optimized for AI-assisted development.

## When to Use a Plan?
- Complex feature affecting multiple files
- Major architectural changes
- Major refactoring
- Integration of new technologies

## Plan Structure

### 1. Context
- Problem to solve
- Feature objectives
- Technical constraints

### 2. Proposed Solution
- Chosen technical approach
- Considered alternatives
- Choice justification

### 3. Implementation Plan
- Detailed steps
- Files to modify/create
- Dependencies between steps

### 4. Tests
- Test strategy
- Main test cases
- Regression tests

### 5. Risks and Mitigation
- Identified risks
- Mitigation plans
- Rollback points

## AI Tips
- Be specific in instructions
- Mention project conventions
- Reference existing documentation
- Break down into atomic steps

## Plan Template
Create a file in `_plans/` with this structure:

```markdown
# Plan: [Feature Name]

## Context
[Problem description]

## Solution
[Chosen approach]

## Implementation Steps
1. [Step 1]
2. [Step 2]
3. [etc.]

## Required Tests
- [Test 1]
- [Test 2]

## Validation
- [ ] Feature implemented
- [ ] Tests pass
- [ ] Documentation updated
```
