pipeline{
  agent any
stages {
  stage ('Git Cloning') {
    steps {
      echo "Cloning the Git from the Git Repo"
    }
  }
  stage ('Building war/jar file'){
    steps{
      echo "Building the jar file uisng the Maven"
    }
  }
  stage ('Code Review Using Sonar'){
    steps{
      echo "SonarQube"
    }
  }
  stage ('Docker Image and Pusing to the Docker Repo'){
    steps {
      echo "Creating Docker Image from Docker file and uploading to the Docker repo"
    }
  }
  stage ('Deploying the aplication in K8S cluster'){
    steps {
      echo "Application deployed into the K8S cluster"
    }
  }
  stage ('Email triggering to the stakeholders') {
    steps {
      echo "Email triggered to the stakeholders"
    }
  }
}
}
