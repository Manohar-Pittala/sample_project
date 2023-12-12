pipeline {
  stages{
    stage (checkout){
     steps{
       script{
         checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Manohar-Pittala/sample_project.git']])
        }
     }
  }
}
}
