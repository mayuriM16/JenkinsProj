pipeline {

agent any

stages {

stage('Build') {

steps {

//echo "HelloWorld"
bat 'javac HelloWorld'
  bat 'java -version'
}

}

stage('Run') {

steps {

//echo "HelloWorld"
  bat 'java HelloWorld'
}
}
}
}
