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
        GIT_COMMIT_MSG=sh (script: 'git log -1 --pretty=%B ${GIT_COMMIT_MSG}', returnStdout: true).trim()
        echo "GIT_COMMIT_MSG: ${scmVars.GIT_COMMIT_MSG}"
    }
}
