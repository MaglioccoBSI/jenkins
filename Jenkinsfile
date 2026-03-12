pipeline{
//agent {label 'worker'}
agent any
stages{
stage("make directory"){
steps{
sh "mkdir ~/jenkins-tutorial-test"
}
}
stage("make a file"){
steps{
sh "touch ~/jenkins-tutorial-test/file1.txt"
}
}
}
}
