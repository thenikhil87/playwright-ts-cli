# Changelog

## [0.5.1] - 2024-01-17

### Updated Dependencies

- Updated all the dependencies to their latest versions.

## [0.5.0] - 2023-08-26

### Features

- **Windows Support**: Introduced the ability to successfully initialize the repository on Windows systems using the `npm vasu-playwright-ci init` command.

## [0.4.2] - 2023-08-23

### Improvements

- **Husky Setup**: Removed the Husky setup process when initializing the framework as a subdirectory, simplifying the initialization process.

## [0.4.1] - 2023-08-23

### Improvements

- **Husky Installation**: Enhanced Husky installation to be conditional, installing only if the framework is not a subproject of an existing Git repository. This change improves compatibility and avoids conflicts in various project structures.

## [0.4.0] - 2023-08-23

### Features

- **Project Initialization**: Created a new Playwright framework project using the [vasu-playwright-template](https://github.com/vasu31dev/playwright-ts-template).
- **Package.json**: Improved logic for modifying `package.json` as needed.
- **Documentation**: Added comprehensive Readme documentation, including sections for running tests and viewing reports.

## [0.3.2] - 2023-08-23

### Documentation

- **Readme**: Enhanced the Readme with prerequisites, refined installation steps, and comprehensive explanations.

## [0.3.1] - 2023-08-22

### Bug Fixes

- **Post-Install Script**: Removed the post-install script to avoid potential issues during installation.

## [0.3.0] - 2023-08-22

### Features

- **Code Formatting**: Introduced `.prettierrc` and applied formatting to TypeScript files.
- **Logging**: Enhanced console logging for better readability.
- **Git Initialization**: Added logic to initialize as a Git repository only under specific conditions.
  
### Bug Fixes

- **Git Warning**: Resolved a Git warning related to the initial branch name.

## [0.2.2] - 2023-08-22

### Improvements

- **Template Cloning**: Aligned the cloning structure of `vasu-playwright-template` with `vasu-playwright-lib@0.4.4`.

## [0.2.1] - 2023-08-21

### Bug Fixes

- **Module Error**: Fixed a "Cannot find Module" error that occurred during project initialization.

## [0.2.0] - 2023-08-21

### Features

- **Build System**: Switched from `esbuild` to `tsc` for building the project.
- **Repository Cloning**: Moved from SSH to HTTPS for cloning the repository.
- **Cleanup**: Implemented logic to remove the `temp-repo` directory if present.
- **Git Branch**: Set the default Git branch name to "main."

### Documentation

- **ReadMe**: Updated the ReadMe document with the latest changes.

## [0.1.0] - 2023-08-20

### Features

- **Initial Release**: The first stable release of the project.
