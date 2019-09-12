node ('master'){
stage ('clone the code'){
  git 'https://github.com/saranamsai/ansible.git'
}
  stage ('run the ansible playbook'){
    sh 'ansible-playbook ./saranamsai'
  }
}
