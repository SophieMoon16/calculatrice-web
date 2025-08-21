pipeline {
  agent any
  stages 
  {
    stage('Build') { steps { echo "Début du Build" } }
    stage('Test') { steps  {script { if (fileExists('index.html')) {echo 'Yes, index.html exists'} else {echo 'No, index.html does not exist'}}}}
  }
}
