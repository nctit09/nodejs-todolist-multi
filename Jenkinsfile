 pipeline {
     agent any
     stages {
            stage("Begin github from branch Development") {
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