[![Build Status](http://65.0.108.6:8080/buildStatus/icon?job=maven-demo)](http://65.0.108.6:8080/job/maven-demo/)
# maven-employee-web-application
maven-employee-web-application
# How to build
docker build --build-arg git_url=https://github.com/kunchalavikram1427/maven-employee-web-application.git --build-arg project_name=maven-employee-web-application  --build-arg artifact_id=employee -t employee:4.0 .
