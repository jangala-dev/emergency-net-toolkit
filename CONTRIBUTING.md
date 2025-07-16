# Contributing to Emergency Net Toolkit

Thank you for your interest in contributing. This project is built on the belief that open, practical tools can support critical connectivity under the most constrained conditions. Whether you’re adding documentation, improving a guide, translating materials, or helping shape the network architecture – your contribution is welcome.


## What You Can Contribute

You might contribute by:

- Improving or correcting technical documentation
- Translating materials into other languages
- Adding new deployment guides for specific contexts (eg. refugee camps, rural schools)
- Contributing images or diagrams
- Reporting bugs or suggesting enhancements
- Sharing feedback from field use


## Getting Started

1. **Fork the repository**: [GitHub guide on forking](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
2. **Create a branch**: Use a clear branch name (eg. `add-arabic-guides` or `fix-antenna-diagram`)
3. **Make your changes**: Follow the formatting and structure guidance below
4. **Submit a pull request**: Include a brief summary of your changes


## Documentation Guidelines

All textual documentation should be written in [Markdown](https://www.markdownguide.org/basic-syntax/). Markdown is a plain text format that’s easy to learn and widely used for project documentation.

- Use `#` for headings, `-` or `*` for lists
- Link internally using `[text](relative/path.md)`
- Keep formatting consistent with existing documents
- Break content into manageable sections for clarity


## Diagrams and Visuals

We support diagrams in both visual and code-based formats:

### 1. **Mermaid Diagrams (recommended for network architecture)**

Mermaid allows you to describe diagrams using plain text syntax.

- Learn more at [https://mermaid.js.org](https://mermaid.js.org)
- Diagrams should be included in fenced code blocks:

  <pre>
  ```mermaid
  graph TD
    Laptop --> Switch
    Switch --> AP
    Switch --> Internet
  ```
  </pre>

will render as

  ```mermaid
  graph TD
    Laptop --> Switch
    Switch --> AP
    Switch --> Internet
  ```


* Keep diagrams simple, labelled, and readable
* Include a plain text explanation underneath if the diagram is complex

### 2. **Images**

You may include:

* `.jpg` or `.png` for photographs or screenshots
* `.svg` for scalable vector diagrams or illustrations

Images should be placed in a clearly named `images/` subfolder and referenced relatively:

```markdown
![Example Setup](../images/site-layout.png)
```

Please keep image file sizes modest where possible.


## Language and Accessibility

* Write in plain, clear English (or provide parallel content in Arabic, Spanish, etc.)
* Avoid acronyms or explain them on first use
* Use headers and lists to aid navigation
* Provide alt text for images


## Field-Use Considerations

Where possible, prioritise content that works well in:

* Offline or low-bandwidth environments
* Print-friendly formats
* Environments with limited or no technical support


## Reporting Issues or Making Suggestions

If you spot an error, have a question, or would like to propose a change, please open an issue using GitHub’s [issue tracker](https://github.com/jangala-dev/emergency-net-toolkit/issues). Be as clear and descriptive as possible.


## Attribution and Licensing

By contributing, you agree that your contributions will be released under the same open licence as the project (GPL). Please ensure that any materials you submit do not infringe on copyright and are your original work, or are openly licensed with appropriate attribution.


## Questions?

If in doubt, you can always contact the project maintainers via [contact@janga.la](mailto:contact@janga.la) or raise a question in the issue tracker.

We are grateful for your time and support.


*Last updated: \[1 July 2025]*
