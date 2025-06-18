pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                // Checkout the source code from your version control system (e.g., Git)
                checkout scm

                // Execute the compile.bat file
                bat 'compile.bat'
            }
        }
    }
}
