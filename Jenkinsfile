pipeline{

    agent docker{
      image 'phpunit/phpunit'
    }


    stages{
        stage('unit test'){
            steps{
                echo 'this is the first job'
                sh 'phpunit --version'
            }
        }
    }

 
}
