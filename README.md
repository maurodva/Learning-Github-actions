# Learning-GitHub-Actions
Welcome to the "Learning-GitHub-Actions" project! This repository is designed for beginners to understand and practice GitHub Actions, utilizing a sample workflow inspired by the OWASP PyGoat intentionally vulnerable web project.

## Workflow Overview

The GitHub Actions workflow defined in `.github/workflows/main.yml` consists of two jobs:

1. **sast_scan:** This job checks the codebase for security issues using Bandit, a Python static analysis tool. The findings are stored as an artifact.

2. **image_scan:** This job builds a Docker image using the provided Dockerfile and performs security scans using Docker Scout. The scan results are saved as an artifact.

## Getting Started

1. Clone the Repository:
   ```bash
    git clone https://github.com/your-username/Learning-GitHub-Actions.git
    cd Learning-GitHub-Actions
   ```

2. Run GitHub Actions Workflow:
   - Manually trigger the workflow by navigating to the "Actions" tab on GitHub and selecting "Run workflow" for the desired workflow.

3. Explore Results:
   - View Bandit scan results in the bandit-findings artifact.
   - Check Docker Scout scan findings in the docker-scout-findings artifact.


