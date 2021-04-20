node {  
    stage('Build') { 
        // 
    }
    stage('Test') { 
        // 
    }
    stage('Deploy') { 
        // 
    }
    stage('SCM checkout') { 
        // 
        sh "printenv"
        echo ${env.BUILD_NUMBER}
        final scmVars = checkout(scm)
        echo "GIT_COMMIT: ${scmVars.GIT_COMMIT}
    }
}
