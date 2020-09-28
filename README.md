# docker-sonarqube

## Start sonarqube server

`docker-compose up -d`

## Run sonarqube analysis.

`cp run-sonar.sh.sample run-sonar.sh`

Edit run-sonar.sh change `<project_path>` with the complete path to the proyect to annalyse. 

`sh run-sonar.sh`

