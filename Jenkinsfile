node{
	checkout([$class: 'GitSCM', 				
				branches: [[name: "origin/master"]], 
				userRemoteConfigs: [[
                url: 'https://github.com/pipelineascodecourse/pipeline-triggers-pollSCM.git']],
				workspace: 'z:\\node-foo'
				])
	stage('Build'){
		echo 'Hello World 1'
	}
}
