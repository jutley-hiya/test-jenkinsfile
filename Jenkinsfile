pipeline {

  agent any

  stages {
    stage('Test') {
      echo "Running tests..."
      sleep 0.5
      echo "Tests pass"
    }
    stage('Build') {
      echo "Building Docker image..."
      sleep 0.5
      echo "Build complete"
    }
    stage('Deploy') {
      def regions = ["use1", "usw2", "cac1", "sae1", "euc1", "apse1", "apse2"]
      regions.each { r ->
        echo "Deploying to $r"
        sleep 0.5
        echo "Done"
      }
    }
    stage('Cleanup') {
      echo "Scubba dub dub"
    }
  }
}
