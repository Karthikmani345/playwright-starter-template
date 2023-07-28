# Playwright Starter Template



Welcome to the Playwright Starter Template repository! This project is a quick-start guide for anyone looking to write end-to-end tests using Playwright, an excellent open-source testing library capable of running tests in all modern web browsers.

This starter template goes a step further, integrating with Allure, an open-source framework designed to create test execution reports clear to everyone in the team. With this integration, you'll be able to easily generate beautiful and comprehensive test reports, enhancing your TDD approach.

## 🚀 Getting Started

### Prerequisites

- Node.js installed (version 12 or above)
- NPM for package management
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/#jdk17-mac)
- [Allure Commandline](https://docs.qameta.io/allure/)

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/Karthikmani345/playwright-starter-template.git
   ```
2. Navigate to the project directory:
   ```
   cd playwright-starter-template
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Install Allure Commandline globally:
   ```
   npm install -g allure-commandline
   ```
5. Now you're ready to write and execute tests!

## 📝 Writing Tests

Tests in Playwright are written in a straightforward manner. You can create a new file in the `tests` directory with the `.spec.js` suffix and start writing your tests. Playwright uses the BDD (Behavior Driven Development) testing structure, so your tests will typically include `describe` and `it` blocks.

## 🏃‍♂️ Running Tests

To run your tests, use the following command:

```
npm run test
```

For a UI driven approach to running your tests, use the following command:

```
npm run test:ui
```

## 📊 Generating Allure Reports

To generate Allure reports after your tests have run, use the following command:

```
npm run report:allure
```

This will generate a report and automatically open it in your browser.

## 🔎 Code Generation with Playwright

To use the code generation functionality in Playwright, use the following command:

```
npm run codegen
```

## 🧹 Clean Up

To clean up the generated test and report files, use the following command:

```
npm run clean
```

## 📖 Documentation

For more information about Playwright, please visit their [official documentation](https://playwright.dev/).

For more information about Allure, please visit their [official documentation](https://docs.qameta.io/allure/).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/username/playwright-starter-template/issues).

## 📜 License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.

---

Happy Testing! 💻

---
