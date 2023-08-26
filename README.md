# LogoCraft - SVG Logo Generator

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Table of Contents

- [Description](#description)
- [Live Demo](#live-demo)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Features](#features)
- [Usage Instructions](#usage-instructions)
- [Contribution Guidelines](#contribution-guidelines)
- [Testing](#testing)
- [License](#license)
- [Questions](#questions)

## Description

LogoCraft is a user-friendly SVG logo generator designed to empower freelance web developers and small business owners. Say goodbye to hefty graphic design fees and create your own simple logos in minutes. This application utilizes the command line and the Inquirer library to prompt users for logo specifications. You can customize the logo by specifying the text content (up to three characters), text color, shape (triangle, square, or circle), and shape color. Once you've provided your choices, LogoCraft generates an SVG logo file.

This project also marks the developer's first venture into unit testing, offering one test suite with three tests. These tests ensure the application consistently delivers the correct shapes and colors.

Future enhancements may include expanded error handling, additional unit testing, and the addition of more polygons and font styles for users to choose from.

## Live Demo

See LogoCraft in action: [Live Demo](https://drive.google.com/file/d/1AMDQU-UmMNdfuerkqlAPvFFeMImd-Exv/view)

## Screenshots

### Examples of Generated Logos

![Logo Example 1](https://user-images.githubusercontent.com/120127903/232142654-9a5a9937-e831-4838-86a1-4323c7b9cc39.png)

![Logo Example 2](https://user-images.githubusercontent.com/120127903/232142705-29cd92d9-1c12-46ce-a81a-64893ac15a00.png)

## Technologies Used

LogoCraft is built using the following technologies:

- Node.js v16
- Inquirer v8.2.4 (Node Package Manager)
- File System Module (Node Package Manager)
- Jest v29.6.3 (Node Package Manager) for unit testing

## Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:2015johngtz/SVG-Logo-Maker.git
   ```

2. Open the project in Visual Studio Code or your preferred code editor.

3. Install Node.js version 16. If you have Homebrew installed, you can use the following command to install Node.js:

   ```bash
   brew install node@16
   ```

   Note that the installation process may vary depending on your system, so consult the official Node.js documentation for guidance if needed.

4. Once Node.js v16 is installed, initialize a `package.json` file in your project directory by running the following command in the terminal:

   ```bash
   npm init -y
   ```

5. Install the project's dependencies using npm:

   ```bash
   npm install
   ```

   If necessary, you can install Inquirer and Jest directly using the following commands:

   ```bash
   npm install inquirer@8.2.4
   npm install jest
   ```

6. To run the application, enter the following command in the terminal:

   ```bash
   node index.js
   ```

## Features

Key features of LogoCraft:

- Generate logos quickly and easily through SVG files, entirely from the command line.
- No need for a user interface or front-end tools.

## Usage Instructions

To create a logo with LogoCraft, follow these steps:

1. Open your terminal and navigate to the LogoCraft project directory.

2. Install project dependencies if you haven't already (use `npm install`).

3. Run the application by entering the following command:

   ```bash
   node index.js
   ```

4. Follow the on-screen prompts to customize your logo. You will be asked for:

   - Text content (up to three characters)
   - Text color (you can use color keywords or hexadecimal numbers)
   - Shape (choose from triangle, square, or circle)
   - Shape color (you can use color keywords or hexadecimal numbers)

5. After answering all the prompts, LogoCraft will generate your logo, and you will receive a message in the terminal confirming the logo's creation. You can find your new logo in the newly generated SVG file.

## Contribution Guidelines

LogoCraft is open to collaboration. If you'd like to contribute, please follow these steps:

1. Open an issue to propose changes or improvements.

2. Create a feature branch for your changes.

3. Make your modifications and ensure your code adheres to project standards.

4. Submit a pull request, and your changes will be reviewed for merging into the main branch.

## Testing

To run unit tests for LogoCraft, use the following command in the terminal:

```bash
npm run test
```

The unit tests consist of one test suite with three tests. The test suite verifies that the `render()` method returns a string for the corresponding SVG file with the specified shape color.

## License

This application is covered under the MIT License. See the [LICENSE](LICENSE) file for details.

## Questions

If you have any questions or would like to contact the developer, you can reach out through the following channels:

- [GitHub](https://github.com/2015johngtz)
- Email: [1998johngtz@gmail.com](mailto:1998johngtz@gmail.com)

Feel free to get in touch with any inquiries or suggestions!