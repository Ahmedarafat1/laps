pipeline {
  agent any
  stages {
    stage('Biuld') {
      steps {
        sh 'echo "Hello world"'
        sh ''' 
	    echo “Multiline shell steps works too”
	    ls -lah
	   ''' 
      }
    }

  }
}
