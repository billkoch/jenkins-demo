node {
  stage 'Build'
  sh './gradlew clean assemble'

  stage 'Test'
  sh './gradlew check'
}
