node {

    try {
        stage ('Clone') {
        	checkout scm
        }
        stage ('Build') {
        	sh "echo 'hello'"
        }
       }catch (err) {
        currentBuild.result = 'FAILED'
        throw err
    }
}
