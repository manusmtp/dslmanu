// Jenkinsfile

pipeline {
    agent any
    stages {
        stage('Create Radio Buttons Job') {
            steps {
                script {
                    jobDsl scriptText: '''
                        job('MyRadioButtonsJob') {
                            parameters {
                                extendedChoice(name: 'DeployTo', description: 'Select the environment to deploy to', type: 'PT_RADIO', value: 'Dev,Test,Stage', visibleItemCount: 5)
                            }
                            // Other job configuration steps...
                        }
                    '''
                }
            }
        }
    }
}
