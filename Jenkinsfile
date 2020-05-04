node {
    stage('Clone') {
        git 'https://github.com/remiliance/PlaybookDeployJar.git'
    }
    stage('Ansible') {
    sh 'ansible-playbook -i inventaire.ini playbook.yml'
    }
}
