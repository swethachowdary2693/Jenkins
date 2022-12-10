pipeline {
    agent any
    stages {
        stage("parallel") {
            parallel {
                stage("one") {
                    steps {
                        echo "sleep 15"
                    }
                }

                stage("two") {
                    steps {
                        echo "sleep 15"
                    }
                }
            }
        }
    }
}