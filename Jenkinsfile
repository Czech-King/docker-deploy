pipeline { 
    stages {
        stage('Maven Build') {
            steps {
                // Maven build
                script {
                    def mvnHome = tool 'maven'
                    def mvnCMD = "${mvnHome}/bin/mvn"

                    sh "${mvnCMD} clean install"
                    // Add additional Maven goals or options as needed
                }
            }
        }
    }
}
