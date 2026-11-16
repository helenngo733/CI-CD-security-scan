# CI/CD with Security Scanning

A GitHub Actions workflow that runs unit tests and scans for security issues on every push and pull request.

## About the Workflow
The security-ci.yml file defines a GitHub Actions workflow that:
1. Sets up a Python environment
2. Installs the dependencies, plus `safety` and `bandit`
3. Runs the unit tests with `pytest`
4. Performs security scans and reports findings