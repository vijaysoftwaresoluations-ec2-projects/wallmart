pipeline {
  agent any
  stages {
    stage('Build JOB') {
      steps {
        echo 'Agent Any'
      }
    }

    stage('ExecuteSonarqubeReport') {
      parallel {
        stage('ExecuteSonarqubeReport') {
          steps {
            echo 'Agent any'
          }
        }

        stage('testtool') {
          steps {
            echo 'agent any'
          }
        }

      }
    }

    stage('UploadArtifactintoNexus') {
      steps {
        echo 'Agent any'
      }
    }

  }
}