node{
	stage('checkout code')
	{
		checkout changelog: false, poll: false, scm: [$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'git', url: 'https://github.com/lturaga/project1.git']]]

	}
	
	stage('execute playbook')
	{
		sh 'echo ${workspace} && ls'
		
	
	}


}
