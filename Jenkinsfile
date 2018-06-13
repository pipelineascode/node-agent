node{
	checkout([$class: 'GitSCM', 				
				branches: [[name: "origin/master"]], 
				userRemoteConfigs: [[
                url: 'https://github.com/pipelineascode/node-agent.git']],
				workspace: 'z:\\node-foo'
				])
	stage('Build'){
		echo 'Hello World 1'
	}
}
