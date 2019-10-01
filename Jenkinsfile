node('UBUNTU'){
    stage('GIT'){
        git 'https://github.com/kavya-4/jenkins.git'
    }
    stage('package'){
        sh 'mvn package' 
    }
}