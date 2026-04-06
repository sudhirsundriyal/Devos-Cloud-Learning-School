## DevOps-Maven-Project- My App

### Project Overview
This is a simple Java application built using Maven and automated with Jenkins. 
It demonstrates basic CI/CD concepts for Java projects.

### Features
- Java application packaged as a JAR.
- Maven for dependency management and build automation.
- Jenkins for automated build pipeline.

### Build Steps (via Jenkins)
1. Checkout code from GitHub.
2. Run Maven build:
   ```bash
   mvn clean install
