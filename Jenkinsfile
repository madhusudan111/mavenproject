pipeline{
    agent any
    stages{
        stage(checkout){
            steps{
               git branch: 'develop', changelog: false, poll: false, url: 'https://github.com/madhusudan111/javaproject-IMP.git' 
            }
        }
    }
}
