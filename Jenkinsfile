node {
    stage('clone'){
   //     git 'https://github.com/remyg0656/JavaHelloGreg.git'
        git branch: 'main', url: 'https://github.com/remyg0656/JavaHelloGreg.git'
        
    }
     stage('build'){
        sh label: '', script: 'javac HelloGreg.java'
    }
    stage('run'){
        sh label: 'main', script: 'java HelloGreg'
    }
}
