# Style Guide Example

This style guide outlines the preferred coding standards for AgentesInteligentes. By following these standards, we can maintain consistency and make the code easier to read, understand, and maintain.

## General Guidelines

- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) for Python code.
- Use [EditorConfig](https://editorconfig.org/) to maintain consistent coding styles between different editors and IDEs.
- Write clear, concise, and descriptive code and comments.
- Use meaningful variable and function names.
- Avoid using abbreviations unless they are well-known and widely used.
- Keep lines under 80 characters in length.

## Git Commit Messages

- Use the present tense ("Add feature" not "Added feature").
- Limit the first line to 72 characters or less.
- Reference any related issues or pull requests in the body of the commit message.

## Documenting Code

- Use docstrings to document the purpose and arguments of functions and classes.
- Use inline comments to explain complex or non-obvious code.

## Code Formatting

- Use 4 spaces for indentation (not tabs).
- Put spaces around operators and after commas.
- Put a space after the `#` in a comment.
- Avoid trailing whitespaces.

```python
# Correct
x = 1 + 2
y = [1, 2, 3]

def func(arg1, arg2):
    """This is a docstring."""
    return arg1 + arg2

# Incorrect
x=1+2
y=[1,2,3]

def func(arg1,arg2):
  """This is a docstring."""
  return arg1+arg2
```

These are just guidelines, not strict rules. If you have a good reason to deviate from them, feel free to do so. The most important thing is to write readable, maintainable code.