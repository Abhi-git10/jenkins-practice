pipeline{
stages{
stage('build'){
steps {
sh 'echo "this is build stage"'
}
}
stage('test'){
steps {
sh '''
echo "this is test stage"
echo "this is used test the stages"
'''
}
}
stage('deploy'){
steps {
sh 'echo "this is deploy stage"'
}
}
}
}
