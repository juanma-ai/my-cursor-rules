# Awesome Cursor Rules

A curated collection of `.mdc` files for enhancing your Cursor AI development experience.

## Why Cursor Rules?

Cursor Rules (`.mdc` files) are a powerful way to customize and enhance your Cursor AI experience. They provide project-specific instructions and guidelines that help Cursor AI better understand your codebase and generate more relevant and accurate code.

## File Structure

All rule files are stored in the `.cursor/rules/` directory and follow this structure:

```markdown
---
description: "Brief description of what the rule covers"
globs: ["**/*.{extension}"]
alwaysApply: false
---

# Rule Content
```

## Available Rules

### Frontend Development

- [JavaScript Development](.cursor/rules/javascript.mdc) - Comprehensive guidelines for JavaScript development focusing on modern practices, patterns, and maintainability

### Backend Development

- [Node.js with TypeScript](.cursor/rules/nodejs-typescript.mdc) - Best practices for Node.js development using TypeScript, including Webpack configuration
- [WordPress Development](.cursor/rules/wordpress.mdc) - Guidelines for WordPress core development including PHP standards and best practices
- [WooCommerce Development](.cursor/rules/woocommerce.mdc) - Specialized guidelines for WooCommerce extension and theme development

### Tools and Extensions

- [VSCode Extension Development](.cursor/rules/vscode-extension.mdc) - Complete guide for developing VSCode extensions

### Project Management

- [Changelog Management](.cursor/rules/changelog.mdc) - Guidelines for maintaining a consistent and organized changelog using semantic versioning

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/my-cursor-rules.git
   ```

2. Copy the desired `.mdc` files to your project:

   ```bash
   cp .cursor/rules/desired-rule.mdc /path/to/your-project/.cursor/rules/
   ```

3. The rules will automatically apply when working with files that match the specified glob patterns in the frontmatter.

## Rule Format

Each `.mdc` file follows this format:

```markdown
---
description: "Clear description of the rule's purpose"
globs: ["**/*.{relevant-extensions}"]
alwaysApply: false
---

# Main Title

## Section 1

- Guidelines
- Best practices
- Code examples

## Section 2

...
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new `.mdc` file in `.cursor/rules/`
3. Follow the standard format with frontmatter
4. Submit a pull request

### Contribution Guidelines

- Ensure your rule has clear, practical examples
- Include appropriate glob patterns
- Provide comprehensive documentation
- Follow the established `.mdc` format

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Related

- https://docs.cursor.com/context/rules-for-ai
- https://notes.switchdimension.com/cursor-ai-rules
- https://forum.cursor.com/t/what-is-a-mdc-file/50417
