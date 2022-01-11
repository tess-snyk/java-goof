pipeline {
  agent any
  stages {
    stage('Snyk Scan') {
      steps {
        snykSecurity(failOnIssues: true, organisation: 'tess.davis', projectName: 'java-goof-jenkins', severity: 'High', snykTokenId: 'snyk_token')
      }
    }

  }
}