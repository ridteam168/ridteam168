# Zenmed RID Programming Working Instruction

> Standardization for collaborations and documentations in code/programming related fields

## List of Contents
1. [General](#general)
2. [Conventional Commits](#conventional-commits)
3. [Workflow](#workflow)
4. [Documentation](#documentation)

## General
- Language : English
- Git Remote Platform : [Github](https://github.com/)
- Commit Typing :  [Conventional Commits](https://www.conventionalcommits.org/)

## Conventional Commits

```
<type of code change>: <commit message>
```

### Type of code change
- **feat**: The new feature you're adding to a particular application
- **fix**: A bug fix
- **style**: Feature and updates related to styling
- **refactor**: Refactoring a specific section of the codebase
- **test**: Everything related to testing
- **docs**: Everything related to documentation
- **chore**: Regular code maintenance.[ You can also use emojis to represent commit types]

### Example
- docs: adding details of automark parameters
- feat: small object filter by thresholding contour area
- fix: is inside bug cause by scaling
- refactor: move the method and calibrator in a folder

## Workflow
### New Project
1. Make a new repository for the project. Repository naming rules:
    - use underscore as spacing
    - use lowercase
    - 
2. Set repository as private if it declared not open for public
3. Add peoples who will be working on the project as collaborators
4. Add repository name and link to [profile page README.md](https://github.com/ridteam168/ridteam168/blob/main/README.md) (necessary to improve project maintainability)
5. Make first commit and push to main branch
6. Make a new branch named with developer name or feature name
7. During development collaborators push code to their respective branches
8. Only project lead or team who assigned as the person in charge of the project who doing `pull` and `push` to main branch

### Existing Project
1. Ask for project access as collaborator to project lead or team who assigned as the person in charge of the project
2. Make a new branch named with developer name or feature name
3. During development collaborators push code to their respective branches
4. Only project lead or team who assigned as the person in charge of the project who doing `pull` and `push` to main branch

## Documentation
For now we only use project level documentation using a README file in each project. There is no specific rules for documentation format, but at least it contains:
- Project title
- Project description
- Technology used in the project (programming languages, frameworks, packages, methods, etc)
- How to use intructions

### What should we do after documenting
- Documentation should be a continuous process along with code development, just like testing.
- Do systematic code reviews, including formal code reviews targeted at inspecting the documentation.