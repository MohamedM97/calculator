node{
    stage ('clone') {
        checkout scm
    }
    stage ('build image') {
        docker.build("mohamed976/myapp")
    }
}
