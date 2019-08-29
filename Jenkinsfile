pipeline {
ageny any
stages {
stage('git') {
steps {
git 
}
}//stage git
stage('build'){
steps {
sh 'mvn package'
}//stage build
stage('Ansible'){
steps {
ansible-playbook tomcat.yml
}
}//stage ansible
}//stages
}//pipeline
