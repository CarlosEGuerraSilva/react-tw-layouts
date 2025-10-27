# AGENTS.md

## Code Style & Best Practices

### Language and Documentation

- All documentation and comments must be in English, regardless of the conversation language
- Avoid inline comments using `//` at the end of lines
- Do not include emojis in code or comments
- Minimize unnecessary inline documentation within function bodies
- Use JSDoc comments for function signatures, parameters, and return types, especially for public APIs or complex logic
- Reserve inline comments only for non-obvious or intricate implementation details

Example:

```typescript
/**
 * Check if the current environment is a browser.
 * @returns {boolean} True if running in a browser, false if on the server.
 */
export const isBrowser = (): boolean => typeof window !== 'undefined';
```

### Code Changes and File Management

- When generating new files or modifying existing files, always include the file path in the conversation
- Do not include file paths as comments within the generated code
- Reference the file path clearly when presenting code changes to maintain clarity and context

### Dependency Management

- Avoid modifying packages (installing or uninstalling) unless absolutely necessary
- Only modify dependencies if explicitly requested by the user
- Prioritize working with existing dependencies
- Document any dependency changes when they are required

### General Guidelines

- Write clean, readable code that prioritizes clarity
- Follow DRY (Don't Repeat Yourself) principles
- Use meaningful variable and function names
- Keep functions focused and modular
- Leverage TypeScript for type safety when applicable
- Ensure code is well-tested and maintainable
