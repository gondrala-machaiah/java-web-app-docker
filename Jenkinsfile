node{
      stage ("Git Clone") {

            git url:'https://github.com/gondrala-machaiah/java-web-app-docker.git', branch: 'master'
      }

        stage ("maven clean package"){

        def mavenHome= tool name:"maven 3.8.6"
        sh "${mavenHome}/bin/mvn clean package"
        }


}
