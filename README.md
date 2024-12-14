# Awesome WindsurfRules [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> This project is a fork of [awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules), specifically adapted for Windsurf. The main difference is the support for global rules in Windsurf, which is reflected in the modified directory structure. While workspace rules are forked from the original project, the global rules feature is unique to this implementation.

A curated list of awesome .windsurfrules files for enhancing your Windsurf experience.

[Windsurf](https://codeium.com/windsurf) is an AI-powered code editor. `.windsurfrules` files define custom rules for Windsurf to follow when generating code, allowing you to tailor its behavior to your specific needs and preferences.

## Why .windsurfrules?

`.windsurfrules` is a powerful feature in Windsurf that allows developers to define project-specific instructions for the AI. Here's why you might want to use it:

1. **Customized AI Behavior**: `.windsurfrules` files help tailor the AI's responses to your project's specific needs, ensuring more relevant and accurate code suggestions.

2. **Consistency**: By defining coding standards and best practices in your `.windsurfrules` file, you can ensure that the AI generates code that aligns with your project's style guidelines.

3. **Context Awareness**: You can provide the AI with important context about your project, such as commonly used methods, architectural decisions, or specific libraries, leading to more informed code generation.

4. **Improved Productivity**: With well-defined rules, the AI can generate code that requires less manual editing, speeding up your development process.

5. **Team Alignment**: For team projects, a shared `.windsurfrules` file ensures that all team members receive consistent AI assistance, promoting cohesion in coding practices.

6. **Project-Specific Knowledge**: You can include information about your project's structure, dependencies, or unique requirements, helping the AI to provide more accurate and relevant suggestions.

By creating a `.windsurfrules` file in your project's root directory, you can leverage these benefits and enhance your coding experience with Windsurf AI.

## Content

### Global Rules
Global rules are a unique feature in Windsurf that apply across all projects. They are organized in the following structure:

- **global_rules/** - Root directory for global rules
  - [**language/**](./rules/global_rules/global-en-language)
    - English-only responses
    - Localization preferences
  - [**commit-message/**](./rules/global_rules/global-commit-message)
    - Standard prefixes (feat, fix, docs, etc.)
    - Message structure guidelines

### Workspace Rules
Workspace rules are specific to each project and are organized in the following structure:

- **workspace_rules/** - Root directory for workspace rules
  - [**lorem/**](./rules/workspace_rules/#)

## Directories

## How to Use
1. Install [Windsurf](https://codeium.com/windsurf) if you haven't already.
2. Browse the rules above to find a `.windsurfrules` file that suits your needs.
3. Copy the chosen `.windsurfrules` file to your project's root directory.
4. Customize the rules as needed for your specific project requirements.


## Contributing

Contributions are welcome! If you have a great `.windsurfrules` file to share:

1. Fork this repository.
2. Create a new folder in the `global_rules` or `workspace_rules` directory. The folder name should follow this pattern:
   `technology-focus-windsurfrules-prompt-file`
   For example: `react-typescript-windsurfrules-prompt-file`
3. Add your `global_rules.md` or `.windsurfrules` file to the new folder.
4. Optionally, include a README.md in the folder to provide credit and a brief description.
5. Update the main README.md file, adding your contribution to the appropriate category.
6. Ensure your contribution follows the guidelines in the [`.windsurfrules`](./.windsurfrules) file at the root of this repository.
7. Submit a pull request.

Please ensure your contribution is original or properly credited if based on existing work. Refer to the `global_rules.md` or `.windsurfrules` file in the root of this repository for detailed guidelines on formatting, naming conventions, and best practices for contributions.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
