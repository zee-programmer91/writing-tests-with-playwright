# Writing Tests With Playwright

This is a project where I learn to write test using Playwright on Python

## Create and activate virtual environment

    ```python -m venv venv
    source venv/bin/activate
    ```

## Install Playwright

    ```bash
    npm init playwright@latest
    ```

When you run this command, you're asked a few questions to configure the Playwright project:

- Select the language you want to use for your tests. We recommend **TypeScript**.
- Select the name of the test directory. We recommend **tests**.
- Add a GitHub Action for automating tests. We recommend **Yes**.
- Install Playwright browsers. We recommend selecting the default of **True**

## Running tests

### Runs the end-to-end tests

    ```bash
    npx playwright test
    ```

## Show test report

    ```bash
    npx playwright show-report
    ```

### Starts the interactive UI mode

    ```bash
    npx playwright test --ui
    ```

### Runs the tests only on Desktop Chrome

    ```bash
    npx playwright test --project=chromium
    ```

### Runs the tests in a specific file

    ```bash
    npx playwright test example
    ```

### Runs the tests in debug mode

    ```bash
    npx playwright test --debug
    ```

### Auto generate tests with Codegen

    ```bash
    npx playwright codegen
    ```
