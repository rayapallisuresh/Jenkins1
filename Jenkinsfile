pipeline{
    agent{
        any
    }
    stages{
        stage("1st stage"){
            steps{
                echo "========executing A========"
            }
            post{
                always{
                    echo "========always after stage ========"
                }
                success{
                    echo "========A executed successfully after stage ========"
                }
                failure{
                    echo "========A execution failed after stage========"
                }
            }
        }
    }
    post{
        always{
            echo "========end of stage -- always========"
        }
        success{
            echo "======== end of stage --  pipeline executed successfully ========"
        }
        failure{
            echo "========end of stage --  pipeline execution failed========"
        }
    }
}
