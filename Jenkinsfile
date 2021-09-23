pipeline {
    agent any //must run manually job before/
    // if job is aborted -> can not trigger webhook
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
