pipeline {
    agent any
    steps {
        stage("build") {
            steps {
                sh 'ant -f build.xml -v'
            }
        }
    }
}