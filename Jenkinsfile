pipeline {
    agent {
    kubernetes {
    // This is a YAML representation of the Pod, to allow setting any values not supported as fields.
      yamlFile 'k8s/k8sPodTemplate.yaml' // Declarative agents can be defined from YAML.
    }
  }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World trigger '
            }
        }
    }
}