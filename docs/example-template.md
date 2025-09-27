# Example Template

Use this template when adding new adversarial prompt examples to the collection.

## File Structure

Save your example as `examples/your-example-name.md` with a descriptive filename.

## Template

```markdown
# [Example Name]

**Category**: [Prompt Injection | Jailbreaking | Data Extraction | Code Injection | Social Engineering | Information Disclosure]  
**Target**: [Specific LLM or system, e.g., ChatGPT, Claude, GitHub Copilot]  
**Discovered**: [Research team, individual, or organization]  
**Severity**: [Low | Medium | High | Critical]  
**Date**: [YYYY-MM-DD]

## Overview

Brief description of what this example demonstrates (1-2 sentences).

## Description

Detailed explanation of the attack technique, how it works, and why it's effective.

## Attack Vector

Step-by-step breakdown of how the attack is executed:

1. **Step 1**: Description
2. **Step 2**: Description
3. **Step 3**: Description

## Example Payload

```
[Include the actual prompt, code, or text used in the attack]
```

## Technical Details

- How the attack exploits specific LLM behaviors
- Why the technique is effective
- What makes it difficult to detect or prevent

## Impact

- Potential consequences of successful exploitation
- Risk to users, systems, or data
- Broader implications for LLM security

## Mitigation Strategies

### For Users
- Specific actions users can take to protect themselves
- Warning signs to watch for

### For Developers
- Technical measures to prevent or detect this attack
- Best practices for secure LLM integration

### For Organizations
- Policy and process recommendations
- Security controls and monitoring

## Detection Methods

How to identify if this attack has been attempted or successful:
- Log patterns to monitor
- Behavioral indicators
- Technical signatures

## References

- [Link to original research](https://example.com)
- [Related security advisories](https://example.com)
- [Additional reading](https://example.com)

## Visual Example

![Description of image](../images/your-example-screenshot.png)

*Caption describing what the image shows*

## Timeline

- **Discovery**: When and how the technique was discovered
- **Disclosure**: Responsible disclosure timeline
- **Mitigation**: When fixes or improvements were implemented
- **Public Release**: When information was made public

## Related Examples

- Links to similar techniques in this repository
- Related attack vectors or variations

---

*This example is for educational purposes only. Do not use these techniques maliciously.*
```

## Guidelines

### Writing Quality
- Use clear, concise language
- Provide sufficient technical detail without being overly verbose
- Include practical examples and code when relevant
- Explain concepts in a way that's accessible to security professionals

### Images and Screenshots
- Store images in the `/images` directory
- Use descriptive filenames: `technique-name-screenshot.png`
- Include alt text for accessibility
- Ensure no sensitive information is visible
- Keep file sizes reasonable (< 1MB when possible)

### Ethical Considerations
- Always include the disclaimer about educational use only
- Provide comprehensive mitigation strategies
- Follow responsible disclosure principles
- Don't include techniques that are primarily harmful with no educational value

### Technical Accuracy
- Test examples before submitting
- Verify that mitigation strategies are effective
- Include accurate technical details
- Cite sources for claims and research findings

## Review Process

1. Fork the repository
2. Create your example using this template
3. Add any necessary images to the `/images` directory
4. Update the main README.md to include your example
5. Submit a pull request with a clear description

Your contribution will be reviewed for:
- Technical accuracy
- Educational value
- Ethical compliance
- Documentation quality
- Proper formatting