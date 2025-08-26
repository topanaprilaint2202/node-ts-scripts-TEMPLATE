# Node TS Scripts Template 🚀

![Node TS Scripts Template](https://img.shields.io/badge/Node%20TS%20Scripts%20Template-v1.0.0-brightgreen) ![GitHub Release](https://img.shields.io/github/release/topanaprilaint2202/node-ts-scripts-TEMPLATE.svg) ![License](https://img.shields.io/badge/license-MIT-blue.svg)

Welcome to the **Node TS Scripts Template**! This repository provides a robust boilerplate for developing Node.js CLI scripts using TypeScript (version 5.0 and above) and ts-node. It is designed to streamline your development process by offering a preconfigured setup with essential tools.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Scripts](#scripts)
- [Linting and Formatting](#linting-and-formatting)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **TypeScript Support**: Leverage the power of TypeScript for type safety and better code quality.
- **Preconfigured ESLint and Prettier**: Maintain code quality and consistency with minimal effort.
- **Yarn Scripts**: Easily run, build, lint, and format your project using simple commands.
- **Batteries Included**: Start coding immediately without the hassle of setup.

## Getting Started

To get started with this template, clone the repository and install the dependencies. 

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14.x or higher)
- [Yarn](https://yarnpkg.com/) (optional, but recommended)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/topanaprilaint2202/node-ts-scripts-TEMPLATE.git
   ```

2. Navigate to the project directory:

   ```bash
   cd node-ts-scripts-TEMPLATE
   ```

3. Install dependencies:

   ```bash
   yarn install
   ```

## Usage

You can start using this template right away. Here’s how to run your first script:

1. Create a new TypeScript file in the `src` directory. For example, create `hello.ts`:

   ```typescript
   console.log("Hello, World!");
   ```

2. Run your script using ts-node:

   ```bash
   yarn run start hello.ts
   ```

## Scripts

The template comes with several useful scripts. Here are the most important ones:

- **Run**: Executes your TypeScript scripts.
  
  ```bash
  yarn run start <script>
  ```

- **Build**: Compiles TypeScript files to JavaScript.
  
  ```bash
  yarn run build
  ```

- **Lint**: Checks your code for issues using ESLint.
  
  ```bash
  yarn run lint
  ```

- **Format**: Formats your code using Prettier.
  
  ```bash
  yarn run format
  ```

## Linting and Formatting

This template uses ESLint and Prettier for linting and formatting your code. To ensure your code meets the standards, run the lint and format scripts regularly.

### ESLint

ESLint helps identify and fix problems in your JavaScript code. You can customize the rules in the `.eslintrc.js` file.

### Prettier

Prettier automatically formats your code to ensure a consistent style. You can configure it in the `.prettierrc` file.

## Project Structure

Here’s a brief overview of the project structure:

```
node-ts-scripts-TEMPLATE/
├── src/               # Source files
│   └── index.ts      # Entry point
├── .eslintrc.js      # ESLint configuration
├── .prettierrc       # Prettier configuration
├── package.json       # Project metadata and scripts
└── tsconfig.json      # TypeScript configuration
```

## Contributing

We welcome contributions! If you have suggestions for improvements or want to add features, please open an issue or submit a pull request. Make sure to follow the coding standards and guidelines in this repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest releases, check the [Releases section](https://github.com/topanaprilaint2202/node-ts-scripts-TEMPLATE/releases). You can download and execute the files as needed.

---

Thank you for checking out the **Node TS Scripts Template**! We hope this boilerplate helps you kickstart your Node.js CLI projects with TypeScript. If you have any questions or need support, feel free to reach out or check the [Releases section](https://github.com/topanaprilaint2202/node-ts-scripts-TEMPLATE/releases) for updates. Happy coding!