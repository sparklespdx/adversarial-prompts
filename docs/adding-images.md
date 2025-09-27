# Adding Images to Examples

This document explains how to properly add images to your adversarial prompt examples.

## Image Storage

All images should be stored in the `/images` directory with descriptive filenames:

```
images/
├── README.md
├── copilot-injection-screenshot.png
├── chatgpt-jailbreak-example.png
└── prompt-injection-demo.gif
```

## Linking Images in Markdown

From the `examples/` directory, reference images using relative paths:

```markdown
![Alt text description](../images/your-image-file.png)
```

## Example Structure

Here's how the Trail of Bits Copilot injection example is structured:

```
examples/trail-of-bits-copilot-injection.md
    └── References: ../images/trail-of-bits-copilot-injection-screenshot.png
```

## Image Guidelines

1. **Format**: Use PNG for screenshots, SVG for diagrams, GIF for animations
2. **Size**: Keep files under 1MB when possible
3. **Names**: Use descriptive, lowercase names with hyphens
4. **Content**: Ensure no sensitive information is visible
5. **Alt Text**: Always include descriptive alt text for accessibility

## Visual Assets You Can Include

- Screenshots of attack results
- Code editor screenshots showing malicious prompts
- Diagrams explaining attack flow
- Before/after comparisons
- Network requests/responses (sanitized)
- Error messages or system outputs

## Example Markdown Pattern

```markdown
## Visual Example

![Description of what the image shows](../images/example-screenshot.png)

*Caption explaining the context and significance of the image*

### Additional Screenshots

For attacks with multiple steps, you can include several images:

![Step 1: Initial prompt](../images/attack-step1.png)
*The initial malicious prompt that bypasses filters*

![Step 2: System response](../images/attack-step2.png)
*The system's compromised response showing the attack succeeded*
```

This approach ensures all visual documentation is properly organized and accessible.