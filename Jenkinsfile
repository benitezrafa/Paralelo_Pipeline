pipeline {
    agent any

    tools {NodeJS 'node'}

    stages {

        stage('Cypress Parallel Test Suite') {
            parallel {
                stage('Slave 1') {
                    agent {
                        label "Agent1_1"
                    }
                    steps {
                        git url: 'https://github.com/benitezrafa/Paralelo_Pipeline.git'
                        bat 'npm install'
                        bat 'npm update'                       
                        bat 'npx cypress run --record --key f8643467-abd6-4691-aef8-721285385df0  --parallel'
                    
                    }
                }

                stage('Slave 2') {
                    agent {
                        label "Agent1_2"
                    }
                    steps {
                        git url: 'https://github.com/benitezrafa/Paralelo_Pipeline.git'
                        bat 'npm install'
                        bat 'npm update'                       
                        bat 'npx cypress run --record --key f8643467-abd6-4691-aef8-721285385df0  --parallel'
                    
                    }
                }

                stage('Slave 3') {
                    agent {
                        label "Agent1_3"
                    }
                    steps {
                        git url: 'https://github.com/benitezrafa/Paralelo_Pipeline.git'
                        bat 'npm install'
                        bat 'npm update'                       
                        bat 'npx cypress run --record --key f8643467-abd6-4691-aef8-721285385df0  --parallel'
                    
                    }
                }

                stage('Slave 4') {
                    agent {
                        label "Agent1_4"
                    }
                    steps {
                        git url: 'https://github.com/benitezrafa/Paralelo_Pipeline.git'
                        bat 'npm install'
                        bat 'npm update'                       
                        bat 'npx cypress run --record --key f8643467-abd6-4691-aef8-721285385df0  --parallel'
                    
                    }
                }

                stage('Slave 5') {
                    agent {
                        label "Agent1_5"
                    }
                    steps {
                        git url: 'https://github.com/benitezrafa/Paralelo_Pipeline.git'
                        bat 'npm install'
                        bat 'npm update'                       
                        bat 'npx cypress run --record --key f8643467-abd6-4691-aef8-721285385df0  --parallel'
                    
                    }
                }

                
   
                  
            }

             
        }

    }
            
}