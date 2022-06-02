pipeline {

agent any

stages {

stage('Build') {

steps {
  bat 'javac HelloWor.java'
  bat 'java -version'

}

}

stage('Run') {

steps {

bat 'java HelloWorld'
}
}
}
}
