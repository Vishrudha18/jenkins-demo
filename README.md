# Jenkins Controller-Agent Setup with GitHub Integration

## Project Overview

This project demonstrates the setup of a distributed Jenkins architecture on AWS EC2 using a Jenkins Controller and a Jenkins Agent connected through SSH.

The project also integrates GitHub with Jenkins to automatically retrieve source code and execute build jobs on the remote agent node.

## Architecture

GitHub Repository
        │
        ▼
Jenkins Controller (AWS EC2)
        │ SSH
        ▼
Jenkins Agent (AWS EC2)
        │
        ▼
Build Execution

## Technologies Used

- AWS EC2
- Ubuntu Linux
- Jenkins
- Java 21
- Git
- GitHub
- SSH

## Features

- Jenkins installation on AWS EC2
- Java 21 configuration
- SSH-based Jenkins agent setup
- Distributed build execution
- GitHub repository integration
- Source code cloning from GitHub
- Remote build execution on Jenkins Agent

## Repository Contents

- README.md
- index.html
- style.css

## Build Verification

The Jenkins job successfully:

1. Connects to GitHub
2. Clones the repository
3. Retrieves project files
4. Executes build steps on the Jenkins Agent
5. Generates successful build logs

## Learning Outcomes

- Jenkins Controller-Agent Architecture
- GitHub Integration with Jenkins
- Distributed Builds
- AWS EC2 Administration
- SSH-based Authentication
- Continuous Integration Fundamentals
