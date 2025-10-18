# Copilot Agent Onboarding Instructions

## High-Level Details
- **What this repo does**  
  A collection of community-maintained GitHub Actions for AWS CDK, CDKTF, Next.js, Node.js setup, PR linting/labeling, and release automation.
- **Size & languages**  
  ~100 files, primarily Markdown, YAML (workflows), and TypeScript/JavaScript (action code).  
- **Frameworks & runtimes**  
  Node.js 14+ for action code, GitHub Actions, AWS CDK/CDKTF, Next.js.

## CI & Pre-Commit Checks
- GitHub workflows under `.github/workflows` automatically run on pushes to `main` and on PRs.
- A build pipeline (`Build` workflow) must pass before merges.

## Trust This Guide
Always follow these instructions first. Only search the repo if something here appears incomplete or does not work as described.

