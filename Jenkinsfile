node {
    stage ('Checkout Repository') {
           deleteDir()
           checkout scm
      // Get our repo cloned and prepped for action
     }
    stage ('Render Configurations') {
      sh 'ansible-playbook generate_configurations.yaml'
     }
    stage ('Unit Testing') {
    // Do some kind of "linting" on our code to make sure we didn't bugger a
     }
    stage ('Deploy Configurations to Dev') {
     // Push the configurations out to the dev environment
     }
    stage ('Functional/Integration Testing') {
     // Ping stuff and make sure we didn't blow up dev!
     }
    stage ('Promote Configurations to Production') {
     // Ping stuff and make sure we didn't blow up dev!
     }
    stage ('Production Functional/Integration Testing') {
     // Ping stuff and make sure we didn't blow up prod!
     }
   }
node {
     stage ('Checkout Repository') {
          deleteDir()
          checkout scm
     }
    }
