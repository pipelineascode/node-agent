node{
	ws("z:\\node-foo") {
		checkout([$class: 'GitSCM', 				
					branches: [[name: "origin/master"]], 
					userRemoteConfigs: [[
					url: 'https://github.com/pipelineascode/node-agent.git']]
					])
		stage('Build'){
			echo 'Hello World 1'
		}
	}
}
