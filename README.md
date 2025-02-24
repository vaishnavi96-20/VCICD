# VCICD
How to setup a CI/CD Integration
# CI/CD Integration with GitHub Actions

This is a sample Java project demonstrating CI/CD integration using GitHub Actions. The project uses:
- Selenium WebDriver for browser automation.
- TestNG for testing framework.
- Maven as the build tool.
- GitHub Actions for CI/CD pipeline.

## How It Works:
- The workflow triggers when changes are pushed to the `main` branch.
- The tests are automatically built and executed.
- Results are displayed in GitHub Actions logs.

## Prerequisites:
- Ensure you have Maven and Java 11 installed locally.
- Set up `chromedriver` in your environment.

## Running Locally:
1. Clone the repository.
2. Run `mvn clean install`.
3. Execute tests with `mvn test`.
