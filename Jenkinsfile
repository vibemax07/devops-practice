pipeline
{
    agent any
    {
        stages{
            steps(Checkout)
            {
                echo "Checking out the code from the repository"
            }
            steps(Buid)
            {
                echo "Building the code"
            }
            steps(Test)
            {
                echo "Running the tests"
            }
            steps(Deploy)
            {
                echo "Deploying the application"
            }
        }
    }
}