pipeline{
	agent any
	stages{
		stage ('Build') {
		steps {
		sh 'gradle build'
		}
	     }
		steps {
		sh 'gradle run'
	}
     }
  }
}