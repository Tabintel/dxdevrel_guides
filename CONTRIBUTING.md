# Contributing to DxDevRel Guides

Thanks you for taking the time to contribute! Contributions are always welcome, no matter how large or small!

Here are some guidelines to help you:

We want this community to be friendly and respectful to each other. Please follow it in all your interactions with the project. Before contributing, please read the [code of conduct](./CODE_OF_CONDUCT.md).

## Get Started

1. **Fork the repository**: Create a personal copy of the repo by clicking the fork button.

2. **Clone your fork**:

   ```bash
   git clone https://github.com/yourusername/dx-devrel-guide.git
   ```

3. **Install the Mintlify CLI**: To work locally with your documentation, install the Mintlify Command Line Interface (CLI) by running the following command in your terminal.

   ```bash
    npm i -g mintlify
   ```

4. **Create a branch after picking an issue**: Work on a new feature or fix in a separate branch.

   ```bash
   git checkout -b feat/your-feature-name
   ```

5. **Run Locally to view changes**: Run the below command to see changes you made locally

    ```bash
       mintlify dev
     ```


##  Writing Content

- Follow the file naming conventions: `lowercase-with-dashes.mdx`
- Use `---` frontmatter for the title, e.g.:

```mdx
---
title: Developer Advocacy
---

## Public Speaking
...
```
    
## Submitting Changes

1. **Test your changes**: Ensure that all existing and new tests pass.
2. **Commit**: Write meaningful commit messages.
   ```bash
   git commit -m "Fix: short description of the fix"
   ```
3. **Push your branch**:
   ```bash
   git push origin feat/your-feature
   ```

4. **Open a Pull Request**: Once your changes are ready, submit a pull request.



## Commit message convention

We follow the [conventional commits specification](https://www.conventionalcommits.org/en) for our commit messages:

- `fix`: bug fixes, e.g. fix crash due to deprecated method.
- `feat`: new features, e.g. add new method to the module.
- `refactor`: code refactor, e.g. migrate from class components to hooks.
- `docs`: changes into documentation, e.g. add usage example for the module..
- `test`: adding or updating tests, e.g. add integration tests using detox.
- `chore`: tooling changes, e.g. change CI config.



## Sending a Pull request (PR)

> **Working on your first pull request?** You can learn how from this _free_ series: [How to Contribute to an Open Source Project on GitHub](https://app.egghead.io/playlists/how-to-contribute-to-an-open-source-project-on-github).

When you're sending a pull request:

- Prefer small pull requests focused on one change.
- Verify that linters are passing.
- Review the documentation to make sure it looks good.
- Follow the pull request template when opening a pull request.
- For pull requests that change the API or implementation, discuss with maintainers first by opening an issue.


## Style Guidelines

- Follow the existing code style.
- Ensure all new code is properly commented.


## Reporting Issues

- Use [Issues](https://github.com/Tabintel/dxdevrel_guides/issues) to report bugs or request features.
- Provide a detailed description and steps to reproduce (if applicable).
