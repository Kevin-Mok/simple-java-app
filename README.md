# Simple Java App

A minimal Java application template with Maven build configuration, JUnit testing, and CI/CD pipeline setup.

![Java](https://img.shields.io/badge/Java-17+-orange)
![Maven](https://img.shields.io/badge/Maven-3.9-blue)
![JUnit](https://img.shields.io/badge/JUnit-5-green)

## Overview

A starter template for Java applications demonstrating modern Java development practices. Includes Maven for dependency management, JUnit 5 for testing, and Jenkins pipeline configuration for CI/CD.

## Features

- **Maven Build** - Standard project structure and dependency management
- **JUnit 5 Testing** - Modern test framework with Jupiter API
- **CI/CD Ready** - Jenkinsfile for automated builds
- **GitHub Actions** - Workflow configuration included

## Tech Stack

| Component | Technology |
|-----------|------------|
| **Language** | Java 17+ |
| **Build** | Maven 3.9.2+ |
| **Testing** | JUnit 5 (Jupiter 5.10.3) |
| **CI/CD** | Jenkins, GitHub Actions |

## Project Structure

```
simple-java-app/
├── src/
│   ├── main/java/com/mycompany/app/
│   │   └── App.java              # Main application
│   └── test/java/com/mycompany/app/
│       └── AppTest.java          # Test suite
├── pom.xml                       # Maven configuration
├── Jenkinsfile                   # CI/CD pipeline
└── .github/                      # GitHub workflows
```

## Installation

### Prerequisites
- Java 17+
- Maven 3.9+

### Build and Run

```bash
# Clone repository
git clone git@github.com:Kevin-Mok/simple-java-app.git
cd simple-java-app

# Build
mvn clean package

# Run tests
mvn test

# Execute
java -jar target/simple-java-app-1.0-SNAPSHOT.jar
```

## Why This Project is Interesting

### Technical Highlights

1. **Modern Java Setup**
   - Java 17+ features
   - Maven best practices
   - Standard directory layout

2. **Testing Infrastructure**
   - JUnit 5 Jupiter API
   - Test-driven development ready
   - Code coverage support

3. **CI/CD Integration**
   - Jenkins pipeline as code
   - GitHub Actions workflows
   - Automated build and test

### Skills Demonstrated

- **Java Development**: Modern Java, OOP
- **Build Tools**: Maven, dependency management
- **Testing**: JUnit 5, test organization
- **DevOps**: Jenkins, GitHub Actions, CI/CD

## Author

[Kevin Mok](https://github.com/Kevin-Mok)
