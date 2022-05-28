pipeline {
  agent any
  stages {
    stage(build) {
      steps {
        echo 'Build hello.sh'
      }
    }
    stage(test) {
      steps {
        echo 'Test hello.sh'
	ls
      }      
    }
    stage(deploy) {
      steps {
        echo 'Deploy hello.sh'
      }
    }
  }
}
