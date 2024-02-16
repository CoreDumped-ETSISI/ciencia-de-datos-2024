# Contributing to `<Project Name>`

We welcome contributions to `<Project Name>`! If you're looking to contribute, there are a few things you should know.

## Pull Requests

Here's the process for submitting a pull request:

1. Fork the repository.
2. Clone your fork to your local machine.
3. Create a branch for your changes.
4. Make your changes.
5. Push your changes to your fork.
6. Submit a pull request against the master branch.

When submitting a pull request, please make sure to:

1. Clearly describe the problem you're solving.
2. Reference any relevant issues or documentation.
3. Explain your solution and why it's the best approach.
4. Ensure that your code is properly formatted and follows the [style guide](./STYLE_GUIDE.md).
5. Include tests that validate your changes.
6. Code of Conduct

## Style Guide

Please follow the style guide when submitting code.

## Git Commit Guidelines

Writing clear and descriptive Git commit messages is an important part of the software development process. It helps to provide context and make the code easier to understand and maintain. Here are some guidelines for writing Git commit messages:

### Message Structure

A Git commit message should have a clear structure with the following components:

```txt
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

- `type`: A keyword that describes the type of the change, e.g. `feat` (feature), `fix` (bug fix), `docs` (documentation), `style` (formatting), `refactor`, `test`, etc.
- `scope` (optional): A short description of the affected part of the code, e.g. `module name`, `file name`, etc.
- `subject`: A brief summary of the change, written in the present tense and no more than 50 characters.
- `body` (optional): A detailed description of the change, written in the present tense. If the change fixes a bug, the body should describe the problem and how the change solves it.
- `footer` (optional): Additional information, such as reference to related issues, pull requests, etc.

Here is an example of a well-structured Git commit message:

```txt
fix(module): resolve ReferenceError on line 42

The code on line 42 was using an undefined variable, causing a ReferenceError.
This change adds the missing variable declaration and resolves the error.

Fixes #123
```

### Message Content

- Write clear, concise, and descriptive messages.
- Use the present tense ("Add feature" not "Added feature").
- Limit the subject line to 72 characters or less.
- Capitalize the subject line and leave a blank line between the subject and body.
- Wrap the body at 72 characters.
- Use the body to explain what and why, not how.
- Reference any related issues or pull requests in the footer.

By following these guidelines, you can ensure that your Git commit messages are consistent, informative, and helpful for other contributors and future maintainers of the project.
