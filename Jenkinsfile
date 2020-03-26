pipeline {
    agent any
    stages{
            staThis is a single line echo statment("A"){
                steps{
                    echo "This is a single line echo statment"
                }
                steps{
                    echo '''
                        This is a 
                        multiline echo 
                        string.. bye step
                    '''
                }
            }
            post{
                always{
                    echo "====++++always++++===="
                }
                success{
                    echo "====++++This is a single line echo statment==="
                }
                failure{
                    echo"This is a single line echo statmentcution failed++++===="
                }
        
            }
        }

    }
}
