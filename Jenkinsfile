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
        stage('two'){
            steps{
                echo 'this is the second job'
                sh 'uptime'
                sleep 9
            }
        }
        stage('three'){
            steps{
                echo 'this is the third job'
                sh 'uptime'
                sleep 7
            }
        }
    }

 
}
