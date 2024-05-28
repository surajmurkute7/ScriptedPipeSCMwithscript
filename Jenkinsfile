node {
    
    stage('fetching the code') { 
        git 'https://github.com/surajmurkute7/maven_Project.git'
        
    }
    stage('Build'){
                sh 'mvn clean package'
            
    }
   stage('Test'){
                
            echo "This is testing phase"
    } 
}

