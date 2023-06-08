node {
    stage ('clone') {
        checkout scm
    }
    stage ('build image') {
        docker.build("mohamed976/myapp")
    }
    stage ('Push') {
        sh 'docker login -u hocinho699 -p dckr_pat_RKE9TZX584T4KyDMfqmQSssLP6Y'
        sh 'docker push hocinho699/calculete'
    }
}
