pipeline{
agent any
tools{
        maven 'apache-maven-3.6.3'
        jdk 'jdk-11'
}
stages{
      stage('Compilation du projet')
      {
        steps{
           bat 'mvn compile'
              }
      }
}

}
