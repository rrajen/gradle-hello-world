node {

    stage('Pre_Processing') {
        echo "Pre-Processing step"
    }

    stage('Building') {
        sh 'pwd'
        sh 'ls -l'
        sh 'gradle -q helloWorld'           
    }

    stage('Post_Processing') {
        echo "Post-Processing step"           
    }

}