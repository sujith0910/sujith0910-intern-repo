# Branching & Team Collaboration

## Why is pushing directly to main problematic?

Pushing directly to the main branch can be risky because any bugs, incomplete features, or accidental mistakes immediately affect the shared codebase. In team environments, this can break the application for other developers and make collaboration more difficult. It also reduces the opportunity for proper testing and code review before changes are added to the main project.

---

## How do branches help with reviewing code?

Branches allow developers to work on features or fixes separately without affecting the main branch. This makes it easier to test changes safely and review code before merging it into the main project. Team members can provide feedback, identify issues, and suggest improvements during the review process.

Branches also help developers organise work more clearly because each feature or bug fix can have its own branch.

---

## What happens if two people edit the same file on different branches?

If two people modify the same part of a file on different branches, a merge conflict can happen when combining the branches. Git will ask the developers to manually review and choose which changes should be kept. This helps prevent accidental overwriting of someone else’s work.

---

## Reflection

This task helped me understand why branches are important in collaborative software development. Using branches keeps the main codebase stable while allowing developers to work independently on different tasks. It also showed how Git helps manage changes safely when multiple people are working on the same project.