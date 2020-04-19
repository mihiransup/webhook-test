node {

    try {
        stage ('Clone') {
        	checkout scm
        }
        stage ('Build') {
        	sh "echo 'hello world'"
        }
       }catch (err) {
        currentBuild.result = 'FAILED'
        throw err
    }
}
