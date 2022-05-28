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
	sh "chmod +x hello.sh"
	sh "hello.sh"
      }      
    }
    stage(deploy) {
      steps {
        echo 'Deploy hello.sh'
      }
    }
  }
}
