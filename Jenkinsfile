  def DOCKER_HUB_ACCOUNT = '<docker-hub-username>'
  def DOCKER_IMAGE_NAME = 'k8s-example'

  echo 'Building Docker image'
  stage('BuildImage') 
  def app = docker.build("${DOCKER_HUB_ACCOUNT}/${DOCKER_IMAGE_NAME}", '.')

