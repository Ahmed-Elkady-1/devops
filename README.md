# devops

## CI/CD Pipeline

This repository includes a GitHub Actions pipeline that automatically runs when:
- Code is pushed to the main branch
- A pull request targeting the main branch is created

The pipeline performs the following actions:
1. Checks out the code
2. Runs the specified script

To modify the script that runs, edit the `.github/workflows/main.yml` file.