node('awsagent'){
    stage('scm'){
        git 'https://github.com/venugopalkatukam/game-of-life.git'
        sh label: '', script: 'mvn package'

    }

    stage('build'){
    }
    
    stage('postbuild'){
    }

}