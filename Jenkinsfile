pipeline {
    agent any
    parameters {
        string (description: 'enter ami_id', name: 'ami_id')
    }
    stages {
        stage ('build') {
           steps {
           //git url: 'https://github.com/usman6745/ec2-launch-jenkins.git'
           // Show the select input modal
           input "do you want proceed"
            echo "hello from stage two"
            echo "enter your name"
            read name
            echo $name   
               
               echo $amid_id
    
           
           }
        }
   }
}   
