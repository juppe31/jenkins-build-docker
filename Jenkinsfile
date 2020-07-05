node {
 stage('clone') {
    git 'https://github.com/juppe31/jenkins.git'
  
}  
  stage('build and run') {
   sh label: '', script: '''javac Main.java
java Main'''
}  
}
