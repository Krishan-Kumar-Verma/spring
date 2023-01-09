pipeline 
{
    agent any
    tools{
        maven "M3"
    }

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App'
                git 'https://github.com/Krishan-Kumar-Verma/SpringBoot-Demo.git'
                echo 'This is stage for building the project'
                bat 'mvn clean'
            }
        }

        stage('Test') 
        {
            steps
            {
                git 'https://github.com/Krishan-Kumar-Verma/SpringBoot-Demo.git'
                echo 'This is stage for Test Execution'
                bat 'mvn clean'
            }
        }
    }
}
