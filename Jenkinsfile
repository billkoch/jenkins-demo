node {
  git 'https://github.com/billkoch/jenkins-demo.git'
  stage 'Build'
  sh './gradlew clean assemble'

  stage 'Test'
  sh './gradlew check'
}
