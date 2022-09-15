pipeline{
  agent any
  stages {
    stage('Maven install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'LocalMaven', mavenSettingsConfig: 'null') {
          sh 'mvn clean install'
}
    }
  }
}
}
