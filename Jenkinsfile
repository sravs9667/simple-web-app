node {
    stage ('scm chekout'){
        git credentialsId: 'github1', url: 'https://github.com/sravs9667/simple-web-app.git'
    }
    stage ('build'){
        sh 'mvn -f pom.xml clean package'    
    }
    stage ('test'){
        echo 'test'
    }
    stage ('security scanner'){
        echo 'scanning'
    }
    stage ('approval'){
        echo 'approval'
    }
    stage ('deploy'){
        echo 'deploy'
    }
}
