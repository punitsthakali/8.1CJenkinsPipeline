// pipeline updated
pipeline {
  agent any
  stages {

    stage("Build") {
      steps {
        echo "Stage: Build"
        echo "Task: Compile and package the source code into a deployable artifact"
        echo "Tool: Maven - a build automation tool for Java projects"
      }
    }

    stage("Unit and Integration Tests") {
      steps {
        echo "Stage: Unit and Integration Tests"
        echo "Task: Run unit tests to verify individual functions work correctly"
        echo "Task: Run integration tests to verify components work together"
        echo "Tool: JUnit for unit tests, TestNG for integration tests"
      }
    }

    stage("Code Analysis") {
      steps {
        echo "Stage: Code Analysis"
        echo "Task: Analyse code quality and check for code smells and standards violations"
        echo "Tool: SonarQube - a static code analysis platform"
      }
    }

    stage("Security Scan") {
      steps {
        echo "Stage: Security Scan"
        echo "Task: Scan dependencies for known CVE security vulnerabilities"
        echo "Tool: OWASP Dependency-Check"
      }
    }

    stage("Deploy to Staging") {
      steps {
        echo "Stage: Deploy to Staging"
        echo "Task: Deploy the application to a staging server for testing"
        echo "Tool: AWS CLI deploying to an EC2 instance"
      }
    }

    stage("Integration Tests on Staging") {
      steps {
        echo "Stage: Integration Tests on Staging"
        echo "Task: Validate the full application in a production-like environment"
        echo "Tool: Selenium WebDriver for end-to-end browser tests"
      }
    }

    stage("Deploy to Production") {
      steps {
        echo "Stage: Deploy to Production"
        echo "Task: Deploy the verified application to the live production server"
        echo "Tool: AWS CLI deploying to an EC2 instance"
      }
    }

  }
}
