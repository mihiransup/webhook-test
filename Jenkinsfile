node {

    try {
        stage ('Clone') {
        	checkout scm
            echo "checkkkkk"
        }
        stage ('Build') {
        	sh "echo 'hello world'"
        }
       }catch (err) {
        currentBuild.result = 'FAILED'
        throw err
    }
}
