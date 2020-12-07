# Contributing to Isometric UI

Isometric UI is an opinionated open-source project. We want anyone regardless of their knowledge or experience level to contribute to our project whether it's giving feedback, reporting a bug, ideation on the conceptual techniques or contributing to the codebase with new features, bug fixes and so on.

## Code of Conduct

We want to make contributing to this project as easy and transparent as possible, to achieve this we expect our community members to follow our Code of Conduct. Please read the [full text of Code of Conduct](CODE_OF_CONDUCT.md) so that you can understand what actions will or will not tolerated.

## Development Process

We use Github as the central repository of our codebase. We'll also use Github to track issues, feature requests and reviewing code-contributions through pull requests.

## Issues

We use GitHub issues to track bugs. Please make sure your description is clear and concise and has sufficient instructions to be able to reproduce the issue. If possible please provide a minimal demo of the problem (even if your use-case may include a more complicated setup).

## Issue Triage

We use Github Issues and labeling feature to ensure that anyone can browse related topics easily, which is especially crucial for maintainers.

Here is a list of labels we use and their description:

- `support`: Request a help for your specific use case, which is not an issue with the project itself (otherwise use `bug-report` or `feature-request`).
- `bug-report`: Report a bug with the project itself.
- `security`: Report a security issue, so it can be prioritized accordingly.
- `feature-request`: Request or discuss a new feature or change in fundamental techniques used in the project.
- `documentation`: Report a problem or request a detailed information about documentation, whether it's specific to a section or related to just one sentence. If you think you can help with the documentation, please contribute by opening a new Pull Request.

## Pull Requests

- Fork the repo and create your branch from `main`
- Add tests for any code changes that needs to be tested
- Update the documentation for any changes that needs to be documented
- Ensure the test suite passes.
- Ensure code linting passes.

## Naming Conventions

Our published npm packages uses the so-called "kebab-case" for it's naming. React component packages prefixed with `react`. We use PascalCase for component naming, including the function and file names. We use camelCase for CSS class names and CSS Modules object keys. CSS convention is to use kebap-case for CSS rules, this convention is invalid in JavaScript as a variable name when CSS Modules used. Our bundler uses CSS Modules options to convert all `kebap-case`d class names into `camelCase`d class names for compatibility. This gives you an opportunity to use CSS convention in CSS files, and keep JS convention in JS files.

- `kebab-case`: Package name. Optionally CSS class names in CSS files.
- `PascalCase`: Component name, function name, component and style filenames.
- `camelCase`: CSS class names.

## Coding Style & Conventions

We use ESLint and Prettier to ensure consistenty in our codebase.

## License

By contributing, you agree that your contributions will be licensed under its MIT License.
