pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "mymaven"
    }

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'pipeline' {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "mymaven"
    }

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/Jayshri261/spring-core-demo.git'

              

                // To run Maven on a Windows agent, use
                 bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }

          
        }
    }

              

                // To run Maven on a Windows agent, use
                 bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }

          
        }
        }
    }
}
