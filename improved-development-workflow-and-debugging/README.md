# Improved Development Workflow and Debugging

## NPM

- NPM stand for "Node Package Manager" and it allows you to manage your Node project and its dependencies.
- You can initialize a project with `npm init` and install dependencies with `npm install package-name`.
- NPM scripts can be defined in the `package.json` to give you "shortcuts" for common tasks/commands.

## 3rd Party Packages

- Node projects typically don't just use core modules and custom code but also third-party packages.
- You can install these packages via `npm install package-name`.
- You can differentiate between dependencies (needed for production `--save`), development dependencies (needed for development only `--save-dev`) and global dependencies (installed globally `--global`).

## Types of Errors

- Syntax errors: Errors that occur when you write invalid JavaScript code.
- Runtime errors: Errors that occur when you run the code.
- Logical errors: Errors that occur when the code runs but doesn't do what you intended.

Syntax and runtime errors throw (helpful) error messages (with line numbers) while logical errors can be fixed with testing and the help of the debugger.

## Debugging

- Use the debugger to step into your code and go through it step by step.
- Analyze variable values at runtime.
- Look into (and manipulate) variables at runtime.
- Set breakpoints cleverly (e.g. respect the async/event-driven nature).

## Useful Resources & Links

- [Node.js Debugger](https://nodejs.org/en/docs/guides/debugging-getting-started/)
