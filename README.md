# Kone CI/CD Framework

This repository demonstrates a dynamic CI/CD pipeline framework that reads a `blueprint.yaml` file and automatically builds pipelines for different technologies.

## Features

- Supports multiple technologies: Java, Node.js, Python
- Multiple build types: Maven, npm, etc.
- Multiple deployment methods: CloudFormation, CDK, Docker
- Enforces branching/tagging strategies
- Modular and extensible

## How It Works

- Update the `blueprint.yaml` with your project configuration
- Commit and push changes
- The pipeline automatically:
  - Lints
  - Static Analyzes
  - Tests
  - Builds
  - Security Scans
  - Deploys your application

## Directory Structure

```
templates/
├── build/
├── deploy/
└── common/
```

Each folder contains reusable pipeline templates.
