node {

    stage('Pre_Processing') {
        echo "Pre-Processing step"
    }

    stage('Building') {
        sh 'pwd'
        sh '\rm -r gradle-hello-world'
        sh 'git clone https://github.com/rrajen/gradle-hello-world.git'
        sh 'ls -l'
        sh 'cd gradle-hello-world && gradle -q helloWorld'           
    }

    stage('Post_Processing') {
        echo "Post-Processing step"           
    }

}