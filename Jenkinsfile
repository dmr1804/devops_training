pipeline{
  agent any
  stages {
    stage('Maven install') {
      steps {
        withMaven(jdk: 'LocalJDK8',maven: 'LocalMaven') {
          sh "mvn clean package"
}
    }
  }
}
}
