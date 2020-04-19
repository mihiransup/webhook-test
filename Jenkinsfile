node {

    try {
        stage ('Clone') {
        	checkout scm
        }
        stage ('Build') {
        	sh "echo 'shell scripts to build project...'"
        }
       }catch (err) {
        currentBuild.result = 'FAILED'
        throw err
    }
}
