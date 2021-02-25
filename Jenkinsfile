node {
  stage("Build"){
    echo "Build Stage"
    sh '.gradlew build --no-daemon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
  }
}
