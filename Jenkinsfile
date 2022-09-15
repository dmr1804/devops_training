pipeline{
  agent any
  stages {
    stage('Maven install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'LocalJDK8', maven: 'LocalMaven', mavenSettingsConfig: 'null') {
          sh 'mvn clean install'
}
    }
  }
}
}
