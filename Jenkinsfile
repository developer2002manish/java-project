node {
    stage('Clone the Java Project') {
        git url: 'https://github.com/developer2002manish/java-project.git'
    }

    stage('Build the Java Project') {
        sh 'javac Test.java'
    }

    stage('Run the Java Project') {
        sh 'java Test'
    }

    stage('Successfully Done') {
        echo "Congratulations, build and run done!"
    }
}
