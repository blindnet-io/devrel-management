# Blindnet DevRel Management

> Open Management of everything related to Developer Relations at blindnet.

This project is here to help blindnet staff member track and document all DevRel related matters openly in accordance with our [Openness Framework](https://github.com/openness-framework).

All contributions are welcomed.
Just [open a "request" issue](https://github.com/blindnet-io/devrel-management/issues/new/choose) to get the discussion started, and we'll do the rest.

## Workflow

### 1. Issues

Every goal or task is detailed in an issue using one of the following types:

- **[Epic](https://github.com/blindnet-io/devrel-management/labels/epic)**: Placeholder for large requirements that should be broken down into specific issues
- **Simple Task**: simple goal that doesn't need an extensive definition (only to answer W questions)
- **SMART Goal**: important goal requiring an extensive and thorough definition

**Anyone can create an issue using [the associated templates](https://github.com/blindnet-io/devrel-management/issues/new/choose).\
When in doubt, just use the _Request_ template. We'll make sure to answer it in time and will refine the description ourselves.**

### 2. Documentation and Pull Requests

Most task-related documentation happens in issues descriptions and comments.

Yet, some information may need to be more carefully stored and detailed.\
In this case, we create a Pull Request to add a new markdown file in the `docs/` directory or update an existing one.

If you're familiar with git and Node.js, clone the repository and refer to the [Contributing](#contributing) section.

If not, it's OK too. Just do everything in Github, and we'll make sure to update the document afterward:

1. [Create a new branch directly from the related issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-a-branch-for-an-issue) and ignore the "git checkout" message
1. Click on the name of the new branch
1. Click on the `docs` directory
1. [Add a new file](https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files) or [edit an existing one](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files)
1. Write some content using the a [basic markdown syntax](https://www.markdownguide.org/cheat-sheet/)
   - you can (but don't have to) check out [the associated Github documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) if you want to go further
1. Save and share your work by clicking on the big green button at the bottom

## Contributing

### Requirements

This project requires Node.js 16.

Using NVM for automatic Node.js version management is recommended.

Run `nvm install` from the root directory of this project to install the required version,
then `nvm use` to activate it.

### Formatting

This project uses [Prettier](https://prettier.io/) and [Markdownlint-cli](https://github.com/igorshubovych/markdownlint-cli) for formatting.

Both are automatically run on staged files before any commit using [lint-staged](https://github.com/okonet/lint-staged) and [Husky](https://typicode.github.io/husky).

Run `npm run lint` to check the format of all files manually, and `npm run format` to automatically fix errors.
