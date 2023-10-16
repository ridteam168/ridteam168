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
- **build**: The commit alters the build system or external dependencies of the product (adding, removing, or upgrading dependencies).

- **change**: The commit changes the implementation of an existing feature.

- **chore**: The commit includes a technical or preventative maintenance task that is necessary for managing the product or the repository, but it is not tied to any specific feature or user story. For example, releasing the product can be considered a chore. Regenerating generated code that must be included in the repository could be a chore.

- **ci**: The commit makes changes to continuous integration or continuous delivery scripts or configuration files.

- **deprecate**: The commit deprecates existing functionality, but does not remove it from the product. For example, sometimes older public APIs may get deprecated because newer, more efficient APIs are available. Removing the APIs could break existing integrations so the APIs may be marked as deprecated in order to encourage the integration developers to migrate to the newer APIs while also giving them time before removing older functionality.

- **docs**: The commit adds, updates, or revises documentation that is stored in the repository.

- **feat**: The commit implements a new feature for the application.

- **fix**: The commit fixes a defect in the application.

- **perf**: The commit improves the performance of algorithms or general execution time of the product, but does not fundamentally change an existing feature.

- **refactor**: The commit refactors existing code in the product, but does not alter or change existing behavior in the product.

- **remove**: The commit removes a feature from the product. Typically features are deprecated first for a period of time before being removed. Removing a feature from the product may be considered a breaking change that will require a major version number increment.

- **revert**: The commit reverts one or more commits that were previously included in the product, but were accidentally merged or serious issues were discovered that required their removal from the main branch.

- **security**: The commit improves the security of the product or resolves a security issue that has been reported.

- **style**: The commit updates or reformats the style of the source code, but does not otherwise change the product implementation.

- **test**: The commit enhances, adds to, revised, or otherwise changes the suite of automated tests for the product.


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
    - use concise words
    - not more than 50 characters
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