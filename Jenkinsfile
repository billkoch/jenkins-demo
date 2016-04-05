node {
  stage 'Build'
  sh './gradlew clean assemble'

  stage 'TEst'
  sh './gradlew check'
}
