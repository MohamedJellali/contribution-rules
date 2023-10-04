# contribution-rules
## Project
A brief description

## How to start

```bash
# How to start
```

## Contributing

To ensure a smooth collaboration, please follow these guidelines when contributing:

### Getting Started

1. Fork the repository and clone it locally.
2. Create a new branch for your feature or bug fix: [Check the branches naming convetion](#branch)
3. Make your changes: Ensure your code adheres to the [airbnb open source style guide](https://github.com/airbnb/javascript).
4. Test your changes thoroughly to ensure they don't introduce any issues.

<a id="commit"></a>
### Committing Changes

Please commit your changes with a clear and descriptive message and use one of the following prefixes to provide clarity on the nature of the changes made:

- feat: Use this prefix when introducing a new feature.
- fix: Use this prefix when addressing a bug and providing a fix.
- docs: Use this prefix for changes that solely involve documentation.
- style: Use this prefix for code changes that do not affect the functionality but relate to - formatting, white-space, or similar aspects.
- refact: Use this prefix for code changes that neither fix a bug nor introduce a new feature but involve modifications or restructuring.
- perf: Use this prefix for code changes aimed at improving performance.
- test: Use this prefix when adding missing tests.
- chore: Use this prefix for changes related to the build process or auxiliary tools and libraries, such as documentation generation.

Example : `git commit -m -s "feat: your feature description"` or `git commit -m -s "fix: your bugfix description"`.

### Pull Request Processus

1. Ensure that your branch is up to date with the latest changes from the main branch : performing a `git pull`.
2. Resolve the conflicts and commit your changes by following the steps mentioned in the [committing changes](#commit).
3. Push the code to your Branch; example : `git push origin feature/jdo-add-login-page`.
4. Open a Pull Request.

<a id="branch"></a>
### Branches naming convention

Please ensure to name your branch as following : 

1. Feature Branches: `git checkout -b feature/trigram-your-feature`.
2. Bugfix Branches: `git checkout -b fix/trigram-your-bugfix`.
3. Test Branches: `git checkout -b test/trigram-your-test`.
4. Refactor Branches: `git checkout -b refactor/trigram-your-refactor`.
5. Documentation Branches: `git checkout -b docs/trigram-your-refactor`.
6. Release Branches: `git checkout -b release/trigram-version`.

-The `trigram` of a name consists of the first letter of the first name followed by the first and second letters of the last name. For example, the trigram of `John Doe` is `jdo`.

-Example of branch naming : `feature/jdo-add-login-page`

### Code Review

- Ensure your code adheres to the [airbnb open source style guide](https://github.com/airbnb/javascript).
- Write clear and concise commit messages.
- Provide relevant documentation and tests for your changes.

### Reporting Issues

[Back to Top](#top)

