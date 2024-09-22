# Contributing to this repository.

Thank you for your interest in contributing to the project We appreciate your willingness to enhance this project, which aims to provide robust security measures for Linux servers* in alignment with the Security Technical Implementation Guides (STIGs), Security Requirements Guides (SRGs), and NIST 800-53 practices.

This document outlines the guidelines to help you contribute effectively and provide a collaborative environment.

## Table of Contents

- [Getting Started](#getting-started)
- [Code of Conduct](#code-of-conduct)
- [Issues and Feature Requests](#issues-and-feature-requests)
- [Making Contributions](#making-contributions)
- [Documentation](#documentation)
- [Testing](#testing)
- [Style Guide](#style-guide)
- [License](#license)

## Getting Started

1. **Fork the repository**: Click on the "Fork" button in the upper right corner of the repository page.
2. **Clone your fork**: Use the following command to clone your copy of the repository to your local machine:

   ```bash
   git clone https://github.com/YOUR-USERNAME/STIG-NIST-800-53-Compliance-Playbook-for-Ubuntu-Server.git
   ```

3. **Navigate into the directory**:

   ```bash
   cd STIG-NIST-800-53-Compliance-Playbook-for-Ubuntu-Server
   ```

4. **Create a new branch**: Always create a new branch for your contributions by using the following command, replacing `feature-branch-name` with a descriptive name:

   ```bash
   git checkout -b feature-branch-name
   ```

## Code of Conduct

We expect all contributors to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please ensure respectful and constructive dialogue and collaboration within our community. 

## Issues and Feature Requests

Before making changes or initiating a large contribution, check if an issue exists that informs your work. You can view existing issues or create a new one in the [issues tab](https://github.com/EvE-Player/STIG-NIST-800-53-Compliance-Playbook-for-Ubuntu-Server/issues).

When reporting issues, please provide as much detail as possible, including:
- Steps to reproduce the issue
- Expected vs actual behavior
- Context of your environment (OS, Ansible version, etc.)

For feature requests, please describe the feature in detail, including potential implementations and use cases.

## Making Contributions

### Contributions Types

You can contribute by:
- **Implementing Features**: Enhancing the Ansible playbooks or roles by adding new functionalities.
- **Fixing Bugs**: Resolving issues identified in the current Ansible scripts.
- **Improving Documentation**: Clarifying existing documentation or adding new sections for better understanding.
- **Testing Roles**: Running and testing playbooks to ensure the compliance of STIGs, SRGs, or NIST 800-53 practices.

### Guidelines for Contributions

- Please ensure your code is written in Ansible best practices.
- Ensure to document any new features or modifications in the README or relevant documentation.
- Commit messages should be clear and descriptive, following a format like:

  ```
  [Type]: Brief description of changes
  ```

  where **Type** can be one of the following:
  - `Fix`: for bug fixes
  - `Add`: for adding functionalities
  - `Update`: for changes to existing features
  - `Docs`: for documentation updates

Once you’ve made and committed your changes, push your branch back to your fork:

```bash
git push origin feature-branch-name
```

After pushing, you can create a pull request through the GitHub interface.

## Documentation

Documentation is crucial for the usability and maintainability of the project. If you are making changes that affect usage, please update the following:
- README.md: Provide a clear description of any new features.
- Any other relevant markdown files or code comments that clarify how to use your contributions.

## Testing

Before submitting your changes, please run tests to ensure no existing functionality is broken. The testing suite can usually be run with:

```bash
ansible-playbook playbook.yml --check
```

Make sure that all tests pass before you submit your pull request.

## Style Guide

When writing your Ansible playbooks, please adhere to the following style guidelines:
- Use YAML syntax rules properly and ensure proper indentation.
- Use descriptive variable names for clarity.
- Keep playbooks modular by using roles where applicable.

## License

By contributing to this project, you agree that your contributions will be licensed under the [GNU General Public License v3.0](LICENSE).

---

Thank you for contributing to the project! Your contributions can help to create a more secure environment for Linux based* servers, ensuring compliance with essential security frameworks.
