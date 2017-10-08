node {

    stage('Pre_Processing') {
        steps {
            echo "Pre-Processing step"
        }            
    }

    stage('Building') {
        steps {
            sh 'gradle -q helloWorld'
        }            
    }

    stage('Post_Processing') {
        steps {
            echo "Post-Processing step"
        }            
    }

}