pipeline{
  agent any
  
    stages{
      stage('clone'){
        steps{
          git url:"https://github.com/Jnyanesh/jenkins-simple-demo2",
          branch:"main"
        }
      }
      
      stage('Run Script'){
        steps{
          sh "chmod +x script.sh"
          sh "./script.sh"
        }
      }
      
      stage('Run Python file'){
        steps{
          sh "python3 file.py"
        }
      }
      
    }
  }

  
    
