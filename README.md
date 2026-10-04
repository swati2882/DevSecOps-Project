DevSecOps Security Pipeline

Project Overview

This project demonstrates a basic DevSecOps pipeline using Java and GitHub Actions.

The pipeline automatically builds, runs, and performs basic security checks on the Java application whenever changes are pushed to the main branch.

Objectives

- Understand the basic DevSecOps workflow
- Automate Java compilation and execution
- Perform basic security scanning
- Use GitHub Actions for CI/CD automation
- Integrate security testing into the development process

Technologies Used

- Java 17
- Git
- GitHub
- GitHub Actions
- YAML

DevSecOps Pipeline

Code Push
↓
GitHub Actions
↓
Java Setup
↓
Compile Java
↓
Run Application
↓
Security Scan
↓
Security Testing
↓
Pipeline Success

Security Scan

The pipeline performs a basic scan for commonly used sensitive keywords such as:

- password
- secret
- api_key

This helps demonstrate the concept of identifying potentially sensitive information during the development pipeline.

Application Output

The Java application displays:

- DevSecOps Project Started
- Security Testing Pipeline Ready

Result

The GitHub Actions workflow successfully executes the Java application and security checks.

Pipeline Status: Successful ✅

Conclusion

This project demonstrates how security checks can be integrated into a software development pipeline using DevSecOps practices and GitHub Actions.
