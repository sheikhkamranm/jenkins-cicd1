# jenkins-cicd1
lab
my jenkins username = sheikhkamranm
password:

https://github.com/sheikhkamranm/springboot-with-docker.git

node {
stage("Git Clone"){

        git credentialsId: 'GIT_HUB_CREDENTIALS', url: 'https://github.com/sheikhkamranm/springboot-with-docker.git'
        
    }
}
