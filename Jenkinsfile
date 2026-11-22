pipeline
{
    agent any
    {
        stages{
            stage{
            
            steps(Checkout)
            {
                echo "Checking out the code from the repository"
            }
            }
        
        stage{

            steps(Buid)
            {
                echo "Building the code"
            }
        }
        stage{

            steps(Test)
            {
                echo "Running the tests"
            }
        }
        stage{
            steps(Deploy)
            {
                echo "Deploying the application"
               }
                  }
        }
        }
    }
