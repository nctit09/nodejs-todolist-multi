 pipeline {
     agent any
     stages {
            stage("Get code gitlab") {
               steps {
                echo 'gitlab'
                git branch: 'main', url: 'https://gitlab.com/cscmobistudios/ct_demo_nodejs_todolist.git'       
               }
            }
            stage("Build Dockerfile"){
                steps{
                    
                }
            }
        }
    }