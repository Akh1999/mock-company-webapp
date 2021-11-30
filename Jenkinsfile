pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
   stages{
        stage('Build'){
            sh './gradle assemble'
        }
        stage('Test'){
            sh './gradle test'
        }
   }
}
