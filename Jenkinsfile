pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
    tools{
       nodejs 'nodejs' 
    }
    

    stages{
<<<<<<< HEAD
        stage('build'){
=======
        stage(‘build-the-app'){
>>>>>>> 893666b8da24f67c4ef5731d4d543a4882b355cd
            steps{
                echo 'this is the build job'
                sh 'npm install'
            }
        }
<<<<<<< HEAD
        stage('test'){
=======
        stage('test-the-app'){
>>>>>>> 893666b8da24f67c4ef5731d4d543a4882b355cd
            steps{
                echo 'this is the test job'
                sh 'npm test'
            }
        }
<<<<<<< HEAD
        stage('package'){
            steps{
                echo 'this is the package job'
                sh 'npm run package'
=======
        stage(‘package-the-app'){
            steps{
                echo 'this is the package job'
                sh ‘npm run package’
>>>>>>> 893666b8da24f67c4ef5731d4d543a4882b355cd
            }
        }
    }
    
    post{
        always{
            echo 'this pipeline has completed...'
        }
        
    }
    
}
